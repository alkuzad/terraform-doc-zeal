
# Data Source: aws_efs_access_points

Provides information about multiple Elastic File System (EFS) Access Points.

## Example Usage

```hcl
data "aws_efs_access_points" "test" {
  file_system_id = "fs-12345678"
}
```

## Argument Reference

The following arguments are supported:

* `file_system_id` - (Required) EFS File System identifier.

## Attributes Reference

In addition to all arguments above, the following attributes are exported:

* `arns` - Set of Amazon Resource Names (ARNs).
* `id` - RFC3339 timestamp when the data source was invoked.
* `ids` - Set of identifiers.
