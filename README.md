# ansible

# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/debug_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/include_role_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/replace_module.html
# https://docs.ansible.com/ansible/latest/collections/ansible/builtin/shell_module.html
# for template structure-:  https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html
#  https://docs.ansible.com/ansible/latest/collections/ansible/builtin/lineinfile_module.html
#
# 
#
#
#
#
# print Update Redis config
# sed -i -e '/^bind/ s/127.0.0.1/0.0.0.0/' -e '/protected-mode/ c protected-mode no' /etc/redis/redis.conf
# the above step does two functions
# first is updating 127.0.0.1 to 0.0.0.0 in the given configure file(/etc/redis/redis.conf)
# Second is updating protected-mode to protected-mode no in the given configure file (/etc/redis/redis.conf)


