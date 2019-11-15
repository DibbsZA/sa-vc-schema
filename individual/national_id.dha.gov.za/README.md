# national_id.dha.gov.za**

## Purpose

South African National Identity attributes returned by the the HANIS API.

## Version - 1.0.1

## Date - 2019/11/14

## Status - **PROPOSED**

### Ledger Record Id: *not ledgered*

## Attribute Information and Format Convention

| Attribute Name   | Data Type | Example                    | Description                                    |
|------------------|-----------|----------------------------|------------------------------------------------|
| identity_number  | string    | `9404271234081`            | 13 digit National Identity Number              |
| names            | string    | `FREEDOM SISTER`           | All Given Name(s)                              |
| first_name       | string    | `FREEDOM`                  | First Name only                                |
| middle_names     | string    | `SISTER`                   | Middle Name(s)                                 |
| surname          | string    | `AFRICA`                   | Surname                                        |
| last_name        | string    | `AFRICA`                   | Last Name (Same as Surname)                    |
| family_name      | string    | `AFRICA`                   | Family Name (Same as Last Name)                |
| full_name        | string    | `FREEDOM SISTER AFRICA`    | Full unabridged name in culture specific order |
| sex              | string    | `F`                        | Gender classification `F`, `M`, `U`            |
| country_of_birth | string    | `ZAF`                      | `ISO Country Code` of Birthplace Country       |
| date_of_birth    | string    | `1994-04-27`               | Birth Date (`YYYY-MM-DD`)                      |
| citizen_status   | string    | `CITIZEN` or `NON-CITIZEN` | RSA Citizenship Status                         |
| nationality      | string    | `ZAF`                      | `ISO Country Code` of Citizenship Country      |

### Schema

```json
{
  "data": {
    "attr_names": [
      "identity_number",
      "names",
      "first_name",
      "middle_names",
      "surname",
      "last_name",
      "family_name",
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
