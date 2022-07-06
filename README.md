## THIS CODE IS FOR EDUCATIONAL PURPOSES ONLY

Adinusa Ansible Quiz 2 - Create random user accounts with ansible-playbook and ansible-vault

## Running Tests

To run tests, run the following command

```bash
ansible-vault encrypt secret.yml
  ```
```bash
echo 'belajaransible' > vault-pass  
```
  ```bash
chmod 600 vault-pass
  ```
  ```bash
ansible-playbook --vault-password-file=vault-pass quiz2-tasks.yml
  ```
