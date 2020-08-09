
# Data Source: aws_wafregional_rate_based_rule

`aws_wafregional_rate_based_rule` Retrieves a WAF Regional Rate Based Rule Resource Id.

## Example Usage

```hcl
data "aws_wafregional_rate_based_rule" "example" {
  name = "tfWAFRegionalRateBasedRule"
}
```

## Argument Reference

The following arguments are supported:

* `name` - (Required) The name of the WAF Regional rate based rule.

## Attributes Reference
In addition to all arguments above, the following attributes are exported:

* `id` - The ID of the WAF Regional rate based rule.
