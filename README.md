# ansible 
# below links for ansible syntax's:
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/debug_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/include_role_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/replace_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/shell_module.html
# for template structure-:  https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html
#  https://docs.ansible.com/ansible/latest/collections/ansible/builtin/lineinfile_module.html
# for role dependencies :  https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html  
# Here how the use of role dependencies work - (Role dependencies let you automatically pull in other roles when using a role) in other words: when you call dependencies in code by using syntax it first executes the dependencies and then runs the code.
# for conditions : https://docs.ansible.com/ansible/2.9/user_guide/playbooks_conditionals.html  ( usage of conditions is done in user component)
# for grouping the modules -  https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_blocks.html
# for loops - https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_loops.html
# for installs of dnf  https://docs.ansible.com/ansible/latest/collections/ansible/builtin/dnf_module.html
#
# print Update Redis config
# sed -i -e '/^bind/ s/127.0.0.1/0.0.0.0/' -e '/protected-mode/ c protected-mode no' /etc/redis/redis.conf
# the above step does two functions
# first is updating 127.0.0.1 to 0.0.0.0 in the given configure file(/etc/redis/redis.conf)
# Second is updating protected-mode to protected-mode no in the given configure file (/etc/redis/redis.conf)

# to check and go through the main objectives of Retired - Red Hat Certified Specialist in Ansible Automation exam we need to refer to the link (https://www.redhat.com/en/services/training/ex407-retired-red-hat-certified-specialist-in-ansible-automation-exam?section=objectives)
# in the above link we see core components,
# Install and configure an Ansible control node,
# Configure Ansible managed nodes and many more.
