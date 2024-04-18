# Runner-Box
Utilze Github's hosted Runners as a debuggable SSH instance!

# How to use:

1. Fork this repo.

2. Generate an SSH key and assign it a password.
   `ssh-keygen -t rsa`

3. Copy the contents of id_rsa.pub to your Github's accounts SSH keys.

4. Actions -> All Workflows -> Runner Box -> Run Workflow.

5. Head over to your newly executed workflow & under the Setup/Start SSH session you will see the command to run from your terminal.

