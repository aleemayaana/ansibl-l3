# 17 Kubernetes Cluster

## Usage
```bash
ansible-playbook project.yml -i inventory/hosts.yml
```

## Roles
| Role | Purpose |
|------|---------|
| 01precheck | Validate prerequisites |
| 02implementation | Main deployment tasks |
| 03postcheck | Verify implementation |
