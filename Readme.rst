|Build Status| |Coverage Status|

PorePy: A Simulation Tool for Fractured and Deformable Porous Media written in python.
======================================================================================

PorePy is developed by the Porous Media Group at the University of
Bergen, Norway. The software is developed under projects funded by the
Reserach Council of Norway and Statoil.

Table of Contents
=================

-  `Installation <#installation>`__
-  `PorePy features <#porepy-features>`__

Installation
============

Currently only by cloning this repository. Installation by pip / conda
should be available by the start of June 2017.

PorePy features
===============

PorePy currently has the following distinguishing features: - General
grids in 2d and 3d, as well as mixed-dimensional grids defined by
intersecting fracture networks. - Support for analysis, visualization
and gridding of fractured domains. - Discretization of flow and
transport, using finite volume methods and virtual finite elements. -
Discretization of elasticity, using finite volume methods.

PorePy has no support for multi-phase problems, nor are there plans to
develop such capabilities. For this, we recommend the `Matlab Reservoir
Simulation Toolkit <www.sintef.no/projectweb/mrst/>`__.

.. |Build Status| image:: https://travis-ci.org/pmgbergen/porepy.svg?branch=develop
   :target: https://travis-ci.org/pmgbergen/porepy
.. |Coverage Status| image:: https://coveralls.io/repos/github/pmgbergen/porepy/badge.svg?branch=develop
   :target: https://coveralls.io/github/pmgbergen/porepy?branch=develop
