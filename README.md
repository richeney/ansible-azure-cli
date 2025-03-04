# Install Azure CLI

Ansible role to install the Azure CLI for either Ubuntu 20.04 (focal), 22.04 (jammy), or 24.04 (noble).

Updated to handle ARM for the new Surface 7 Laptop.

## Installation

`ansible-galaxy install richeney.azure_cli`

## Example Playbook

```yaml
- hosts: all
  roles:
    - richeney.azure_cli
```

## Requirements

None.

## Dependencies

None.
