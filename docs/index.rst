SikuliX and Oculix Documentation
================================

.. sidebar:: Getting Started

   * Try the :doc:`Table of Contents <toc>` 
   * Look through the :ref:`genindex`
   * Use the :ref:`search`
   * Watch the `development on GitHub <https://github.com/oculix-org/Oculix>`_

SikuliX now is Oculix
---------------------

RaiMan has finally stopped development in 2025.
Great thanks to `Julien Mer <https://github.com/julienmerconsulting>`_, who has taken over the further dev as `Oculix <https://github.com/oculix-org>`_

Document maintained by
 - `from  2026: Julien Mer <https://github.com/julienmerconsulting>`_
 - `until 2025: Raimund Hocke aka RaiMan <https://github.com/RaiMan>`_.

For any question, possible bugs and enhancement requests use the `issue tracker on GitHub <https://github.com/oculix-org/Oculix/issues>`_ .

How to use this document
------------------------

SikuliX at the top supports **scripting via SikuliX IDE** (a basic script editor to load, edit, save and run scripts including the creation/organization of the needed images for your visual workflow).

Supported scripting languages:

 - **Python** (language level 2.7) supported by the `Jython interpreter <http://www.jython.org>`_. 

 - **Ruby** (language level 1.9/2.0) supported by the `JRuby interpreter <http://jruby.org>`_.

... and more

If you are new to
programming, you can still enjoy using SikuliX to automate simple repetitive
tasks without learning one of the supported scripting languages using the SikuliX IDE.

A good start might be to have a look at the :doc:`tutorials <tutorials/index>`.

If you plan to write more
complex scripts, which might even be structured in classes and modules, you have to dive into the `Python Language
<http://www.jython.org/jythonbook/en/1.0/>`_, the `Ruby Language <http://docs.ruby-doc.com/docs/ProgrammingRuby>`_.

.. note::

    **Modules available for Python or Ruby might not be available for the SikuliX environment**,
    since Jython and JRuby are based on Java as SikuliX as well. Modules that refuse to work with SikuliX most probably use or reference native code and/or native libraries.
    So before trying to use any non-standard modules or extension packages,
    you have to check, wether they are supported in the SikuliX environment.

.. note::

    **... on Java usage:**
    The features in SikuliX at the bottom line are implemented with Java.
    So you might as well use SikuliX at this Java API level in your Java projects or other Java aware environments (:doc:`see how to <faq/030-java-dev>`). Though this documentation is targeted at the scripting people, it contains basic information about the Java level API as well at places, where there are major differences between the two API level.

Each chapter in this documentaton briefly describes 
a class or a group of methods regarding their basic features.
General usage information are provided and hints, that apply to all methods in 
that chapter. We recommend to read carefully before using the related features.

**If you are totally new with Sikuli**, it might be a good idea to just read
through this documentation sequentially. An alternative way might be to jump to the
chapters that you are interested in by scanning the :doc:`table of contents <toc>`. 
A way in the middle would be reading the core classes in this sequence:
:py:class:`Region`, then :py:class:`Match`, and finally :py:class:`Screen`.

After that, you can go to any
places of interest using the :doc:`table of contents<toc>` or 
use the :ref:`genindex` to browse all classes, 
methods and functions in alphabetical order.

The table of contents
---------------------
   
:doc:`Follow this link, to look through and dive into the content<toc>`