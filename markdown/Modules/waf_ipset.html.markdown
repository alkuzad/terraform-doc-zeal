
# Data Source: aws_waf_ipset

`aws_waf_ipset` Retrieves a WAF IP Set Resource Id.

## Example Usage

```hcl
data "aws_waf_ipset" "example" {
  name = "tfWAFIPSet"
}
```

## Argument Reference

The following arguments are supported:

* `name` - (Required) The name of the WAF IP set.

## Attributes Reference
In addition to all arguments above, the following attributes are exported:

* `id` - The ID of the WAF IP set.
