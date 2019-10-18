# gf2x

Tracking gf2x from https://gforge.inria.fr/projects/gf2x/

This package contains routines for fast arithmetic in GF(2)[x]
(multiplication, squaring, gcd).

## What is this?

This is a verbatin, unmodified copy of gf2x from [Inria](https://gforge.inria.fr/projects/gf2x/).

Authors: Richard Brent, Pierrick Gaudry, Emmanuel Thomé, Paul Zimmermann.

Currently tracked version: **gf2x-1.2.tar.gz** (2017-07-03 14:28, 690 KiB)

### Reasons for this repository

As far as I know, gf2x isn't officially released on github.

Use this repository if you wish to add gf2x as an external dependency
to your project with "git submodule add".

Typical use case: use with Victor Shoup's [NTL library](https://github.com/fhajji/ntl).

Of course, you can alternatively simply fetch gf2x-1.2.tar.gz
from the [official download page](https://gforge.inria.fr/frs/?group_id=1874)
and drop it right into your source tree, if you prefer not to trust this
repository.

These are the **only** changes I've made to the contents of the official tar ball:

  * renamed README to README.gf2x
  * added this README.md file
  * added the file LICENCE, copied verbatim from the beginning of REAME(.gf2x)

## License

I don't own this software. Please see the file LICENSE for details.

