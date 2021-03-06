
## Flights Day View supported query parameters Schema

```
/flights/day-view
```

A schema definition for the flights day-view microsite supported query parameters

| Abstract | Extensible | Status | Identifiable | Custom Properties | Additional Properties | Defined In |
|----------|------------|--------|--------------|-------------------|-----------------------|------------|
| Can be instantiated | No | Experimental | No | Forbidden | Permitted |  |

## Flights Day View supported query parameters Properties

| Property | Type | Required | Nullable | Default | Defined by |
|----------|------|----------|----------|---------|------------|
| [adultsv2](#adultsv2) | `integer` | **Required**  | No | `1` | Flights Day View supported query parameters (this schema) |
| [alternativedestinations](#alternativedestinations) | `string[]` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [alternativeorigins](#alternativeorigins) | `string[]` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [cabinclass](#cabinclass) | `enum` | **Required**  | No | `"economy"` | Flights Day View supported query parameters (this schema) |
| [childrenv2](#childrenv2) | `integer` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [currency](#currency) | `string` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [destination](#destination) | `string` | **Required**  | No |  | Flights Day View supported query parameters (this schema) |
| [inboundDate](#inbounddate) | `string` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [inboundaltsenabled](#inboundaltsenabled) | `boolean` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [infants](#infants) | `integer` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [locale](#locale) | `string` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [market](#market) | `string` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [origin](#origin) | `string` | **Required**  | No |  | Flights Day View supported query parameters (this schema) |
| [outboundDate](#outbounddate) | `string` | **Required**  | No |  | Flights Day View supported query parameters (this schema) |
| [outboundaltsenabled](#outboundaltsenabled) | `boolean` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [preferdirects](#preferdirects) | `boolean` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
| [rtn](#rtn) | `enum` | Optional  | No |  | Flights Day View supported query parameters (this schema) |
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






### alternativedestinations

An array of location codes which will be used as alternative destinations

`alternativedestinations`

* is optional
* type: `string[]`
* defined in this schema

#### alternativedestinations Type


Array type: `string[]`

All items must be of the type:
`string`










### alternativeorigins

An array of location codes which will be used as alternative origins

`alternativeorigins`

* is optional
* type: `string[]`
* defined in this schema

#### alternativeorigins Type


Array type: `string[]`

All items must be of the type:
`string`










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







### destination

Location code for the destination

`destination`

* is **required**
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







### inboundaltsenabled

Inlcuding nearby airports as an inbound place

`inboundaltsenabled`

* is optional
* type: `boolean`
* defined in this schema

#### inboundaltsenabled Type


`boolean`





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

* is **required**
* type: `string`
* defined in this schema

#### outboundDate Type


`string`







### outboundaltsenabled

Inlcuding nearby airports as an outbound place

`outboundaltsenabled`

* is optional
* type: `boolean`
* defined in this schema

#### outboundaltsenabled Type


`boolean`





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



