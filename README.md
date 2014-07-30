krping-rhel6.4-backport-patch
=============================

Backport patch for for krping to work on RHEL6.4/SciLn 6.4/CentOS6.4

While trying to build krping benchmarking code on my Scientific Linux 6.4, I had a bunch of build errors. 
Looking closely I noticed that it was a backport issue. 
Making some changes to the package I was able to succefully build it. 


STEPS:
1. Clone the repo from git://www.openfabrics.org/~swise/krping.git
2. Go to the root dir and patch it with the krping-rhel6.4-backport.patch.
	patch < krping-rhel6.4-backport.patch

NOTE: RHEL6.4 == SciLn6.4 == CentOS6.4
