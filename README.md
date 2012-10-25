ns-3-backoff-patch
==================

A temporary workaround for the ns-3 wireless backoff problem

The dcf-manager.patch is based on the following bug discussion:

https://www.nsnam.org/bugzilla/show_bug.cgi?id=737

The above patche can completely solve the backoff problems. For more discussion, checkout the following discussions:

https://www.nsnam.org/bugzilla/show_bug.cgi?id=912

https://www.nsnam.org/bugzilla/show_bug.cgi?id=977

http://mailman.isi.edu/pipermail/ns-developers/2010-August/008240.html

Apply the patch
===============

In your ns-3.15 directory:
hg import patchname.patch
