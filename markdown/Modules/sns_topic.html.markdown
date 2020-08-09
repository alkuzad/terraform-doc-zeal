
# Data Source: aws_sns_topic

Use this data source to get the ARN of a topic in AWS Simple Notification
Service (SNS). By using this data source, you can reference SNS topics
without having to hard code the ARNs as input.

## Example Usage

```hcl
data "aws_sns_topic" "example" {
  name = "an_example_topic"
}
```

## Argument Reference

* `name` - (Required) The friendly name of the topic to match.

## Attributes Reference

* `arn` - Set to the ARN of the found topic, suitable for referencing in other resources that support SNS topics.
