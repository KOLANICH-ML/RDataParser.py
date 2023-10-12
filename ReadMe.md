RDataParser.py
===============
~~[wheel](https://gitlab.com/KOLANICH/RDataParser.py/-/jobs/artifacts/master/raw/wheels/RDataParser.py-0.CI-py3-none-any.whl?job=build)~~
[![PyPi Status](https://img.shields.io/pypi/v/RDataParser.py.svg)](https://pypi.python.org/pypi/RDataParser.py)
~~![GitLab Build Status](https://gitlab.com/KOLANICH/RDataParser.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/RDataParser.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/RDataParser.py.svg)](https://libraries.io/github/KOLANICH/RDataParser.py)
[![GNU General Public License v3 or later](https://www.gnu.org/graphics/gplv3-88x31.png)](./gpl-3.0.md)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py) 

**We have moved to https://codeberg.org/KOLANICH-ML/RDataParser.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success and wide adoption of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

This is a module allowing importing data stored in R native RData serialization format.
This used a Kaitai Struct-compiled [description](https://codeberg.org/KOLANICH-specs/kaitai_struct_formats/blob/RData/serialization/r_data.ksy) reverse-engineered from [R implementation](https://svn.code.sf.net/p/gwyddion/code/trunk/gwyddion/modules/file/nt-mdt.c), it is licensed on the terms of [![GNU General Public License v3](https://www.gnu.org/graphics/gplv3-88x31.png)](./gpl-3.0.md) or later. Though I personally prefer Unlicense, I'm sorry for that I'm too lazy to black box reverse engineer it from scratch entirely.


Requirements
------------
* [`kaitaistruct`](https://github.com/kaitai-io/kaitai_struct_python_runtime)
  [![PyPi Status](https://img.shields.io/pypi/v/kaitaistruct.svg)](https://pypi.python.org/pypi/kaitaistruct)
  ![License](https://img.shields.io/github/license/kaitai-io/kaitai_struct_python_runtime.svg) as a runtime for Kaitai Struct-generated code

* [`numpy`](https://github.com/numpy/numpy) ![Licence](https://img.shields.io/github/license/numpy/numpy.svg) [![PyPi Status](https://img.shields.io/pypi/v/numpy.svg)](https://pypi.org/project/numpy) [![Build status](https://github.com/numpy/numpy/actions/workflows/linux.yml/badge.svg?branch=main)](https://github.com/numpy/numpy/actions/workflows/linux.yml) [![Libraries.io Status](https://img.shields.io/librariesio/github/numpy/numpy.svg)](https://libraries.io/github/numpy/numpy) 
