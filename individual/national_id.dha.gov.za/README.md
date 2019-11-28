# national_id.dha.gov.za

## Purpose

South African National Identity attributes returned by the the HANIS API.

## Version - 1.0.2

## Date - 2019/11/28

## Status - **PROPOSED**

### Ledger Record Ids:

| Network     | Ledger ID          |
|-------------|--------------------|
| **LIVE**    | _not ledgered yet_ |
| **STAGING** | `  `               |



## Attribute Information and Format Convention

| Attribute Name   | Data Type | Example                    | Description                               |
|------------------|-----------|----------------------------|-------------------------------------------|
| identity_number  | string    | `9404271234081`            | 13 digit National Identity Number         |
| names            | string    | `FREEDOM SISTER`           | All Given Name(s)                         |
| surname          | string    | `AFRICA`                   | Surname                                   |
| gender           | string    | `F`                        | Gender classification `F` or `M`          |
| country_of_birth | string    | `ZAF`                      | `ISO Country Code` of Birthplace Country  |
| date_of_birth    | string    | `1994-04-27`               | Birth Date (`YYYY-MM-DD`)                 |
| citizen_status   | string    | `CITIZEN` or `NON-CITIZEN` | RSA Citizenship Status                    |
| nationality      | string    | `ZAF`                      | `ISO Country Code` of Citizenship Country |
| marital_status   | bool      | `true` or `false`          | Married Status                            |

### Schema

```json
{
  "data": {
    "attr_names": [
      "identity_number",
      "names",
      "surname",
      "gender",
      "country_of_birth",
      "date_of_birth",
      "citizen_status",
      "nationality",
      "marital_status"
    ],
    "name": "national_id.dha.gov.za",
    "version": "1.0.2"
  }
}
```
