
## Flights Browse View supported parameters Schema

```
/flights/browse-view
```

A schema definition for the flights browse view microsite supported path and query parameters

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted |  |

## Flights Browse View supported parameters Properties

| Property | Type | Required | Nullable | Defined by |
|----------|------|----------|----------|------------|
| [adultsv2](#adultsv2) | `integer` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [childrenv2](#childrenv2) | `integer` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [currency](#currency) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [destination](#destination) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [inboundDate](#inbounddate) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [infants](#infants) | `integer` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [iym](#iym) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [locale](#locale) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [market](#market) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [origin](#origin) | `string` | **Required**  | No | Flights Browse View supported parameters (this schema) |
| [outboundDate](#outbounddate) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [oym](#oym) | `string` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [preferdirects](#preferdirects) | `boolean` | Optional  | No | Flights Browse View supported parameters (this schema) |
| [rtn](#rtn) | `enum` | Optional  | No | Flights Browse View supported parameters (this schema) |
| `*` | any | Additional | Yes | this schema *allows* additional properties |

### adultsv2

Number of adult passengers. Adults have to be 16 years old or older.

`adultsv2`

* is optional
* type: `integer`
* defined in this schema

#### adultsv2 Type


`integer`

* minimum value: `1`






### childrenv2

Number of child passengers. The value must be in the format integer|integer.. where each number is the age of the child passenger

`childrenv2`

* is optional
* type: `integer`
* defined in this schema

#### childrenv2 Type


`integer`







### currency

The desired currency for the carhire search results

`currency`

* is optional
* type: `string`
* defined in this schema

#### currency Type


`string`







### destination

Location code for the destination

`destination`

* is optional
* type: `string`
* defined in this schema

#### destination Type


`string`







### inboundDate

Inbound date in the format yymmdd

`inboundDate`

* is optional
* type: `string`
* defined in this schema

#### inboundDate Type


`string`







### infants

Number of infant passengers. An infant is 1 year old or younger.

`infants`

* is optional
* type: `integer`
* defined in this schema

#### infants Type


`integer`







### iym

Arrival date in the format: yymm

`iym`

* is optional
* type: `string`
* defined in this schema

#### iym Type


`string`







### locale

The desired locale for the carhire search results

`locale`

* is optional
* type: `string`
* defined in this schema

#### locale Type


`string`







### market

The market for which the carhire search will be performed.

`market`

* is optional
* type: `string`
* defined in this schema

#### market Type


`string`







### origin

Location code for the origin

`origin`

* is **required**
* type: `string`
* defined in this schema

#### origin Type


`string`







### outboundDate

Outbound date in the format yymmdd

`outboundDate`

* is optional
* type: `string`
* defined in this schema

#### outboundDate Type


`string`







### oym

Departure date in the format: yymm

`oym`

* is optional
* type: `string`
* defined in this schema

#### oym Type


`string`







### preferdirects

Will search only for direct flights if the value is true

`preferdirects`

* is optional
* type: `boolean`
* defined in this schema

#### preferdirects Type


`boolean`





### rtn

Trip type: 0 if oneway or 1 if return or multicity trip

`rtn`

* is optional
* type: `enum`
* defined in this schema

The value of this property **must** be equal to one of the [known values below](#rtn-known-values).

#### rtn Known Values
| Value | Description |
|-------|-------------|
| `0` |  |
| `1` |  |



