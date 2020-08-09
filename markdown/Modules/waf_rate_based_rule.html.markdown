
# Data Source: aws_waf_rate_based_rule

`aws_waf_rate_based_rule` Retrieves a WAF Rate Based Rule Resource Id.

## Example Usage

```hcl
data "aws_waf_rate_based_rule" "example" {
  name = "tfWAFRateBasedRule"
}

```

## Argument Reference

The following arguments are supported:

* `name` - (Required) The name of the WAF rate based rule.

## Attributes Reference
In addition to all arguments above, the following attributes are exported:

* `id` - The ID of the WAF rate based rule.
