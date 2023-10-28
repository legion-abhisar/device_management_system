# Device Management System
This is an application that is based on Django REST Framework to showcase the IoT device management system locally. 

## Requirements
* User login using the Django authentication.
* Private user device profile:
    * username
    * device uuid
    * device name
    * location

* Admin dashboard
    * User status
    * User management

## Schema
* User
    * user_id
    * email
    * password
    * groups: admin or user (can only belong to one)
* Device profile
    * device uuid
    * device name
    * device status
    * device parameters
    * timezone
    * location