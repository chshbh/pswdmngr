# pswdmngr [![Build Status](https://travis-ci.org/chshbh/pswdmngr.svg?branch=master)](https://travis-ci.org/chshbh/pswdmngr)
[peewee](https://github.com/coleifer/peewee) based cli password manager/generator

-  Check .travis.yaml file for easy build.

-  ~~No plans to export on Python3.~~
## Description
- SqlCipher Database is used to encrypt the database file with AES. 
- peewee ORM is used to map and interact with the database. 
- Create, store, edit and generate password, that allows user to use a single "master" password to generate unique password for all the sites and services.
