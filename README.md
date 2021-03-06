ep_maadix
=========

This plugin adds the following features to etherpad-lite:

- User-Management System
- Group-Management System
- Optionally allow register of new users
- Optionally allow public pads
- Administration interface

Installation
------------

In order to use this plugin you have to [configure Etherpad Lite to use MySQL as backend database](https://github.com/ether/etherpad-lite/wiki/How-to-use-Etherpad-Lite-with-MySQL).

At the moment you still cannot install the plugin from the administrator interface so you have to clone it:

    git clone https://github.com/PabloCastellano/ep_maadix
    cp ep_maadix/ep_maadix/email.json.template ep_maadix/ep_maadix/email.json
    cd etherpad-lite
    npm install ../ep_maadix/ep_maadix

In the near future this command should replace the previous ones:

    npm install git+https://github.com/PabloCastellano/ep_maadix.git

Then use the provided [SQL script](/sql_listing.sql) to create the schema:

    mysql -u USER -p < sql_listing.sql

Screenshots
-----------

TODO


Credits
-------

It is based in these other plugins that were unmaintained at the time of the development:

- https://github.com/aoberegg/ep_user_pad/
- https://github.com/aoberegg/ep_user_pad_frontend/

Known alternatives to this plugin
---------------------------------

- https://github.com/framasoft/ep_mypads
- https://github.com/vltugraz/ep_user_pads
- https://github.com/reality/ep_frontend_community


