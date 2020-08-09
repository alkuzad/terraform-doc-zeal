
# Data Source: aws_qldb_ledger

Use this data source to fetch information about a Quantum Ledger Database.

## Example Usage

```hcl
data "aws_qldb_ledger" "example" {
  name = "an_example_ledger"
}
```

## Argument Reference

* `name` - (Required) The friendly name of the ledger to match.

## Attributes Reference

* `arn` - Amazon Resource Name (ARN) of the ledger.
* `deletion_protection` - Deletion protection on the QLDB Ledger instance. Set to `true` by default. 
