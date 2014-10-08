TreeStat
========

A script which gives statistics about a directory tree grouping the results by mime type.

It’s a working example in Bash of how you merge two files based on a key column and do
a group by operation to calculate sum, counts, min, max.

It uses GNU versions of standard Posix command line tools (awk, find, xargs, sort, du, rm, cut, mktemp, mimetype).

It takes one parameter which is the root directory of the tree to explore.
