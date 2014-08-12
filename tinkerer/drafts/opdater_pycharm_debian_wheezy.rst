Opdater PyCharm (Debian Wheezy)
===============================

.. code-block:: console
   
   # tar -C /opt/ -xf /path/to/pycharm-community-3.X.Y.tar.gz
   # ln -s /opt/pycharm-community-3.4.1 /opt/pycharm-latest
   # vim /usr/local/bin/charm

Er et python script

.. code-block:: python

   RUN_PATH = '/opt/pycharn-community-edition-3.1.1/bin/pycharm.sh'

Ændres til:

.. code-block:: python

   RUN_PATH = '/opt/pycharn-latest/bin/pycharm.sh'

Og det samme har jeg gjort i KDE system menuen   

.. author:: default
.. categories:: quicktips
.. tags:: pycharm, debian
.. comments::
