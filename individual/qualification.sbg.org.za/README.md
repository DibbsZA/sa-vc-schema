# qualification.sbg.org.za

## Purpose

Attestation of Educational Qualifications

## Version - 1.0.0

## Date - 2019/11/16

## Status - **PROPOSED**

### Ledger Record Id: *not ledgered*

## Attribute Information and Format Convention

| Attribute Name     | Data Type | Example                       | Description                         |
|--------------------|-----------|-------------------------------|-------------------------------------|
| institution_name   | string    | `University of Witwatersrand` | Institution Name                    |
| qualification_code | string    | `INS-8728346`                 | Institution Course Code             |
| qualification_name | string    | `Bsc Computing`               | Name of qualification               |
| date_of_completion | string    | `2019-11-27`                  | Date of completion of qualification |
| nqf_level          | string    | `9`                           | SAQUA NQF Level or Evivalent        |
| overall_mark       | string    | `PASS`                        | Result achieved                     |
| country_of_issue   | string    | `ZAF`                         | Country of Educational Institution  |

### Schema

```json
{
  "data": {
    "attr_names": [
      "institution_name",
      "qualification_code",
      "qualification_name",
      "date_of_completion",
      "nqf_level",
      "overall_mark",
      "country_of_issue"
    ],
    "name": "qualification.sbg.org.za",
    "version": "1.0.0"
  }
}
```
