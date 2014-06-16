Ntxuva Open311 SMS (beta)
============

Introduction
-----

This Drupal module enables users to submit Ntxuva reports through SMS.

Ntxuva-Open311-SMS handles requests from Telerivet Webhook API, evaluates the data and generates reports if everything is ok.

Requirements
-----
* A content to work as translator: from Location codes to one of lat & long or address_string or address_id (Georeport v2)
* A content to work as translator: from Problem Code to service_code (Georeport v2)
* An Open311 Georeport v2 endpoint
* Telerivet account (ours is working with an Android to provide a local number for users in Maputo to send us SMS)

Features
----
As it is implemented, Ntxuva Open311 SMS will:
* Report new issues through SMS using the Open311 API
* Check status of report by service_request_id

Getting Started
----
1. Still working on it

How it works
----
1. Still working on it

To-Do
---
1. Work on a more context-independent implementation
2. Possibly, integrate with VoIP Drupal simply acting as a script
3. Create required contents on installation
