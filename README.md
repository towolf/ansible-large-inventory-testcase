This repo contains an anonymized version of an actual inventory. The JSON
contains about 8500 groups and 3500 hosts. Reading the JSON is not instructive,
but the original membership structure including hostvars in `_meta` is preserved.

Test with 

   time ansible-playbook -i inventory.sh playbook.yml
