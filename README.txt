SMSsync
=======

A module to work with SMSsync android app.

This module enables the android app to post SMS messages into Drupal

Requirements
=======

This Drupal module works with Drupal 7 and PHP 5.4 or later


Installation and Usage
=======

* Install and enable the module.

* The installation will set up two new content types, 
  - "SMS message" which will hold the incoming messages, and 
  - "SMS message outbox" which will hold the messages to be sent


* The module will provide a link in the navigation menu. 
  This link will help in configuring the module to work with SMSSync app. 
  See 
      http://smssync.ushahidi.com/configure/ 
    for details on how to configure SMSSync android app.
