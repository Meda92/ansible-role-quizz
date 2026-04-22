# Tester le rôle

## Créer un playbook nommé `ansible-role-quiz.yaml` :

```yaml
- name: Déploiement quiz-ansible via role
  hosts: rocky
  become: yes
  roles:
    - ansible-role-quiz
```

Ensuite le tester avec :

```bash
ansible-playbook projet/playbooks/ansible-role-quiz.yaml
```
