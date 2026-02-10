# Ansible Roles and Playbooks

This repo contains a small set of Ansible roles and playbooks I use for repeatable system configuration and automation.

These are practical roles built to standardize setups, reduce manual configuration, and make environments easier to rebuild and maintain.

---

## Structure

- `roles/`  
  Contains reusable Ansible roles for configuring services and systems.

- `playbooks/`  
  Contains playbooks that apply one or more roles to target hosts.

---

## Roles

This repo currently includes a handful of roles focused on common setup and automation tasks. Roles are intentionally kept simple and easy to extend.

Examples of what roles here handle:
- Service installation and configuration
- System setup and baseline configuration
- Reusable automation for common tasks

---

## Playbooks

Playbooks in this repo are used to:
- Apply roles to hosts or groups
- Orchestrate multi-step setups
- Serve as entry points for repeatable builds

---

## Usage

Typical usage looks like:

