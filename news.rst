2013-02-13 Wednesday
--------------------

* REMINDER: please try to use the pair programming technique
* ANNOUNCEMENT: if you ever need to run other executables, for example
  ``make``, ``gcc`` or ``git`` from Python, use the `sh module
  <http://amoffat.github.com/sh/>`_
* ANNOUNCEMENT: EPFL offers Git repositories too: https://git.epfl.ch/polyrepo/

2013-02-12 Tuesday
------------------

* NOTICE: everyone who requested a Github repository should now have one.

* ERRATA: There was a mistake in my explanation of ``assertAlmostEqual`` today.

  The function signature is:

  .. code-block:: python

      assertAlmostEqual(first, second, places=7, msg=None, delta=None)

  What I explained about how ``assertAlmostEqual`` differentiates between
  ``places`` and ``delta`` by inspecting the type, was not correct. Instead, the
  third argument, if it is not a keyword argument, is *always* taken to be
  ``places``. If you want to use ``delta`` you need pass that value explicitly
  using the keyword argument.

  Using ``places``::

    assertAlmostEqual(1.126, 1.12, 2)

  Using ``delta``::

    assertAlmostEqual(1.126, 1.12, delta=0.4)

  If you try to pass in a float as ``places`` you should get an exception.

  The examples on the slides were also incorrect, sorry for the confusion.

2013-02-11 Monday
-----------------

* NOTICE: for those of you that came late: we will start at 9:00 the coming days
* NOTICE: the lunch break will be apprx. one hour, instead of 1.5
* NOTICE: the testing lecture will take place on Tuesday morning

* Notes:

  * To use anaconda you need to modify the ``PATH`` environment variable.
  * ``anaconda_on`` is something specific to my machine, sorry for the
    confusion.
  * There is a bug with the ``UTF-8 locale`` on OSX and the IPython notebook
    and a fix is available.
  * The Ipython notebook is buggy on windows and will note work :(.
  * Solutions to the Python language introduction can be found on:
    https://github.com/pcp13/scipy-lecture-notes/tree/master/intro/solutions
