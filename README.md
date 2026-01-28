# This repository is for migrate and validate data in volume for kubernetes


```bash
ansible-playbook migrate_and_validate.yaml \
  --ask-vault-pass \
  -e namespace=<pvc_namespace> \
  -e source_pvc=<source_pvc_name> \
  -e destination_pvc=<destination_pvc_name>
```

## Reminder
Create your vault to protect your secrets.