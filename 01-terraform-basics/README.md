# 01 – Terraform Basics

In this chapter, you'll:

- Install Terraform CLI
- Write your first `.tf` file
- Initialize Terraform
- Create a local file resource

---

## 📦 Example: Create a File Using Local Provider

We’ll use the `local` provider to write a simple file to your disk – no cloud setup needed.

### 📄 `main.tf`
```hcl
terraform {
  required_providers {
    local = {
      source = "hashicorp/local"
      version = "~> 2.0"
    }
  }
}

provider "local" {}

resource "local_file" "example" {
  content  = "Hello, Terraform!"
  filename = "${path.module}/hello.txt"
}
```
