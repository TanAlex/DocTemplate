.. DocTemplate documentation master file, created by
   sphinx-quickstart on Fri Mar  8 19:24:25 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to DocTemplate's documentation!
=======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


`Read the Docs`_ simplifies software documentation
by automating building, versioning, and hosting of your docs for you.
Think of it as *Continuous Documentation*.

Never out of sync
    Whenever you push code to your favorite version control system,
    whether that is Git, Mercurial, Bazaar, or Subversion,
    Read the Docs will automatically build your docs
    so your code and documentation are always up-to-date.

Multiple versions
    Read the Docs can host and build multiple versions of your docs
    so having a 1.0 version of your docs and a 2.0 version
    of your docs is as easy as having a separate branch or tag in your version control system.

Free and open source
    Read the Docs is free and open source and hosts documentation
    for nearly 100,000 large and small open source projects
    in almost every human and computer language.

.. _Read the docs: http://readthedocs.org/

First steps
-----------

Are you new to software documentation
or are you looking to use your existing docs with Read the Docs?
Learn about documentation authoring tools such as Sphinx and MkDocs
to help you create fantastic documentation for your project.

* **Getting started**:
  :doc:`With Sphinx <intro/getting-started-with-sphinx>` 

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: First Steps

   intro/getting-started-with-sphinx

In order to get all the dependencies successfully installed,
you need these libraries.

.. tabs::

   .. tab:: Mac OS

      If you are having trouble on OS X Mavericks
      (or possibly other versions of OS X) with building ``lxml``,
      you probably might need to use Homebrew to ``brew install libxml2``,
      and invoke the install with::

          CFLAGS=-I/usr/local/opt/libxml2/include/libxml2 \
          LDFLAGS=-L/usr/local/opt/libxml2/lib \
          pip install -r requirements.txt

   .. tab:: Ubuntu

      Install::

        sudo apt-get install build-essential
        sudo apt-get install python-dev python-pip python-setuptools
        sudo apt-get install libxml2-dev libxslt1-dev zlib1g-dev

      If you don't have redis installed yet, you can do it with::

         sudo apt-get install redis-server

   .. tab:: CentOS/RHEL 7

         sudo yum install python-devel python-pip libxml2-devel libxslt-devel

   .. tab:: Other OS

      On other operating systems no further dependencies are required,
      or you need to find the proper equivalent libraries.

How we envision versions working
--------------------------------

Another test sub item
--------------------------------