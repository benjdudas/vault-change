# vault-change
Renaming the vault credentials in tower

To Use:
1) Map the current vault name to the new vault name in a variable dictionary in group_vars/all
   - see example `creds` in group_vars/all

2) Run `ansible-playbook change_vault.yml`
