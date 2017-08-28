Maintenance Mode Exclude Urls
======================

Maintenance Mode Exclude Urls is a very simple and light weight
module. It allows certain pages to be shown 
even when the site is offline.

There are certain cases when you will put your site in maintenance mode
but still want to show some pages (generally READONLY pages) to the
end user. You can use this module in those cases.

Another use case involves incoming webhooks, e.g. those used by the twilio module to
allow the site to respond to incoming sms or voice calls.  This module allows the webhooks 
to be received and processed correctly while the site is in maintenance mode.


Installation 
------------

Install this module using the official Backdrop CMS instructions at 
https://backdropcms.org/guide/modules

## Configuration
Goto Administration > Configuration > Development > Maintenance Mode

Enter one page per line in Exclude Urls text area. Hit Save Configuration.
When you take your site offline all the pages entered will now be shown to the
end users.


Documentation 
-------------

Additional documentation is located in the Wiki: https://github.com/backdrop-
contrib/mmeu/wiki/Documentation

Issues 
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/mmeu/issues

Current Maintainers 
-------------------

- Marc Linn (https://github.com/mclinn)

Credits 
-------

- Ported to Backdrop CMS by Marc Linn (https://github.com/mclinn). 
- Originally written for Drupal by Sonu Raj Chauhan (https://www.drupal.org/u/sonurajchauhan)

License 
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
