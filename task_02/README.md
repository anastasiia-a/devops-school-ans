## Task 2

Write a playbook to create the users: Alice, Bob, Carol.<br>
Each user should be given a name, an email in comment, a home directory, an encrypted password<br>
(an  encrypted variable or a separate encrypted file). Nothing should be encrypted, except the password.<br>
The password shouldn't be changed for existing users.


#### The playbook runs with the following command: 
```
ansible-playbook playbook.yml --ans-vault-pass
```
Vault password = pass