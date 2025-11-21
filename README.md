# Terraform Noop Module

This is a minimal Terraform module that does absolutely nothing. It requires no providers and creates no resources.

## Usage

```hcl
module "noop" {
  source = "git::https://github.com/appvia/WFP-5864-more-use-of-native-graph-discovery.git//noop"
}
```

## Purpose

This module can be used for testing, placeholders, or situations where you need a valid Terraform module that performs no operations.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|----------|
| noop | A noop variable that does nothing | string | "noop" | no |

## Outputs

| Name | Description |
|------|-------------|
| noop | A noop output that does nothing |

