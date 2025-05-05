# ansible-scaffold

Create ansible scaffold with vars, inventories, roles and playbook for a project

# Usage

```bash
# Instal ansible-create script
curl -sSL https://raw.githubusercontent.com/srijanss/ansible-scaffold/refs/heads/main/ansible-create -o /usr/local/bin/ansible-create && chmod +x /usr/local/bin/ansible-create

# Create ansible scaffold
ansible-create --project-dir <project_name> --app-name <app_name> --create-helm-charts
options:
  -h, --help                      show this help message and exit
  -p, --project-dir PROJECT_DIR   Project directory name (default: ansible-scaffold)
  -a, --app-name APP_NAME         Application name (default: my-app)
  -c, --create-helm-charts        Create helm charts for the project (default: False)
```
