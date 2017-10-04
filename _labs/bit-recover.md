---
title: Bit Recover
---

# About
When you store TeraBytes of data for many years, some bits in it will decay.
It is hard to get figures about how much damage we can expect.
But it might be in the order of a handful per TB per year.

How do we recover from it? Here is an elegant method
Add some redundancy, in the form of checksums.
Periodically check the checksums.
When there are errors, use the checksums to correct the errors, if possible.
If it is not possible, use a backup. But beware: the backup might have errors as well.
Even the checksums themselves might have errors. Before we explain our strategy,
here is an example that it actually works.

# Tech
This is a Perl package using standard modules for computing checksums.

# Docs
The method and the experiments done are reported on
[readthedocs](http://bit-recover.readthedocs.io/en/latest/about.html).

# Status
The library is in use at the DANS, but only for one case of
an encrypted dataset of 500 GB. We have monitored this set from 2013 onwards,
and so far no bit has fallen.

# Author
[Dirk Roorda](https://dans.knaw.nl/en/about/organisation-and-policy/staff/roorda)
