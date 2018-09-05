The way to run playbook

# Dry Run on 1 Server
$> ansible-playbook playbooks/test-playbook.yml -i inventory/dev/master -l devserver01.* --diff -C

# Run For Real on 1 Server
$> ansible-playbook playbooks/test-playbook.yml -i inventory/dev/master -l devserver01.* --diff

# Run For Real on ALL Dev Server
$> ansible-playbook playbooks/test-playbook.yml -i inventory/dev/master --diff
