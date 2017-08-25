# Ansible callback plugin to avoid skip tasks on stdout

Import the file in:
/usr/lib/python2.7/site-packages/ansible/plugins/callback/noskip.py 

Insert in your ansible.cfg the following line:
stdout_callback = noskip

And enjoy!
