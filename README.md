ansible-role-facts
=========

Create custom facts

Role Variables
--------------
```
custom_facts:
  - section: metadata
    settings:
      - key: environment
        value: production
      - key: owner
        value: rudi.broekhuizen@naturalis.nl
```

Access facts

{{ ansible_local.custom_facts }} 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
