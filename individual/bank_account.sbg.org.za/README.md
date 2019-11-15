# bank_account.sbg.org.za

## Purpose

Banking account details

## Version - 1.0.1

## Date - 2019/11/14

## Status - **PROPOSED**

### Ledger Record Id: *not ledgered*

## Attribute Information and Format Convention

| Attribute Name        | Data Type | Example         | Description                                                        |
|-----------------------|-----------|-----------------|--------------------------------------------------------------------|
| bank_name             | string    | `STANDARD BANK` | Name of the Bank                                                   |
| bank_code             | string    | `210001`        | BSVA Bank Routing Code                                             |
| account_holder_name   | string    | `BLUE SHIELD`   | Account holders name (business or individual)                      |
| account_number        | string    | `01234567890`   | Account number                                                     |
| account_type          | enum      | `savings`       | Description of account function: `savings`, `cheque`, `credit`     |
| account_status        | enum      | `open`          | Transactional status of the account: `open`, `closed`, `suspended` |
| account_creation_date | string    | `2019-11-25`    | Inception date of the account                                      |
| branch_code           | string    | `001234`        | (EFT) Branch code of the account                                   |

### Schema

```json
{
  "data": {
    "attr_names": [
      "bank_name",
      "bank_code",
      "account_holder_name",
      "account_number",
      "account_type",
      "account_status",
      "account_creation_date",
      "branch_code"
    ],
    "name": "bank_account.sbg.org.za",
    "version": "1.0.2"
  }
}
```
