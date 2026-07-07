About pgvector-python-feedstock
===============================

Feedstock license: [BSD-3-Clause](https://github.com/AnacondaRecipes/pgvector-python-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/pgvector/pgvector-python

Package license: MIT

Summary: pgvector support for Python

Development: https://github.com/pgvector/pgvector-python

Documentation: https://pypi.org/project/pgvector/

This feedstock packages the **Python client** for pgvector (`import pgvector`).
It is not the PostgreSQL server extension (`CREATE EXTENSION vector`); that is
built separately as the `pgvector` package.

pgvector support for Python.
Great for online recommendations.
Supports Django, SQLAlchemy, Psycopg 3, Psycopg 2, asyncpg, pg8000, and Peewee.

Current build status
====================

All platforms:
[![CircleCI](https://img.shields.io/circleci/project/github/AnacondaRecipes/pgvector-python-feedstock/main.svg)](https://circleci.com/gh/AnacondaRecipes/pgvector-python-feedstock)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pgvector--python-green.svg)](https://anaconda.org/conda-forge/pgvector-python) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/pgvector-python.svg)](https://anaconda.org/conda-forge/pgvector-python) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/pgvector-python.svg)](https://anaconda.org/conda-forge/pgvector-python) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/pgvector-python.svg)](https://anaconda.org/conda-forge/pgvector-python) |

Installing pgvector-python
==========================

Installing `pgvector-python` from `defaults` can be achieved with:

```
conda install pgvector-python
```

or with `mamba`:

```
mamba install pgvector-python
```

It is possible to list all of the versions of `pgvector-python` available on your platform with:

```
conda search pgvector-python
```

or with `mamba`:

```
mamba search pgvector-python
```

Updating pgvector-python-feedstock
==================================

If you would like to improve the pgvector-python recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@mmcauliffe](https://github.com/mmcauliffe/)
