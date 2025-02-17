##########
possibly.click-django CMS; a fork
##########
.. image:: https://travis-ci.org/django-cms/django-cms.svg?branch=develop
    :target: https://travis-ci.org/django-cms/django-cms
.. image:: https://img.shields.io/pypi/v/django-cms.svg
    :target: https://pypi.python.org/pypi/django-cms/
.. image:: https://img.shields.io/badge/wheel-yes-green.svg
    :target: https://pypi.python.org/pypi/django-cms/
.. image:: https://img.shields.io/pypi/l/django-cms.svg
    :target: https://pypi.python.org/pypi/django-cms/
.. image:: https://codeclimate.com/github/divio/django-cms/badges/gpa.svg
   :target: https://codeclimate.com/github/divio/django-cms
   :alt: Code Climate

Decription from Creators - "Open source enterprise content management system based on the Django framework and backed by the non-profit django CMS Association"

Description from me -

A fork to add details for absolute beginners (such as myself) to get up and running on a production server (VPS and or home server/rasberry pi).

I know there are tutorials of various methods for getting everything up and running but so far as of yet I have not been able to. I am going to attempt to cover everything in as consise a way as possible to help the average user.

I will add quotes "" for original text, extra info, links, comments, comic relief, remove un-nessasary info and attempt to understand what it is we are trying to do (namely build a good running universal base for future projects; portfolio, blog, art gallery, social api intergration, e-commerce integration, tryton integration etc.)" 


********
Features
********

* hierarchical pages
* extensive built-in support for multilingual websites
* multi-site support
* draft/publish workflows
* version control
* a sophisticated publishing architecture, that's also usable in your own applications
* frontend content editing
* a hierarchical content structure for nested plugins
* an extensible navigation system that your own applications can hook into
* SEO-friendly URLs
* designed to integrate thoroughly into other applications

Developing applications that integrate with and take advantage of django CMS features is easy and well-documented.

More information on `our website <https://www.django-cms.org>`_.

************
Requirements
************

"See the `Python/Django requirements for the current release version
<http://docs.django-cms.org/en/latest/#software-version-requirements-and-release-notes>`_ in our documentation."
This table is hella confusing but it looks like the latest django-cms 4.0 is compatible with the latest python 3.9.
the lastest




See the `installation how-to guide for an overview of some other requirements and dependencies of the current release
<http://docs.django-cms.org/en/latest/how_to/install.html>`_

*************
Documentation
*************

We maintain documentation for several versions of the project. Key versions are:

* `stable <http://docs.django-cms.org>`_ (default), for the **current release** version
* `latest <http://docs.django-cms.org/en/latest/>`_, representing the latest build of the **release-3.4.x branch**
* `develop <http://docs.django-cms.org/en/develop/>`_, representing the latest build of the **develop branch**

For more information about our branch policy, see `Branches
<http://docs.django-cms.org/en/latest/contributing/development-policies.html>`_.

Our documentation is hosted courtesy of `Read the Docs <https://readthedocs.org>`_.

The dependencies for the docs are compiled by `pip-tools <https://github.com/jazzband/pip-tools>`_.

************************
Developer Bounty Program
************************

Win rewards for creating Pull Requests. Take part in our `developer bounty program <https://www.django-cms.org/en/bounty-program/>`_

********
Tutorial
********

http://docs.django-cms.org/en/latest/introduction/index.html

***********
Quick Start
***********

You can use the `django CMS installer <https://djangocms-installer.readthedocs.io>`_::

    $ pip install --upgrade virtualenv
    $ virtualenv env
    $ source env/bin/activate
    (env) $ pip install djangocms-installer
    (env) $ mkdir myproject && cd myproject
    (env) $ djangocms -f -p . my_demo
    (env) $ python manage.py runserver

****
Demo
****

.. image:: https://raw.githubusercontent.com/django-cms/django-cms/develop/docs/images/try-with-divio.png
   :target: https://control.divio.com/demo/get-new/django-cms/
   :alt: Try demo with Divio Cloud

************
Getting Help
************

Please head over to our `Slack channel <https://www.django-cms.org/slack>`_ or our `discourse forum <https://discourse.django-cms.org/>`_ for support.

******************
Commercial support
******************

This project is backed by the `django CMS Association <https://www.django-cms.org/about-us>`_.
If you need help implementing or hosting django CMS, please contact us:
info@django-cms.org.

**********************
django CMS Association
**********************

The django CMS Association is a non-profit organization that was founded in 2020 with the goal to drive the success of django CMS, by increasing customer happiness, market share and open-source contributions. We provide infrastructure and guidance for the django CMS project.

The non-profit django CMS Association is dependent on donations to fulfill its purpose. The best way to donate is to become a member of the association and pay membership fees. The funding will be funneled back into core development and community projects.

`Join the django CMS Association <https://www.django-cms.org/en/contribute/>`_.


*******
Credits
*******

* Includes icons from `FamFamFam <http://www.famfamfam.com>`_.
* Python tree engine powered by
  `django-treebeard <https://tabo.pe/projects/django-treebeard/>`_.
* JavaScript tree in admin uses `jsTree <https://www.jstree.com>`_.
* Many thanks to
  `all the contributors <https://github.com/django-cms/django-cms/graphs/contributors>`_
  to django CMS!
