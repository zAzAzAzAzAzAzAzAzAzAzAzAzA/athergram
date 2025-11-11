Install Guide
=============

Being a modern Python framework, Pyrogram requires an up to date version of Python to be installed in your system.
We recommend using the latest versions of both Python 3 and pip.


-----

Install Pyrogram
----------------

Pyrogram is distributed via GitHub Releases only (not available on PyPI).

From GitHub
^^^^^^^^^^^

Install the latest release:

    .. code-block:: text

        $ pip3 install git+https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram.git@latest

Install a specific version (replace v2.2.16 with desired version):

    .. code-block:: text

        $ pip3 install git+https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram.git@v2.2.16

With TgCrypto (Recommended)
^^^^^^^^^^^^^^^^^^^^^^^^^^^

For better performance, install with :doc:`TgCrypto <../topics/speedups>`:

    .. code-block:: text

        $ pip3 install git+https://github.com/ohmyarthur/tgcrypto.git
        $ pip3 install git+https://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram.git@latest

Verifying Installation
^^^^^^^^^^^^^^^^^^^^^^

To verify that Pyrogram is correctly installed, open a Python shell and import it.
If no error shows up you are good to go.

.. parsed-literal::

    >>> from pyrogram import __version__
    >>> __version__
    '2.2.20'

.. _`Github repo`: http://github.com/zAzAzAzAzAzAzAzAzAzAzAzAzA/athergram
