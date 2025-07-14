# ansible-lab

A collection of Ansible playbooks, roles, and examples for learning, testing, and automating IT infrastructure.

## Features

- Custom Ansible roles

## Getting Started

### Prerequisites

- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) installed (version 2.18 recommended)
- Access to target hosts (via SSH)

### Clone the Repository

```bash
git clone https://github.com/enigma972/ansible-lab.git
cd ansible-lab
```

### Directory Structure

```text
ansible-lab/
├── roles/
├── .gitignore
├── inventory.ini
└── README.md

```

## Usage

Run a sample playbook:

```bash
ansible-playbook -i inventory/hosts playbooks/sample.yml
```

## Contributing

Contributions are welcome! Please open issues or pull requests for improvements.

## License

This project is licensed under the MIT License.
