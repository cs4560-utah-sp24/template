Your CS 4560 Repository
=======================

You'll be using this repository to do and submit homework assignments
for CS 4560.

Setup
-----

Clone this repository to your computer and then run the following
command to also download the autograder:

	git submodule update --init

If the autograder is ever updated, you can download the updates using:

	git submodule update --remote

That will make changes to the `.gitmodules` file; those changes are
safe to commit and push.

Work
----

Implement your web browser in `browser.py`. If you'd like, feel free
to split your browser into multiple files, as long as you import them
into `browser.py`, like this:

	from http import *
	from ui import *
	from layout import *
	...

Autograder
----------

Every time you push, the autograder will run. You can see the results
by clicking the Actions tab at the top of this page. If you click on
one of the runs on Actions page, you'll see a grade summary at the
bottom of the page.

You can see more information about the autograder, and its test, in
[that repository](https://github.com/cs4560-utah-sp24/test/tree/main).
