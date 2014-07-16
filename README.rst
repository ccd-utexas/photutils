photutils
=========

This package provides an `AstroPy`_ affiliated package for image
photometry tools.

.. image:: https://travis-ci.org/astropy/photutils.png?branch=master
  :target: https://travis-ci.org/astropy/photutils

.. image:: https://coveralls.io/repos/astropy/photutils/badge.png
  :target: https://coveralls.io/r/astropy/photutils

.. _AstroPy: http://www.astropy.org/

Note for ccd-utexas:
=========

Purpose: This fork is used to control the photutils version in use for tsphot. When photutils is integrated with astropy, delete this repository and use astropy.photometry through the Anaconda Python distribution.

To install photutils to work with tsphot, first install and update anaconda.
Then clone this repository ; cd /path/to/photutils ; python setup.py install

Code in this repository is subject to being overwritten by subsequent releases of photutils.

To update ccd-utexas/photutils from astropy/photutils:
- Navigate to https://github.com/ccd-utexas/photutils

- click "Compare"

- click "Edit"

- Set:

  - base fork: ccd-utexas/photutils  base: master

  - head fork: astropy/photutils  compare: master

- This will merge astropy/photutils into ccd-utexas/photutils
