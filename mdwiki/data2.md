# Product Data Hub US (PDH-US)

This repository maintains US books information ...

## C_PRODUCT

Maintains core product information describing its type / sub-type.

Key | Value
---|---
Row Count | **12,914**

### DH_ID 

#### Definition
Autogenerated Row ID

Data Type |Constraint 
---|---
NUMBER |NOT NULL

#### Analysis

Type | Count | %
---|---|---
Null | 0 | 0%
Non-null | 12,914 | 100%
- Duplicate | 0 | 0%
- Distinct | 12,914 | 100%
-- Non-unique | 0 | 0%
-- Unique | 12,914 | 100%
--

Min | Median | Max
---|---|---
11341045 | 554270 | 9017094

* Null: all data that are empty or have "Null" as their value.
* Non-null: all data that are not empty or null (duplicate + distinct)
  * Duplicate: the number of values that are the same as other values in the list
  * Distinct: the number of non-null values that are different from each other (non-unique + unique)
    * Non-unique: the number of values that have at least one duplicate in the list
    * Unique: the number of values that have no duplicates


### DH_TYPE_ID

#### Definition
Refers to Product Type. Values can be derived from C_REFERENCE_DATA

Data Type |Constraint 
---|---
NUMBER |NOT NULL

#### Analysis

Type | Count | %
---|---|---
Null | 0 | 0%
Non-null | 12,914 | 100%
- Duplicate | 12,913 | 99.99%
- Distinct | 1 | 0.01%
-- Non-unique | 1 | 0.01%
-- Unique | 0 | 0%
--

Min | Median | Max
---|---|---
1 | 1 | 1


### DH_SUBTYPE_ID
#### Definition
Refers to Product Type. Values can be derived from C_REFERENCE_DATA

Data Type |Constraint 
---|---
NUMBER |-

#### Analysis

Type | Count | %
---|---|---
Null | 12,842 | 99.44%
Non-null | 72 | 0.56%
- Duplicate | 70 | 0.54%
- Distinct | 2 | 0.02%
-- Non-unique | 2 | 0.02%
-- Unique | 0 | 0%
--

Min | Median | Max
---|---|---
17647492 | 117647492 | 17647494
--
Value | Count | % | Remarks
---|---|---|---
Null | 12,842 | 99.44%
17647492 | 58 | 0.45% | E4
17647294 | 14 | 0.11% | LS

#### Related to

* Product Sub-type Codes from C_REFERENCE_DATA

