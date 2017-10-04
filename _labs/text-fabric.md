---
title: Text Fabric
---

# About
Processing library for handling texts and annotations.
Think of the Hebrew Bible with 4 MB of text and 33 million annotations.

It also defines a minimalistic model for such data, realised in a text-based
file format, `.tf`.

# Tech
This is a Python package, with a lot of attention to performance.
It contains quite a few loops that will frequently iterate millions of times,
so we have carefully used the parts of Python that perform well.

# Docs
The model, file format and API are documented in its
[wiki](https://github.com/Dans-labs/text-fabric/wiki).

# Status
The library is in full productive use at the ETCBC for their flagship dataset
[Biblia Hebraica Stuttgartensia Amstelodamensis](https://github.com/ETCBC/bhsa).
See also the
[pipeline](https://github.com/ETCBC/pipeline) which transports data at the institute to its website
[shebanq](https://ancient-data.org).

# Author
[Dirk Roorda](https://dans.knaw.nl/en/about/organisation-and-policy/staff/roorda)
