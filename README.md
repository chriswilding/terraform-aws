# Terraform AWS

## Prerequisites

1. [terragrunt](https://terragrunt.gruntwork.io/docs/getting-started/install/)

## Setup

```sh
$ git clone git@github.com:ChrisWilding/terraform-aws.git
$ git submodule update --init
```

## How To

### Manage Secrets

See [terraform-aws-secrets](https://github.com/ChrisWilding/terraform-aws-secrets)

### Apply

```sh
$ cd MODULE
$ terragrunt init
$ terragrunt apply
```
