=============================
Welcome to Yalin Li's webpage
=============================

Status
------
.. image:: https://img.shields.io/badge/status-live-brightgreen?style=flat


What's here?
------------
This repository contains the source codes used to generate the personal website of `Yalin Li <mailto:zoe.yalin.li@gmail.com>`_. You are welcome to fork this repository and use for your personal sites. Feel free to post GitHub issues for questions or just chat.

Acknowledgement to me is appreciated but not required. If you really want to say thank you, take a bus trip instead of driving, and say thank you to the bus driver.


Tips
----
Text editors
^^^^^^^^^^^^
For editors, I use `Sublime Text <https://www.sublimetext.com>`_ and found `Atom <https://atom.io>`_ to be a good free and open-source alternative.


``jekyll`` versions
^^^^^^^^^^^^^^^^^^^
If you have multiple versions of ``jekyll``, sometimies just ``jekyll new`` or ``jekyll serve`` might not be calling the correct version. In this case, the easiest solution to is to use ``bundle exec`` followed by the ``jekyll`` command (e.g., ``bundle exec jekyll new``.


``webrick``
^^^^^^^^^^^
You may run into some errors like:

.. code:: bash

	cannot load such file -- webrick (LoadError)

You can fix this by:

.. code:: bash

	bundle add webrick

This is due to the removal of the ``webrick`` dependency in ``jekyll``, for more details, refer to this GitHub `issue <https://github.com/jekyll/jekyll/issues/8523>`_, this should be released in the new release of ``jekyll``.


Acknowledgements
----------------
I got the inspiration from webpages of `Prof. Rao <https://raogroupuiuc.github.io/webpage/>`_ and `Prof. Allan <http://www.allanlab.org/aboutwebsite.html>`_. Tania Rascia's awesome `tutorial <https://www.taniarascia.com/make-a-static-website-with-jekyll/>`_ helped me pick up ``jekyll``.