apptoolkit
===========

.. image:: https://img.shields.io/pypi/v/apptoolkit.svg
    :target: https://pypi.python.org/pypi/apptoolkit/
    :alt: Latest Version

.. image:: https://img.shields.io/pypi/wheel/apptoolkit.svg
    :target: https://pypi.python.org/pypi/apptoolkit/

.. image:: https://img.shields.io/pypi/pyversions/apptoolkit.svg
    :target: https://pypi.python.org/pypi/apptoolkit/

.. image:: https://img.shields.io/pypi/l/apptoolkit.svg
    :target: https://pypi.python.org/pypi/apptoolkit/
    
Introduction
-----------

This is a lightweight set of tools for obtaining information about Android devices in Python

Installing
----------

Install and update using `pip`_:

.. code-block:: text

    pip install -U apptoolkit

A Simple Example
----------------

.. code-block:: python

from apptoolkit import Device

android_devices = Device.get_android_devices()
    
Learn more
-----------

You can read this [blog][mafei-blog] to learn more about the `apptoolkit`.

[mafei-blog]: http://mafei.me/
