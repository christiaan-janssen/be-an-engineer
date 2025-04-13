---
title: Infrastructure as Code
type: docs
prev: docs/basics
next: docs/02-infra-as-code/01-terraform
sidebar:
  open: true
---

A very important part of the work you do as a Devops engineer is developing and maintaining the infrastructure. In the past you would log into a (web)interface and make changes to the infrastructure. While this did work, it had some problems. If you ask ChatGPT about the downsides of not using infrastructure as code, it comes up with some compelling points:

### **Inconsistency and Drift**

- **Manual changes** often lead to environments that don’t match (e.g., dev ≠ prod).
- Over time, configs can drift from intended states, making troubleshooting harder.

### **Error-Prone Manual Processes**

- Manual provisioning or updates increase the risk of human error (wrong config, missed step, etc.).
- These errors are often hard to track and reproduce.

### **Lack of Documentation**

- Without IaC, the only “documentation” might be tribal knowledge or random notes.
- IaC *is* documentation — it describes what infrastructure exists and how it’s configured.

### **Poor Scalability**

- Scaling infra manually is slow and doesn't scale with team or service growth.
- Reproducing environments (e.g., for testing, staging) becomes time-consuming.

### **Harder Auditing and Compliance**

- No change history or version control without IaC.
- Auditing infra changes becomes a manual, error-prone task.

### **No Version Control**

- With IaC, you get git history, reviews, rollbacks, and collaboration.
- Without it, reverting a bad change might mean manually “guessing” the previous state.

### **Slow Onboarding**

- New team members need to be walked through the infrastructure instead of reading code.
- It’s harder to create consistent dev environments without a standard template.

### **No Automation or CI/CD Integration**

- IaC enables automating deploys, tests, and updates through pipelines.
- Without it, you're stuck doing repetitive work manually or building complex scripts from scratch.

## IaC Tools

### Terraform

### Cloudformation

### Ansible

### Biceps
