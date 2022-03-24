=================
All about my work
=================

.. toctree::
   :maxdepth: 1

   software
   successful-projects
   unsuccessful-projects


Some basic formatting
=====================

.. sidebar:: This is a sidebar

    This is the body of the sidebar.

*Emphasis* usually appears in italics. **This strongly-emphasised text** will usually appear
in bold.

* item
* item


Some links
==========

The list of links below appears in a ``seealso`` directive.

.. seealso::

    * `Example <https://example.com>`_
    * `Python <https://python.org>`_


Code
====

Sphinx has a number of parsers for automated language highlighting in
code-blocks. It does a good job of guessing what language you're using,
but you can also state that explicitly as in this example:

 .. code-block:: bash
    :emphasize-lines: 2-3

    python3 -m venv sphinxenv
    source sphinxenv/bin/activate
    pip install sphinx
    pip freeze > requirements.txt
