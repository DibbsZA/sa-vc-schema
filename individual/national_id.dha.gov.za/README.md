# national_id.dha.gov.za

## Purpose

South African National Identity attributes returned by the the HANIS API.

## Version - 1.0.1

## Date - 2019/11/14

## Status - **PROPOSED**

### Ledger Record Ids: 

- **STAGING** `Q5rSXAimLTtZf94mxS4E3j:2:Standard Bank1573807634108:1.0`
- **LIVE**

## Attribute Information and Format Convention

| Attribute Name   | Data Type | Example                    | Description                                    |
|------------------|-----------|----------------------------|------------------------------------------------|
| identity_number  | string    | `9404271234081`            | 13 digit National Identity Number              |
| names            | string    | `FREEDOM SISTER`           | All Given Name(s)                              |
| surname          | string    | `AFRICA`                   | Surname                                        |
| sex              | string    | `F`                        | Gender classification `F`, `M`, `U`            |
| country_of_birth | string    | `ZAF`                      | `ISO Country Code` of Birthplace Country       |
| date_of_birth    | string    | `1994-04-27`               | Birth Date (`YYYY-MM-DD`)                      |
| citizen_status   | string    | `CITIZEN` or `NON-CITIZEN` | RSA Citizenship Status                         |
| nationality      | string    | `ZAF`                      | `ISO Country Code` of Citizenship Country      |
| nationality      | string    | `ZAF`                      | `ISO Country Code` of Citizenship Country      |

### Schema

```json
{
  "data": {
    "attr_names": [
      "identity_number",
      "names",
      "surname",
      "sex",
      "country_of_birth",
      "date_of_birth",
      "citizen_status",
      "nationality"
    ],
    "name": "national_id.dha.gov.za",
    "version": "1.0.1"
  }
}
```
