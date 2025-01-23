# role-gitlab
- Role contains tasks that enable interractions with gitlab

# Requirements
- Role reads and already created file containing the device configurations.

- Minimum ansible 2.11

# Design
- Role designed to be independent of inventory hosts and runs on localhost.

- Role will read *.ucs, *.txt or *.cfg files and add to the cloned git repo and git push.

- If file_upload == false, then there will be no uploading of files.

# Role Variables
- Variables are fed into the role during the play.

- Varibles are set in group_vars/all.yml file

- See example below

# How to use
- See example below

# Example vars file
example-vars.yml

## example playbook file
example-playbook.yml

# License
BSD
