# Object - StockPlan Schema

```txt
Objects.StockPlan.schema.json#/properties/stock_plans/items
```

Object describing a plan which stock options are issued from

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                        |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :-------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [CapTable.schema.json*](../../schema/CapTable.schema.json "open original schema") |

## items Type

`object` ([Object - StockPlan](captable-properties-captable---objectsstockplanschemajson-array-object---stockplan.md))

all of

*   [Object - BaseObject](issuer-allof-object---baseobject.md "check type definition")

# items Properties

| Property                                            | Type          | Required | Nullable       | Defined by                                                                                                                   |
| :-------------------------------------------------- | :------------ | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [object_type](#object_type)                         | Not specified | Optional | cannot be null | [Object - StockPlan](stockplan-properties-object_type.md "Objects.StockPlan.schema.json#/properties/object_type")            |
| [plan_name](#plan_name)                             | `string`      | Required | cannot be null | [Object - StockPlan](stockplan-properties-plan_name.md "Objects.StockPlan.schema.json#/properties/plan_name")                |
| [board_approval_date](#board_approval_date)         | `string`      | Optional | cannot be null | [Object - StockPlan](issuer-properties-type---datestring.md "Types.DateString.schema.json#/properties/board_approval_date")  |
| [current_shares_reserved](#current_shares_reserved) | `object`      | Required | cannot be null | [Object - StockPlan](stockplan-properties-type---numeric.md "Types.Numeric.schema.json#/properties/current_shares_reserved") |
| [stock_class_id](#stock_class_id)                   | `string`      | Required | cannot be null | [Object - StockPlan](stockplan-properties-stock_class_id.md "Objects.StockPlan.schema.json#/properties/stock_class_id")      |
| [id](#id)                                           | Not specified | Optional | cannot be null | [Object - StockPlan](stockplan-properties-id.md "Objects.StockPlan.schema.json#/properties/id")                              |
| [comments](#comments)                               | Not specified | Optional | cannot be null | [Object - StockPlan](stockplan-properties-comments.md "Objects.StockPlan.schema.json#/properties/comments")                  |

## object_type



`object_type`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-object_type.md "Objects.StockPlan.schema.json#/properties/object_type")

### object_type Type

unknown

### object_type Constraints

**constant**: the value of this property must be equal to:

```json
"STOCK_PLAN"
```

## plan_name

Name for the stock plan

`plan_name`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-plan_name.md "Objects.StockPlan.schema.json#/properties/plan_name")

### plan_name Type

`string`

## board_approval_date

Type representing an ISO-8601 date, e.g. 2022-01-28

`board_approval_date`

*   is optional

*   Type: `string` ([Type - DateString](issuer-properties-type---datestring.md))

*   cannot be null

*   defined in: [Object - StockPlan](issuer-properties-type---datestring.md "Types.DateString.schema.json#/properties/board_approval_date")

### board_approval_date Type

`string` ([Type - DateString](issuer-properties-type---datestring.md))

### board_approval_date Constraints

**date**: the string must be a date string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")

## current_shares_reserved

Type representation of a number (up to 10 decimal places supported by the spec)

`current_shares_reserved`

*   is required

*   Type: `object` ([Type - Numeric](stockplan-properties-type---numeric.md))

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-type---numeric.md "Types.Numeric.schema.json#/properties/current_shares_reserved")

### current_shares_reserved Type

`object` ([Type - Numeric](stockplan-properties-type---numeric.md))

## stock_class_id

Id of the StockClass object this plan is composed of

`stock_class_id`

*   is required

*   Type: `string`

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-stock_class_id.md "Objects.StockPlan.schema.json#/properties/stock_class_id")

### stock_class_id Type

`string`

## id



`id`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-id.md "Objects.StockPlan.schema.json#/properties/id")

### id Type

unknown

## comments



`comments`

*   is optional

*   Type: unknown

*   cannot be null

*   defined in: [Object - StockPlan](stockplan-properties-comments.md "Objects.StockPlan.schema.json#/properties/comments")

### comments Type

unknown