ABlog v0.7 released
===================

.. post:: May 3, 2015
   :author: Ahmet
   :category: Release
   :location: Denizli


ABlog v0.7.0 is released to fix the long standing :issue:`1` related to
pickling of Sphinx build environment on Read The Docs. Improvements
also resolved issues with using LaTeX builder, improved cross-referencing
for non-html builders.


ABlog v0.7.1 released
---------------------

.. post:: Jun 15, 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.1 is released to fix Python 3 import issues in :command:`ablog serve`
command.


ABlog v0.7.2 released
---------------------

.. post:: Jun 15, 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.2 is released to prevent potential issues with Disqus thread URLs
by requiring :confval:`disqus_shortname` and :confval:`blog_baseurl`
to be specified together for Disqus integration.


ABlog v0.7.3 released
---------------------

.. post:: July 4 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.3 makes use of `python-dateutil`_ for parsing post dates, so now you
can be flexible with the format you use in posts. Thanks to `Andy Maloney`_
for this improvement.

.. _python-dateutil: https://pypi.python.org/pypi/python-dateutil
.. _Andy Maloney: https://github.com/amaloney


ABlog v0.7.5 released
---------------------

.. post:: July 5 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.5 is released to fix Windows specific path resolving issue with
archive pages. Thanks to Peter Mills for reporting this issue.


ABlog v0.7.6 released
---------------------

.. post:: July 13 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.6 is released to fix path resolving issue that arose when
``:excerpts:`` is used in :rst:dir:`postlist` directive. Once again, thanks
to Peter Mills for reporting this issue. Other minor changes are:

  * ``-P`` argument is added to :ref:`ablog build <build>` command to enable running pdb
    on exceptions.

  * ``conf.py`` file created by :ref:`ablog start <start>` updated to include
    ``about.html`` sidebar that comes with Alabaster_ theme.

ABlog v0.7.7 released
---------------------

.. post:: July 24 2015
   :author: Ahmet
   :category: Release
   :location: SF

ABlog v0.7.7 is released to fix path resolving :issue:`41` that arose when
cross-references were used in post excerpts, and also post redirect
issue in templates.
