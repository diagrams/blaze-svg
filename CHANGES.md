0.3.7 (6 June 2023)
-------------------

* Change maintainer to `diagrams` organization
* Bug fix: make `filter` node a parent rather than a leaf (thanks to
  @jpnp)
* Update and test to work with GHC 9.6

- r1 (30 Jan 2024): allow `base-4.19`, test on GHC 9.8

0.3.6.1 (13 March 2017)
-----------------------

* Allow `blaze-markup-0.8`.

0.3.6 (25 January 2016)
-----------------------

* Change to types of `a`, `aa`, and `ar`, to correct a semantic bug
  (see https://github.com/deepakjois/blaze-svg/pull/19).  Technically
  this should require a major version bump, but since this only changes
  the types of new functions just introduced in 0.3.5, which no one is
  likely to be depending on yet, I judge it more prudent to avoid the
  trouble of forcing lots of upper bound bumps.  As always, if this
  causes problems for you, just yell, and we can deprecate this
  version and do a proper 0.4 release.

0.3.5 (4 January 2016)
----------------------

* Added support for elliptical arcs (aa, ar)

0.3.4.1 (24 February 2015)
--------------------------

* Allow `blaze-markup-0.7`

0.3.4 (21 May 2014)
-------------------

* export `rotateAround`

0.3.3.1 (3 February 2014)
-------------------------

* Allow blaze-markup-0.6
