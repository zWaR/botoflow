Contributing Code
-----------------
A good pull request:

-  Is clear.
-  Works across all supported versions of Python (2.7, 3.4+).
-  Follows the existing style of the code base (PEP-8).
-  Has comments included as needed.

-  A test case that demonstrates the previous flaw that now passes with
   the included patch, or demonstrates the newly added feature.
-  If it adds/changes a public API, it must also include documentation
   for those changes.
-  Must be appropriately licensed (Apache 2.0).

Reporting An Issue/Feature
--------------------------
First, check to see if there's an existing issue/pull request for the
bug/feature. All issues are at
https://github.com/boto/botoflow/issues and pull requests are at
https://github.com/boto/botoflow/pulls.

If there isn't an existing issue there, please file an issue. The
ideal report includes:

-  A description of the problem/suggestion.
-  How to recreate the bug.
-  If relevant, including the versions of your:

   -  Python interpreter
   -  Botoflow
   -  Optionally of the other dependencies involved (e.g. Botocore, Dill, etc.)

-  If possible, create a pull request with a (failing) test case
   demonstrating what's wrong. This makes the process for fixing bugs
   quicker & gets issues resolved sooner.
