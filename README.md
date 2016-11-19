APCu Backwards Compatibility Module
===============================

[![Build Status](https://travis-ci.org/krakjoe/apcu-bc.svg?branch=master)](https://travis-ci.org/krakjoe/apcu-bc)

This module provides a backwards APC compatible API using [APCu](https://github.com/krakjoe/apcu).

Performance
===========

There is no appreciable difference between using apcu_* functions or the aliases this compatibility lib provides; This layer calls the same internal (to apc) functions that APCu does, but just accepts the old parameters, the only meaningful difference is prototypes and names of functions.
