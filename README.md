# Ansible Runbook: updateos

[![Build](https://github.com/dcjulian29/ansible-runbook-updateos/actions/workflows/ci.yml/badge.svg)](https://github.com/dcjulian29/ansible-runbook-updateos/actions/workflows/build.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-runbook-updateos.svg)](https://github.com/dcjulian29/ansible-runbook-updateos/issues)

This an Ansible runbook that will update the operating system and reboot if needed.

## Requirements

- Internet Connection

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
collections:
- name: dcjulian29.updateos
  src: https://github.com/dcjulian29/ansible-runbook-updateos.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy collection install -r requirements.yml
```
