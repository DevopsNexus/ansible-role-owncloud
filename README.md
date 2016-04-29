Role Name
=========

OwnCloud is tool to share and synchronize your files across different devices. The roles installs owncloud

Requirements
------------

The module assumes that if you are going to use MySQL then you already have set it up separately. If there is no MySQL then it will fall back to SQLite.

Role Variables
--------------
Following are the three variables used in the role:
* owncloud_version: "9.0.1"
* setup_php: true
* owncloud_destination: "/var/www/html"

License
-------
GPLv3

Author Information
------------------
Aditya Patawari is founder of [Devops Nexus](http://devopsnexus.com), a consulting and training company. All the training materials are released under Creative Commons license on [TrainingDevops.com](http://trainingdevops.com). For any consulting and training assignments, drop an email to contact@devopsnexus.com.
