Intro to Testing Python
========================

What is "testing"?
-------------------
-  Defined
-  Functional vs Integration testing

    +  I'll focus on Integration testing
   
Why would I do this?
--------------------
-  Code works now, don't break it if you add to it
-  {Typin' and Hopin'} < {Software Engineering}
   
How would I do this?
--------------------
-  Doctest
-  Unittest
-  Nose
-  Pytest

Doctest: your first step into testing
-------------------------------------

Unittest: Testing SMALLTALK style! (like Gangnam Style...but with testing)
---------------------------------------------------------------------------

-  An "`xUnit<https://en.wikipedia.org/wiki/XUnit>`_" style of testing. Based on SUnit from Smalltalk
-  test isolation: why unittest creates a NEW object for EACH test method
-  mocking: because you can't test The Internet

Nose: The New Hotness
----------------------

Pytest: Latest and Greatest
----------------------------

Coverage: Will I talk about it?
-------------------------------
-  I'll evaluate it to see how useful I think it will be to new developers

References
***********
-  `Python 3.4 Doctest docs <https://docs.python.org/3.4/library/doctest.html>`_
-  `Doctest Introduction <http://pythontesting.net/framework/doctest/doctest-introduction/>`_
-  `Testing through documentation <https://pymotw.com/2/doctest/>`_
-  `Python 3.4 Unittest docs <https://docs.python.org/3.4/library/unittest.html#>`_

    +  `TestCase class docs <https://docs.python.org/3.4/library/unittest.html#unittest.TestCase>`_

-  `Ned Batchelder: Getting Started Testing - PyCon 2014 <https://www.youtube.com/watch?v=FxSsnHeWQBY>`_

    +  Ned's `notes <http://nedbatchelder.com/text/test0.html>`_ from that talk.

Give credit where it's due
---------------------------
-  `Python Testing <http://pythontesting.net/>`_
-  `Obey The Testing Goat! <http://www.obeythetestinggoat.com/>`_

    +  `TDD Resources <http://www.obeythetestinggoat.com/pages/tdd-resources.html>`_
