
## Flights Day View for multicity search Schema

```
/flights/multicity
```

A schema definition for the flights day-view microsite supported query parameters

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted |  |

## Flights Day View for multicity search Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [adultsv2](#adultsv2) | `integer` | **Required**  | No | `1` | Flights Day View for multicity search (this schema) |
| [cabinclass](#cabinclass) | `enum` | **Required**  | No | `"economy"` | Flights Day View for multicity search (this schema) |
| [childrenv2](#childrenv2) | `integer` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [currency](#currency) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [date0](#date0) | `string` | **Required**  | No |  | Flights Day View for multicity search (this schema) |
| [date1](#date1) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [date2](#date2) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [date3](#date3) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [date4](#date4) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [date5](#date5) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [destination0](#destination0) | `string` | **Required**  | No |  | Flights Day View for multicity search (this schema) |
| [destination1](#destination1) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [destination2](#destination2) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [destination3](#destination3) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [destination4](#destination4) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [destination5](#destination5) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [infants](#infants) | `integer` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [locale](#locale) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [market](#market) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [origin0](#origin0) | `string` | **Required**  | No |  | Flights Day View for multicity search (this schema) |
| [origin1](#origin1) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [origin2](#origin2) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [origin3](#origin3) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [origin4](#origin4) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| [origin5](#origin5) | `string` | Optional  | No |  | Flights Day View for multicity search (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

### adultsv2

Number of adult passengers. Adults have to be 16 years old or older.

`adultsv2`

* is **required**
* type: `integer`
* default: `1`
* defined in this schema

#### adultsv2 Type


`integer`

* minimum value: `1`






### cabinclass

Fare class

`cabinclass`

* is **required**
* type: `enum`
* default: `"economy"`
* defined in this schema

The value of this property **must** be equal to one of the [known values below](#cabinclass-known-values).

#### cabinclass Known Values
| Value | Description |
|-------|-------------|
| `economy` |  |
| `premiumeconomy` |  |
| `business` |  |
| `first` |  |




### childrenv2

Number of child passengers. The value must be in the format integer|integer.. where each number is the age of the child passenger

`childrenv2`

* is optional
* type: `integer`
* defined in this schema

#### childrenv2 Type


`integer`







### currency

The desired currency for the flights search results

`currency`

* is optional
* type: `string`
* defined in this schema

#### currency Type


`string`







### date0

Outbound date in the format yymmdd

`date0`

* is **required**
* type: `string`
* defined in this schema

#### date0 Type


`string`







### date1

Outbound date in the format yymmdd

`date1`

* is optional
* type: `string`
* defined in this schema

#### date1 Type


`string`







### date2

Outbound date in the format yymmdd

`date2`

* is optional
* type: `string`
* defined in this schema

#### date2 Type


`string`







### date3

Outbound date in the format yymmdd

`date3`

* is optional
* type: `string`
* defined in this schema

#### date3 Type


`string`







### date4

Outbound date in the format yymmdd

`date4`

* is optional
* type: `string`
* defined in this schema

#### date4 Type


`string`







### date5

Outbound date in the format yymmdd

`date5`

* is optional
* type: `string`
* defined in this schema

#### date5 Type


`string`







### destination0

Location code for the destination

`destination0`

* is **required**
* type: `string`
* defined in this schema

#### destination0 Type


`string`







### destination1

Location code for the destination

`destination1`

* is optional
* type: `string`
* defined in this schema

#### destination1 Type


`string`







### destination2

Location code for the destination

`destination2`

* is optional
* type: `string`
* defined in this schema

#### destination2 Type


`string`







### destination3

Location code for the destination

`destination3`

* is optional
* type: `string`
* defined in this schema

#### destination3 Type


`string`







### destination4

Location code for the destination

`destination4`

* is optional
* type: `string`
* defined in this schema

#### destination4 Type


`string`







### destination5

Location code for the destination

`destination5`

* is optional
* type: `string`
* defined in this schema

#### destination5 Type


`string`







### infants

Number of infant passengers. An infant is 1 year old or younger.

`infants`

* is optional
* type: `integer`
* defined in this schema

#### infants Type


`integer`







### locale

The desired locale for the flights search results

`locale`

* is optional
* type: `string`
* defined in this schema

#### locale Type


`string`







### market

The market for which the flights search will be performed.

`market`

* is optional
* type: `string`
* defined in this schema

#### market Type


`string`







### origin0

Location code for the origin

`origin0`

* is **required**
* type: `string`
* defined in this schema

#### origin0 Type


`string`







### origin1

Location code for the origin

`origin1`

* is optional
* type: `string`
* defined in this schema

#### origin1 Type


`string`







### origin2

Location code for the origin

`origin2`

* is optional
* type: `string`
* defined in this schema

#### origin2 Type


`string`







### origin3

Location code for the origin

`origin3`

* is optional
* type: `string`
* defined in this schema

#### origin3 Type


`string`







### origin4

Location code for the origin

`origin4`

* is optional
* type: `string`
* defined in this schema

#### origin4 Type


`string`







### origin5

Location code for the origin

`origin5`

* is optional
* type: `string`
* defined in this schema

#### origin5 Type


`string`






