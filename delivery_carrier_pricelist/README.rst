=========================
Shipping Method Pricelist
=========================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:76b8c6119a643bb4bf503c0bd0fbdbe3dd84d775762f341fd3b259e4e1dc42a0
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fdelivery--carrier-lightgray.png?logo=github
    :target: https://github.com/OCA/delivery-carrier/tree/13.0/delivery_carrier_pricelist
    :alt: OCA/delivery-carrier
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/delivery-carrier-13-0/delivery-carrier-13-0-delivery_carrier_pricelist
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/delivery-carrier&target_branch=13.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

Compute shipping methods fees based on Product Pricelists.

It allows to have different pricing per customer, prices depending on dates, ...
The pricelist based cost is computed from the shipping method's product and the
sales order's pricelist.

It supports the following use cases:

* When no "external" provider (e.g. DHL, UPS, ...) is used, a new provider
  "Based on Product Pricelist" is available.
* When an external provider is used, a new option in the "Invoice Policy"
  selection, named "Pricelist Cost", overrides the provider's cost by the
  pricelist based cost.

**Table of contents**

.. contents::
   :local:

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/delivery-carrier/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/delivery-carrier/issues/new?body=module:%20delivery_carrier_pricelist%0Aversion:%2013.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Camptocamp

Contributors
~~~~~~~~~~~~

* Guewen Baconnier <guewen.baconnier@camptocamp.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/delivery-carrier <https://github.com/OCA/delivery-carrier/tree/13.0/delivery_carrier_pricelist>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
