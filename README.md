Ntxuva Open311 SMS (beta)
=======


Introduction
-----

This Drupal module enables users to submit Ntxuva reports through SMS.

Ntxuva-Open311-SMS handles requests from Telerivet Webhook API, evaluates the data and generates reports if everything is ok.

Requirements
-----
* A content to work as translator: from Location codes to one of lat & long or address_string or address_id (Georeport v2)
* An Open311 Georeport v2 endpoint
* Telerivet account (ours is working with an Android to provide a local number for users in Maputo to send us SMS)

Features
----
As it is implemented, Ntxuva Open311 SMS will:
* Report new issues through SMS using the Open311 API
* Check status of report by service_request_id

Users are able to report new issues by inserting a location code and a comment. (SMS would be something like: 01001 There is waste here.)
* 010 is the code of the location
* 01 is the service_code of the request

How to set up
----
1. Install the Module
2. Insert a set of location codes and coordinates (translator)
3. Configure Open311 GeoReport v2 API endpoint in the module configuration
4. Test if everything works with a REST client
5. Configure webhook URL in your telerivet account
6. Install Telerivet App on an Android and connect to the service
7. Test using the Telerivet test console
4. Inform citizens of the location codes and service codes to get on going!

How it works
----
![NtxuvaOpen311 SMS](http://www.ntxuva.org/wp-content/uploads/2014/09/Ntxuva_SMS.png)

To-Do
---
~~1. Explain how it works and getting started~~
~~3. Enhance SMS workflow~~
2. Work on the semantic analysis of SMS
4. Include validations of settings
5. Clean messy code
6. Include debug flag
7. Save incoming SMS as content
8. Provide more options for module config

Requirements
-----
* A content to work as translator: from Location codes to one of lat & long or address_string or address_id (Georeport v2)
* An Open311 Georeport v2 endpoint
* Telerivet account (ours is working with an Android to provide a local number for users in Maputo to send us SMS)

Features
----
As it is implemented, Ntxuva Open311 SMS will:
* Report new issues through SMS using the Open311 API
* Check status of report by service_request_id
