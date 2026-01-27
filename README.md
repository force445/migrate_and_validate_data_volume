# This repository is for migrate and validate data in volume for kubernetes


```bash
ansible-playbook migrate_pvc.yaml \
  --ask-vault-pass \
  -e namespace=jupyterhub \
  -e source_pvc=jupyterhub-claim-user1 \
  -e destination_pvc=jupyterhub-claim-user1-temp
```
