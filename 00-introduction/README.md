
---
# 00 – Introduction to Terraform

Terraform is an open-source infrastructure as code (IaC) tool by HashiCorp that allows you to define, provision, and manage infrastructure across cloud and on-premises environments.

## 💡 Why Use Terraform?

- Platform agnostic: AWS, GCP, Azure, VMware, Docker, and more
- Declarative: Focus on *what* you want, not *how* to do it
- Version-controlled: Store infrastructure changes in Git
- Reusable: Modular architecture encourages code reuse

## 🧱 Core Concepts

| Term | Description |
|------|-------------|
| Provider | Cloud/on-prem API Terraform communicates with |
| Resource | The infrastructure object being created (e.g. instance, network) |
| Module | Reusable block of configuration |
| State | Tracks the real-world infrastructure |
| Plan | Shows changes Terraform *will* make |
| Apply | Executes changes to reach the desired state |

---

Next → [Terraform Basics](../01-terraform-basics)

