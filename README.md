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

    npm install git+https://github.com/PabloCastellano/ep_maadix_pads.git

    git clone https://github.com/PabloCastellano/ep_maadix_pads
    mysql -u USER -p < sql_listing.sql
    cp ep_maadix/email.json.template ep_maadix/email.json
    cd etherpad-lite
    npm install ../ep_maadix/ep_maadix

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


