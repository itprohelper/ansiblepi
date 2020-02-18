# ansiblepi
Playbook for deploying configurations on remote Raspberries.

You need to change the hosts file and *config.cfg* to meet your requirements.

Run the playbook:
	`ansible-playbook playbook.yml -v -K`

*-v lets you see verbose output about what going on*

*-K lets you enter the 'become user' password or *sudo* password*
