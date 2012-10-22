ns-3-backoff-patch
==================

A temporary workaround for the ns-3 wireless backoff problem

The dcf-manager.patch is based on the following bug discussion:
https://www.nsnam.org/bugzilla/show_bug.cgi?id=737

The dca-txop.patch is based on the following discussion in the ns-3-user google group:
https://groups.google.com/d/topic/ns-3-users/AHL3FI7iqhA/discussion

Note: The dca-txop.patch may not have any effect. And neither of the above patches can completely solve the backoff problems. For more discussion, checkout the following discussions:
https://www.nsnam.org/bugzilla/show_bug.cgi?id=912
https://www.nsnam.org/bugzilla/show_bug.cgi?id=977
http://mailman.isi.edu/pipermail/ns-developers/2010-August/008240.html

Apply the patch
===============

In your ns-3.15 directory:
hg import patchname.patch
