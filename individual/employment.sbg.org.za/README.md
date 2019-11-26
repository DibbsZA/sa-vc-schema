# employment.sbg.org.za

## Purpose

Record of Employment

## Version - 1.0.1

## Date - 2019/11/26

## Status - **PROPOSED**

### Ledger Record Ids

- **STAGING** ``
- **LIVE** ``

## Attribute Information and Format Convention

| Attribute Name           | Data Type | Example         | Description                                       |
|--------------------------|-----------|-----------------|---------------------------------------------------|
| employer_name            | string    | `ACME Corp`     | Business Name                                     |
| employee_number          | string    | `INS-8728346`   | Employee Employment Number                        |
| postion_held             | string    | `Clerk`         | Job Title / Description of Position Held          |
| employee_name            | string    | `Joe Blogs`     | Person Name                                       |
| employee_identity_number | string    | `5235345252354` | Person Identity Number                            |
| start_date               | string    | `1999-01-01`    | Start of Engagement                               |
| end_date                 | string    | `2000-12-30`    | End Of Engagement                                 |
| employment_status        | string    | `RESIGNED`      | Current/Last employment status with this employer |

### Schema

```json
{
  "data": {
    "attr_names": [
      "employer_name",
      "employee_number",
      "postion_held",
      "employee_name",
      "employee_identity_number",
      "start_date",
      "end_date",
      "employment_status"
    ],
    "name": "employment.sbg.org.za",
    "version": "1.0.1"
  }
}
```
