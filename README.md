# Ansible plugin to avoid skip tasks

Import the file in: 

Ansible callback plugin without skip tasks

/usr/lib/python2.7/site-packages/ansible/plugins/callback/noskip.py

Insert in your ansible.cfg the following line:

stdout_callback = noskip

And enjoy!
