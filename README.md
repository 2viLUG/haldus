Haldus - Free Management Web Application
=================================

Haldus is a free management software developed by 2viLUG - Dueville Linux User Group.

Requirements
============

Haldus requires Python 2.7.4 and Django 1.5.1.
It requires a database too: we use MySQL. Just setup a database and import mysql.sql file that you find in this repository.
You than have a Super User already. You can login with these credentials:
Username: admin
Password: admin

Last edit file haldus/settings.py and edit DATABASES dictionary with your database details.
You might want to edit also TIME_ZONE and LANGUAGE_CODE

Changelog
=========

v0.1
- Added Django framework
