RDataParser.py
===============
~~[wheel](https://gitlab.com/KOLANICH/RDataParser.py/-/jobs/artifacts/master/raw/wheels/RDataParser.py-0.CI-py3-none-any.whl?job=build)~~
[![PyPi Status](https://img.shields.io/pypi/v/RDataParser.py.svg)](https://pypi.python.org/pypi/RDataParser.py)
~~![GitLab Build Status](https://gitlab.com/KOLANICH/RDataParser.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/RDataParser.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/RDataParser.py.svg)](https://libraries.io/github/KOLANICH/RDataParser.py)
[![GNU General Public License v3 or later](https://www.gnu.org/graphics/gplv3-88x31.png)](./gpl-3.0.md)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py) 

This is a module allowing importing data stored in R native RData serialization format.
This used a Kaitai Struct-compiled [description](https://codeberg.org/KOLANICH-specs/kaitai_struct_formats/blob/RData/serialization/r_data.ksy) reverse-engineered from [R implementation](https://svn.code.sf.net/p/gwyddion/code/trunk/gwyddion/modules/file/nt-mdt.c), it is licensed on the terms of [![GNU General Public License v3](https://www.gnu.org/graphics/gplv3-88x31.png)](./gpl-3.0.md) or later. Though I personally prefer Unlicense, I'm sorry for that I'm too lazy to black box reverse engineer it from scratch entirely.


Requirements
------------
* [`kaitaistruct`](https://github.com/kaitai-io/kaitai_struct_python_runtime)
  [![PyPi Status](https://img.shields.io/pypi/v/kaitaistruct.svg)](https://pypi.python.org/pypi/kaitaistruct)
  ![License](https://img.shields.io/github/license/kaitai-io/kaitai_struct_python_runtime.svg) as a runtime for Kaitai Struct-generated code

* [`numpy`](https://github.com/numpy/numpy) ![Licence](https://img.shields.io/github/license/numpy/numpy.svg) [![PyPi Status](https://img.shields.io/pypi/v/numpy.svg)](https://pypi.org/project/numpy) [![Build status](https://github.com/numpy/numpy/actions/workflows/linux.yml/badge.svg?branch=main)](https://github.com/numpy/numpy/actions/workflows/linux.yml) [![Libraries.io Status](https://img.shields.io/librariesio/github/numpy/numpy.svg)](https://libraries.io/github/numpy/numpy) 
