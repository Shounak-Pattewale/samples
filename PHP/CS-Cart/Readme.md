CSCart Integration for Sage Line 50 - STANDARD
----------------------------------------------

This integration downloads standard Customer and Order Information into Sage Line 50 from CSCart.
The Orders can be downloaded as either Sales Orders or Invoices.

If you require any customisation to these scripts then please contact our Sales Team who will be able to provide you with a tailored quotation.

Customer Download:
==================
Automatically create an individual Sales Ledger record in Sage for customers should they have an order pending download.

Alternatively all orders can be downloaded to a single account reference.
Downloaded details can include Customers Name, Billing Address, Shipping Address and Contact Number.

Order Download:
===============
Choose to download the Order as either a Sales Order or Invoice to Sage Line 50.

Automatically create an individual Sales Order or Invoice within Sage Line 50 for your website orders.
Downloaded details can include Billing and Shipping details (name, address, telephone number);
Products purchased as item lines within Sage (with the net price, tax rate, quantity, unit discount, nominal code, item code, and product name)
Shipping method and cost as an order Carriage (with the net price, tax rate, nominal code)
Payment information can be downloaded optionally.

All orders will be downloaded as T1 should there be a tax rate present upon the order.


Installation - CSCart Scripts for Connect
-----------------------------------------

- Copy the 'sage' folder into the root of your website.
    It may appear as: http://www.your-website.com/sage

- Set the connection properties for your MySQL database in the config.php file.
    If there are any other settings within the 'Configure settings' section of the config file then please set those now.

- Run the setup file (index.php) location within '/sage/install/'
    This may be: http://www.your-website.com/sage/install
    The setup process will check your CSCart installation for compatibility.

- Install Connect and create a new profile choosing 'HTTP' as your connector.

- Within Connect point the Download URL to  the 'download.php' file.
    This may be: http://www.your-website.com/sage/download.php
- Within Connect point the Notify URL to the 'notify.php' file.
    This may be: http://www.your-website.com/sage/notify.php
