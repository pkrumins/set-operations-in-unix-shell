This is an implementation of 14 set operations by using only Unix utilities.

It was created by Peteris Krumins (peter@catonmat.net).
His blog is at http://www.catonmat.net  --  good coders code, great reuse.

This document is released under GNU Free Documentation License.

It was written as a supplementary material for my article "Set Operations in
the Unix Shell". This article explains how all the set operations were
created. It can be read here:

    http://www.catonmat.net/blog/set-operations-in-unix-shell/

------------------------------------------------------------------------------

The implementation contains the following 14 set operations:

    * Set Membership.
    * Set Equality.
    * Set Cardinality.
    * Subset Test.
    * Set Union.
    * Set Intersection.
    * Set Complement.
    * Set Symmetric Difference.
    * Power Set.
    * Set Cartesian Product.
    * Disjoint Set Test.
    * Empty Set Test.
    * Minimum.
    * Maximum.

They are implemented by using the following Unix utilities:

    * grep
    * awk
    * diff
    * comm
    * cat
    * sort
    * uniq
    * head
    * join
    * tail
    * wc
    * tr
    * sed
    * cut

The implementation is available in .txt (ascii), .pdf and excel 2007 (.xlsx)
formats. The latest version of this cheat sheet can always be downloaded here:

    .txt: http://www.catonmat.net/download/setops.txt
    .pdf: http://www.catonmat.net/download/setops.pdf

    excel file is available only in the source tree.

I am sorry that I didn't use LaTeX for this document but I wanted to see what
I can create in excel.

Actually I also wrote another article on the same subject called "Set
Operations in the Unix Shell Simplified" where I just listed the operations
without explaining them. It's here:

http://www.catonmat.net/blog/set-operations-in-unix-shell-simplified/


------------------------------------------------------------------------------

Have fun with unix and sets! ;)


Sincerely,
Peteris Krumins
http://www.catonmat.net

