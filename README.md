Cteam-lab.com website
========================

This is the actual code that is running on our servers.

Platform:

   * Linux
   * HHVM 5.6
   * Symfony2
   * Mysql
   * Grunt
   * Bower

Install NodeJS and then run:

    npm update -g npm
    npm install -g grunt-cli
    npm install -g bower
    
If using Ubuntu (14.04) and installing HHVM 3.6.0 version, add the following line both to HHVM php.ini and server.ini:

  | hhvm.libxml.ext_entity_whitelist = file,http

