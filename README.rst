#The README.rst file can contain detailed information for users about your package, installation steps, basic usage instructions, and links to other resources such as documentation.
#It is written using Markdown syntax.

==============
City Locations
==============

City Locations is a Django app that can be installed in an existing Django project
Documentation: https://toddpy-django-cityloc-pkg.readthedocs.io/en/latest/

Installation
------------

1. Add "citylocations" to your INSTALLED_APPS setting in settings.py:
    INSTALLED_APPS = [
        ...
        
        'citylocations',

    ]

2. Include the citylocations URLconf in your project urls.py like this::
    path('', include('citylocations.urls')),

3. Start the development server and visit http://127.0.0.1:8000/