# ObligatorioTaller2025.

Aqui encontraremos el inventario, playbooks, results y respuesta a preguntas de obligatorio.

Para ejecutar los playbooks :

sudo ansible-playbook -i /home/ansible/ObligatorioTaller2025/Inventory/Inventory.ini Hardening.yml 

sudo ansible-playbook -i /home/ansible/ObligatorioTaller2025/Inventory/Inventory.ini web_setup.yml --limit ubuntu
