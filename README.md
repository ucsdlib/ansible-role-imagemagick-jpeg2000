ImageMagick-JPEG2000
====================

Installs ImageMagick with JPEG 2000 support

Provided as a separate role in the chance that vendor provided ImageMagick packages lack JPEG 2000 support, so this role would need to download and compile locally.

Requirements
------------

No external requirements.

Role Variables
--------------

No role variables.

Dependencies
------------

No external dependencies.

Example Playbook
----------------



    - hosts: servers
      roles:
         - ucsdlib.imagemagick-JPEG2000

License
-------

BSD 2 Clause

Author Information
------------------

John H. Robinson, IV  
The Library  
UC San Diego  
