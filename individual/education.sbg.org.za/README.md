# education.sbg.org.za

## Purpose

Attestation of Educational Achievements

## Version - 1.0

## Date - 2019/11/29

## Status - **PROPOSED**

### Ledger Record Ids:

| Network     | Ledger ID                                              |
|-------------|--------------------------------------------------------|
| **LIVE**    | _not ledgered yet_                                     |
| **STAGING** | `38KXQS8YISJTTP4KZPTJKQ:2:WITS.AC.ZA1575058609571:1.0` |

## Attribute Information and Format Convention

| Attribute Name          | Data Type | Example                       | Description                               |
|-------------------------|-----------|-------------------------------|-------------------------------------------|
| institution_name        | string    | `University of Witwatersrand` | Institution Name                          |
| institution_type        | string    | `University`                  | Institution Type                          |
| qualification_code      | string    | `INS-8728346`                 | Institution Course Code                   |
| qualification_name      | string    | `Bsc Computing`               | Name of qualification                     |
| qualification_type      | string    | `Degree`                      | Type of qualification                     |
| student_name            | string    | `JO BLOGGER`                  | Name of the student                       |
| student_identity_number | string    | `9404275000089`               | National ID or Passport number of student |
| student_number          | string    | `2019-ICT-200001`             | Institution assigned number               |
| final_year              | string    | `Degree`                      | Date of last attendance/graduation        |
| completion_status       | string    | `COMPLETED`                   | 'Years completed', 'COMPLETED'            |
| nqf_level               | string    | `9`                           | SAQUA NQF Level or Equivalent             |
| country_of_issue        | string    | `South Africa`                | Country Name of Institution               |

### Schema

```json
{
  "data": {
    "attr_names": [
      "institution_name",
      "institution_type",
      "qualification_code",
      "qualification_name",
      "qualification_type",
      "student_name",
      "student_identity_number",
      "student_number",
      "final_year",
      "completion_status",
      "nqf_level",
      "country_of_issue"
    ],
    "name": "education.sbg.org.za",
    "version": "1.0"
  }
}
```
