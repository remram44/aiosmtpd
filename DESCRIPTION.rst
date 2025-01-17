######################################
 aiosmtpd - asyncio based SMTP server
######################################

| |github license| |_| |PyPI Version| |_| |PyPI Python| |_| |PyPI PythonImpl|
| |GA badge| |_| |CodeQL badge| |_| |codecov| |_| |readthedocs|
| |GH Release| |_| |GH PRs| |_| |GH LastCommit|
| |PyPI DL| |_| |GH DL|
|
| |GH Discussions|
|

.. .. U+00A0 is non-breaking space
.. |_| unicode:: 0xA0
   :trim:
.. |github license| image:: https://img.shields.io/github/license/aio-libs/aiosmtpd?logo=Open+Source+Initiative&logoColor=0F0
   :target: https://github.com/aio-libs/aiosmtpd/blob/master/LICENSE
   :alt: Project License on GitHub
.. |PyPI Version| image:: https://img.shields.io/pypi/v/aiosmtpd?logo=pypi&logoColor=yellow
   :target: https://pypi.org/project/aiosmtpd/
   :alt: PyPI Package
.. |PyPI Python| image:: https://img.shields.io/pypi/pyversions/aiosmtpd?logo=python&logoColor=yellow
   :target: https://pypi.org/project/aiosmtpd/
   :alt: Supported Python Versions
.. |PyPI PythonImpl| image:: https://img.shields.io/pypi/implementation/aiosmtpd?logo=python
   :target: https://pypi.org/project/aiosmtpd/
   :alt: Supported Python Implementations
.. .. For |GA badge|, don't forget to check actual workflow name in unit-testing-and-coverage.yml
.. |GA badge| image:: https://github.com/aio-libs/aiosmtpd/workflows/aiosmtpd%20CI/badge.svg
   :target: https://github.com/aio-libs/aiosmtpd/actions/workflows/unit-testing-and-coverage.yml
   :alt: GitHub CI status
.. |CodeQL badge| image:: https://github.com/aio-libs/aiosmtpd/workflows/CodeQL/badge.svg
   :target: https://github.com/aio-libs/aiosmtpd/actions/workflows/codeql.yml
   :alt: CodeQL status
.. |codecov| image:: https://codecov.io/github/aio-libs/aiosmtpd/coverage.svg?branch=master
   :target: https://codecov.io/github/aio-libs/aiosmtpd?branch=master
   :alt: Code Coverage
.. |readthedocs| image:: https://img.shields.io/readthedocs/aiosmtpd?logo=Read+the+Docs
   :target: https://aiosmtpd.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status
.. |GH Release| image:: https://img.shields.io/github/v/release/aio-libs/aiosmtpd?logo=github
   :target: https://github.com/aio-libs/aiosmtpd/releases
   :alt: GitHub latest release
.. |GH PRs| image:: https://img.shields.io/github/issues-pr/aio-libs/aiosmtpd?logo=GitHub
   :target: https://github.com/aio-libs/aiosmtpd/pulls
   :alt: GitHub pull requests
.. |GH LastCommit| image:: https://img.shields.io/github/last-commit/aio-libs/aiosmtpd?logo=GitHub
   :target: https://github.com/aio-libs/aiosmtpd/commits/master
   :alt: GitHub last commit
.. |PyPI DL| image:: https://img.shields.io/pypi/dm/aiosmtpd?logo=pypi
   :target: https://pypi.org/project/aiosmtpd/
   :alt: PyPI monthly downloads
.. |GH DL| image:: https://img.shields.io/github/downloads/aio-libs/aiosmtpd/total?logo=github
   :target: https://github.com/aio-libs/aiosmtpd/releases
   :alt: GitHub downloads
.. |GH Discussions| image:: https://img.shields.io/github/discussions/aio-libs/aiosmtpd?logo=github&style=social
   :target: https://github.com/aio-libs/aiosmtpd/discussions
   :alt: GitHub Discussions

This is a server for SMTP and related MTA protocols,
similar in utility to the standard library's |smtpd.py|_ module,
but rewritten to be based on ``asyncio`` for Python 3.7+.

Please visit the `Project Homepage`_ for more information.

.. _`Project Homepage`: https://aiosmtpd.readthedocs.io/
.. |smtpd.py| replace:: ``smtpd.py``
.. _`smtpd.py`: https://docs.python.org/3/library/smtpd.html


Signing Keys
============

Starting version 1.3.1,
files provided through PyPI or `GitHub Releases`_
will be signed using one of the following GPG Keys:

.. _`GitHub Releases`: https://github.com/aio-libs/aiosmtpd/releases

.. .. In the second column of the table, prefix each line with "| "
   .. In the third column, refrain from putting in a direct link to keep the table tidy.
      Rather, use the |...|_ construct and do the replacement+linking directive below the table

+-------------------------+------------------------------------+-----------+
| GPG Key ID              | Owner / Email                      | Key       |
+=========================+====================================+===========+
| ``5D60 CE28 9CD7 C258`` | | Pandu POLUAN /                   | |pep_gh|_ |
|                         | | pepoluan at gmail period com     |           |
+-------------------------+------------------------------------+-----------+
| ``5555 A6A6 7AE1 DC91`` | | Pandu E POLUAN                   |           |
|                         | | pepoluan at gmail period com     |           |
+-------------------------+------------------------------------+-----------+
| ``E309 FD82 73BD 8465`` | | Wayne Werner                     |           |
|                         | | waynejwerner at gmail period com |           |
+-------------------------+------------------------------------+-----------+

.. .. The |_| contruct is U+00A0 (non-breaking space), defined at the start of the file
.. |pep_gh| replace:: On |_| GitHub
.. _`pep_gh`: https://github.com/pepoluan.gpg
