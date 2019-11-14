# terraform-aws-multifolder

### How to call multi-folder repo in private mudule in Terraform Cloud 

```

module "multifolder1" {
  source  = "app.terraform.io/tforg123/multifolder/aws//module1"
  version = "0.0.1"
}

module "multifolder2" {
  source  = "app.terraform.io/tforg123/multifolder/aws//module2"
  version = "0.0.1"
}

```

