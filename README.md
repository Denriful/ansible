# ansible
for testing purposes

commands reminder:

ansible-playbook -i ./inventory/inventory.static.yml reddit_app.yml --private-key /home/sulgin/.ssh/appuser -u appuser --limit db --tag db-tag

ansible-playbook -i ./inventory/inventory.static.yml reddit_app.yml --private-key /home/sulgin/.ssh/appuser -u appuser --limit app --tag app-tag

ssh -i /home/sulgin/.ssh/appuser appuser@35.223.146.100