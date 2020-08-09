
# Data Source: aws_outposts_outpost

Provides details about an Outposts Outpost.

## Example Usage

```hcl
data "aws_outposts_outpost" "example" {
  name = "example"
}
```

## Argument Reference

The following arguments are supported:

* `id` - (Optional) Identifier of the Outpost.
* `name` - (Optional) Name of the Outpost.

## Attribute Reference

In addition to all arguments above, the following attributes are exported:

* `arn` - Amazon Resource Name (ARN).
* `availability_zone` - Availability Zone name.
* `availability_zone_id` - Availability Zone identifier.
* `description` - Description.
* `owner_id` - AWS Account identifier of the Outpost owner.
* `site_id` - Site identifier.
