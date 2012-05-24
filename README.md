textile-test
============
```yml
virtual_folder: [path to startsiden-frontpage-layout root]/templates/virtual_example/frontdesk/

static:
    include_path:
        - __path_to(root)__
        - [path to startsiden-frontpage-layout root]
    ignore_extensions:
        - tmpl
        - tt
        - tt2 

View::TT:
    INCLUDE_PATH:
        - __path_to(root)__
        - [path to startsiden-frontpage-layout root]
        - [path to startsiden-frontpage-layout root]/templates/virtual_example
```
