Overview
========

Django-Crudbuilder allows you to generate class based views for CRUD (Create, Read, Update and Delete) for specific model

Features
--------
- Generates class based views for CRUD
- Uses **django-tables2** to display objects in ListView
- Allows custom forms/tables as additional arguments
- Context provides additional template variables **APP_LABEL** and **MODEL** for all CRUD templates
- Enable/disable login required option for CRUD views
- Enable/disable permission required option for CRUD views
- All the generated views/tables/forms/url are extendable.


Requirements and Compatibility
------------------------------

The 0.0.x series currently supports Django >= 1.8.x and corresponding versions of Python also supported by Django (including Python 3).  Development of django-crudbuilder follows Django's Supported Version Policy and testing for older versions of Django/Python will be removed as time marches on.