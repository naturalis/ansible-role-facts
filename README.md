Role Name
=========

Create custom facts

Role Variables
--------------
```
facts_name: custom 
facts_sub_name: subname
facts_dict:
  fact1: 1
  fact2: 2
```

Access facts

{{ ansible_local.custom.subname.fact1 }} 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
