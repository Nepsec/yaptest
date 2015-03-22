# Checking Out Code #

If you want to make changes, go right ahead and make them to trunk.  First check it out by following the [usual instructions](http://code.google.com/p/yaptest/source/checkout).

Then later commit your changes:

svn ci

# Tagging Code #

Periodically we'll tag trunk with a human-friendly name like 'release-0.2.1'.  Here's how I created this this tag:

svn copy https://yaptest.googlecode.com/svn/trunk/ https://yaptest.googlecode.com/svn/tags/release-0.2.1 -m 'Tagging version 0.2.1 from http://pentestmonkey.net/projects/yaptest/yaptest-installation/'

# Branches #

If you want to fork the code for a while to work on a major change you can do so like this (probably - I haven't actually tired it):

svn copy https://yaptest.googlecode.com/svn/trunk/ https://yaptest.googlecode.com/svn/branches/anyoldnameforyourbranch -m 'My new branch with lots of new kickass features'

This should help avoid having trunk broken for ages.

# Merging Branches Back Into Trunk #

We'll cross that bridge when we come to it. :-)