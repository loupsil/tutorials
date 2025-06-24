# Odoo tutorials

This repository hosts the code for the bases of the modules used in the
[official Odoo tutorials](https://www.odoo.com/documentation/latest/developer/tutorials.html).

It has 3 branches for each Odoo version: one for the bases, one for the
[Discover the JS framework](https://www.odoo.com/documentation/latest/developer/tutorials/discover_js_framework.html)
tutorial's solutions, and one for the
[Master the Odoo web framework](https://www.odoo.com/documentation/latest/developer/tutorials/master_odoo_web_framework.html)
tutorial's solutions. For example, `17.0`, `17.0-discover-js-framework-solutions` and
`17.0-master-odoo-web-framework-solutions`.

----------

To run the server: 

python odoo-bin --addons-path="addons,../enterprise,../tutorials" -d odoo_tutorial --db_user=odoo --db_password=odoo --dev=all

----------

To activate the venv (inside Odoo/odoo):

. venv/Scripts/activate


------------

To start querying in PostgreSQL 

& "C:\Program Files\PostgreSQL\15\bin\psql.exe" -U odoo -d rd-demo