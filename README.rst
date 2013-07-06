===================
djadmin2-theme-1995
===================

A 1995-era admin theme for Django Admin2. 

Warning
========

This is silly. Don't use this or base your theme off this project.

Why? (silly)
============

Why not? No one represents old-skool web design anymoar!

Why? (Serious)
===============

I need to construct a sample theme for django-admin2 so I can see exactly what needs to be documented in order to create new themes. 

Installation
============

Getting the Code
-----------------

From PyPI::

    pip install djadmin2-theme-1995

From development

    git clone git@github.com:twoscoops/djadmin2-theme-1995.git
    cd djadmin2-theme-1995
    python setup.py develop

Configuration
--------------

In your settings.py::
    
    INSTALLED_APPS = (
        # ... snip the rest
        'djadmin2',
        'djadmin2_1995'
    )

    ########## ADMIN2 CONFIGURATION
    ADMIN2_THEME_DIRECTORY = "djadmin2_1995/"
    ########## END ADMIN2 CONFIGURATION
