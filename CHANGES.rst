1.2.7 (unreleased)
------------------

- Nothing changed yet.


1.2.6 (2013-10-11)
------------------

README_fixt.py was not include in the release. Fix #54.


1.2.5 (2013-10-10)
------------------

cssselect compat. See https://github.com/SimonSapin/cssselect/pull/22

tests improvments. no longer require a eth connection.

fix #55

1.2.4
-----

Moved to github. So a few files are renamed from .txt to .rst

Added .xhtml_to_html() and .remove_namespaces()

Use requests to fetch urls (if available)

Use restkit's proxy instead of Paste (which will die with py3)

Allow to open https urls

python2.5 is no longer supported (may work, but tests are broken)

1.2.3
-----

Allow to pass this in .filter() callback

Add .contents() .items()

Add tox.ini

Bug fixes: fix #35 #55 #64 #66

1.2.2
-----

Fix cssselectpatch to match the newer implementation of cssselect. Fixes issue #62, #52 and #59 (Haoyu Bai)

Fix issue #37 (Caleb Burns)

1.2.1
-----

Allow to use a custom css translator.

Fix issue 44: case problem with xml documents

1.2
---

PyQuery now use `cssselect <http://pypi.python.org/pypi/cssselect>`_. See issue
43.

Fix issue 40: forward .html() extra arguments to ``lxml.etree.tostring``

1.1.1
-----

Minor release. Include test file so you can run tests from the tarball.


1.1
---

fix issues 30, 31, 32 - py3 improvements / webob 1.2+ support


1.0
---

fix issues 24

0.7
---

Python 3 compatible

Add __unicode__ method

Add root and encoding attribute

fix issues 19, 20, 22, 23 

0.6.1
------

Move README.txt at package root

Add CHANGES.txt and add it to long_description

0.6
----

Added PyQuery.outerHtml

Added PyQuery.fn

Added PyQuery.map

Change PyQuery.each behavior to reflect jQuery api


