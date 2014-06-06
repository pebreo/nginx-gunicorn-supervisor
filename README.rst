  

Quickstart
---------

.. code::  bash
$ gunicorn myproj.myproj.wsgi 

.. code:: bash

  Nginx
  Create link
  $ CURRENT_DIR=`pwd -P` # raw path, no symbolic links
  $ sudo ln -s ${CURRENT_DIR}/nginx.conf /etc/nginx/sites-enabled/mysite
  $ sudo service nginx reload

  location: /etc/supervisor/conf.d/myprog
  $ sudo apt-get update
  $ sudo apt-get install supervisor
  $ sudo service supervisor restart
  $ sudo supervisorctl
  > reread myprog 
  > update 
  > restart myprog
  > quit
  
  Node commands
  $ node start
  $ node app.js
  $ node scripts/web-server.js
