.PHONY: update install create display all

update: 
	ansible-playbook -i ../inventory.ini tags.yaml --tags "update"

install: 
	ansible-playbook -i ../inventory.ini tags.yaml --tags "install"

create:
	ansible-playbook -i ../inventory.ini tags.yaml --tags "create_users"

display:
	ansible-playbook -i ../inventory.ini tags.yaml --tags "display"

all: create display update install 