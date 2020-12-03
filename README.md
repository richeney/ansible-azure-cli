# Install Azure CLI

Ansible role to install the Azure CLI for either Ubuntu 16.04 (xenial), 18.04 (bionic) or 20.04 (focal).

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
