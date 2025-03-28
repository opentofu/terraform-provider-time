---

<!-- Please do not edit this file, it is generated. -->
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "unix_timestamp_parse function - terraform-provider-time"
subcategory: ""
description: |-
  Parse a unix timestamp integer into an object
---

# function: unix_timestamp_parse

Given a unix timestamp integer, will parse and return an object representation of that date and time. A unix timestamp is the number of seconds elapsed since January 1, 1970 UTC.

## Example Usage

```terraform
output "test" {
  value = provider::time::unix_timestamp_parse(1606105443)
}
```

## Signature

<!-- signature generated by tfplugindocs -->
```text
unix_timestamp_parse(unix_timestamp number) object
```

## Arguments

<!-- arguments generated by tfplugindocs -->
1. `unix_timestamp` (Number) Unix Timestamp integer to parse


<!-- cache-key: cdktf-0.20.8 input-94172a433fe5902925761b59a8c29ab4e179ff06a5e62c02d01a3bc0f06a3204 -->