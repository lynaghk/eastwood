Dec 24 2013: Lots of exceptions about *runner* not being bound while
linting, I think limited to the test namespaces.  These are likely due
to the use of speclj for writing tests.  I do not know how to avoid
those errors when linting.  Added to lint.sh so that it only lints
:source-paths, not :test-paths.

Oct 9 2018: After updating to most recent version of reply source code,
similar exceptions occurred with error messages about *runner* not
being bound.
