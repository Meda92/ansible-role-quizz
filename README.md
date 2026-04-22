# Tester le rôle

## Créer un playbooks qu'on nomme ansible-role-quiz.yaml:

- name: Déploiement quiz-ansible via role
  hosts: all
  become: yes
  roles:
  - ansible-role-quiz

Ensuite le tester
