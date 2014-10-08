TreeStat
========

A script which gives statistics about a directory tree grouping the results by mime type.

It’s a working example in Bash of how you merge two files based on a key column and do
a group by operation to calculate sum, counts, min, max.

It uses GNU versions of standard Posix command line tools (awk, find, xargs, sort, du, rm, cut, mktemp, mimetype).

It takes one parameter which is the root directory of the tree to explore.

It returns a tab-separated list which looks like this :

    application/javascript	3822001	282	237	698728
    application/octet-stream	70721850	1459	47	16777216
    application/x-compressed-tar	26043879	4	5200994	9344566
    application/x-font-otf	36424	2	18212	18212
    application/x-font-ttf	111896	5	9860	37212
    application/x-glade	24234	1	24234	24234
    application/x-gzip	134666	1	134666	134666
    application/xml	1045	1	1045	1045
    application/x-php	8683962	484	26	387867
    application/x-python-bytecode	36998	2	14121	22877
    application/x-sharedlib	12257904	1	12257904	12257904
    application/x-shellscript	33569	32	31	14786
    application/x-shockwave-flash	119103	4	13133	57051
    application/x-x509-ca-cert	244983	1	244983	244983
    application/zip	74996	2	12461	62535
    image/gif	87533	63	37	15238
    image/png	1764106	113	80	617254
    image/svg+xml	263291	12	540	84719
    text/css	2595292	148	366	219741
    text/html	45908	3	7192	19358
    text/plain	245928	238	0	35122
    text/x-csrc	3095	2	1244	1851
    text/x-gettext-translation-template	25887	3	7470	10647
    text/x-log	284	1	284	284
    text/x-markdown	2369	2	67	2302
    text/x-python	27349	2	9774	17575
