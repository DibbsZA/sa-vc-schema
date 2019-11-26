# qualification.sbg.org.za

## Purpose

Attestation of Educational Qualifications

## Version - 1.0.0

## Date - 2019/11/16

## Status - **PROPOSED**

### Ledger Record Id:

- **STAGING** `Q5rSXAimLTtZf94mxS4E3j:2:Standard Bank1573808083301:1.0`
- **LIVE**

## Attribute Information and Format Convention

| Attribute Name     | Data Type | Example                       | Description                         |
|--------------------|-----------|-------------------------------|-------------------------------------|
| institution_name   | string    | `University of Witwatersrand` | Institution Name                    |
| institution_type   | string    | `University`                  | Institution Type                    |
| qualification_code | string    | `INS-8728346`                 | Institution Course Code             |
| qualification_name | string    | `Bsc Computing`               | Name of qualification               |
| qualification_type | string    | `Degree`                      | Type of qualification               |
| final_year         | string    | `2019-11-27`                  | Date of last attendance/graduation  |
| completion_status  | string    | `COMPLETED`                   | 'Years completed', 'COMPLETED'      |
| nqf_level          | string    | `9`                           | SAQUA NQF Level or Equivalent       |
| country_of_issue   | string    | `South Africa`                | Country Name of Institution         |

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
      "final_year",
      "completion_status",
      "nqf_level",
      "country_of_issue"
    ],
    "name": "qualification.sbg.org.za",
    "version": "1.0.0"
  }
}
```
