# EzAce
Source Code for Casino Table Project.  Combined odoo backend with custom floor layout module and django integration with odoo API using the package djangodoo to simplify the API calls.  You can also do these calls directly following the odoo developer documentation.

* As an important note, right now the pos_resturant file overwrites the pos_resturant in the namespace of odoo.  We need to change that but I need to do some renaming of the lower level modules so they load correctly.  its a start though

### When initializing the odoo data base for the first time, this must match up for the Django Odoo Integration
ODOO_HOST = {
    'USER': 'EzAce@gmail.com',
    'PASSWORD': 'EzAce',
    'HOST': 'http://172.20.0.1',
    'PORT': 8069,
    'DB': 'EzAce'
}