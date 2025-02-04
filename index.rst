.. _em_index:

EM GeoSci
=========

.. image:: images/casehistories.png
    :alt: em-case-histories
    :width: 100%
    :align: center

.. purpose::

    To facilitate the understanding and use of
    electromagnetics in solving exploration, geotechnical and environmental
    problems.


.. image:: disc_dipole.png
   :alt: dipole
   :width: 30%
   :align: right

.. _why:

Why EM GeoSci
-------------

Electromagnetics has not yet reached its full potential for solving problems
in the geosciences. However that is changing and today the combination of
better field systems and high quality data, advances in scientific computing,
and the exponential increase in computer power allows us to solve problems
that were not possible a few years ago. It is also becoming more common-place to
acquire laboratory or in-situ measurements of physical properties and these
are essential links in tying geophysics to questions about the earth. The
other advance is the open-source technology that
allows technical  material and ideas to be generated by multiple contributors
through sources like Github_ . Cloud-based computing environments and
open source software have also opened up portals for interacting with equations
and concepts in real time as material is being read. The goal of :ref:`EM GeoSci <em_index>`
is to blend these items as seamlessly as possible and provide a learning
environment in which geoscientists with various backgrounds and expertise can
connect with the application of electromagnetics in their field of study.
Having a resource that allows participants to answer many different questions
connected with electromagnetics will enhance efficiency of research and
applications. Moreover, this resource provides an explicit repository for
knowledge that has been acquired by practising geoscientists and, when made
available, can elevate the learning and responsible use of electromagnetics
throughout the communinity.

.. _Github: https://github.com/geoscixyz/em

.. _what:

What is EM GeoSci?
------------------

EM GeoSci is an open-source resource that emphasizes the physical principles
of electromagnetic methods and their application in solving geoscience
problems. Rigorous analytic solutions of the EM problems with specific
transmitting fields and earth models are left to existing books and research
papers, and so too are the computational details required to numerically solve
Maxwell’s equations. Our emphasis is on using analytic and numerical solutions
to understand electromagnetic fields and fluxes obtained from various types of
transmitters in different geological environments and to show how different EM
surveys, using controlled or natural sources, can be applied in practise.
`Case Histories <https://em.geosci.xyz/content/case_histories/index.html#case-histories-index>`_
play an essential role. They allow readers to make the
connection between the geoscience problem, the EM survey, and the eventual
outcome. Understanding the fundamental physics is facilitated through the use
of `Jupyter Notebooks <https://mybinder.org/v2/gh/geoscixyz/em-apps/main?filepath=index.ipynb>`_
which allow users to visualize fields and
explore understanding by changing parameters. The simulations use the open-
source package `SimPEG <https://simpeg.xyz>`_ (Simulation and Parameter
Estimation in Geophysics).


.. image:: https://mybinder.org/badge.svg
    :target: https://mybinder.org/v2/gh/geoscixyz/em-apps/main?filepath=index.ipynb
    :alt: Binder



EM GeoSci and the SEG
---------------------

.. image:: https://upload.wikimedia.org/wikipedia/en/thumb/4/4d/SEG_2016_logo.svg/1200px-SEG_2016_logo.svg.png
  :align: right
  :alt: SEG logo
  :width: 35%
  :target: https://seg.org

EM GeoSci served as the main "textbook" resource for the `SEG 2017
Distinguished Instructor Short Course
<https://doi.org/10.1190/tle40020140.1>`_
on “Geophysical Electromagnetics: Fundamentals and Applications”. We are
grateful that the SEG supported us in our open-source experiment and allowed
us to substitute EM GeoSci for the traditional hardcopy book that accompanies
the DISC.  The `Case Histories <https://em.geosci.xyz/content/case_histories/index.html#case-histories-index>`_,
which form an important component of EM GeoSci, are presented within
a synoptic Seven-Step framework that is linked to original, published and
copyrighted papers. We are grateful that the SEG has allowed us to adapt
figures and content from their publications.


EM GeoSci is under construction
-------------------------------

EM GeoSci is under active construction. We are working to fill in blank
pages and address todo's. Our  goal is to have a mature version available by the
end of 2019. In the meantime, we are making this resource available and
`inviting contributions for case histories <http://disc2017.geosci.xyz/#contribute>`_.
We welcome `feedback <http://geosci.xyz/contact>`_ about the useability of the site and the technical details.



.. Contributors
.. ------------

.. .. include:: AUTHORS.rst


How is it organized?
--------------------

.. toctree::
   :maxdepth: 1
   :name: `EM GeoSci`
   :hidden:

   apps
   contributors
   content/introduction/index
   content/physical_properties/index
   content/maxwell1_fundamentals/index
   content/maxwell2_static/index
   content/maxwell3_fdem/index
   content/maxwell4_tdem/index
   content/geophysical_surveys/index
   content/inversion/index
   content/case_histories/index
   content/references


The motivation for the structure of em.geosci follows from
:ref:`introduction_basic_electromagnetic_experiments`. The goal is to identify
topics that are logically self-contained and then use links to connect them.
At the large scale we have the following items.

- :ref:`introduction_index`:

  - Provides motivational examples, outlines the site, takes care of housekeeping
    items like notation

|

- :ref:`physical_properties_index`:

  - Is the "go-to" location for information about what the properties are, how
    they are measured, typical values etc.

|

- :ref:`maxwell1_fundamentals_index`:

  - This contains a summary and background about the formative laws
    that are the basis for Maxwell's
    equations as well as an introduction to general topics that and not survey specific.
    (eg  the basic equations in the frequency and time domain, interface conditions, concepts of fields and fluxes,
    plane waves in homogeous media, fields from electric and magnetic dipoles etc.
    )

|

- :ref:`maxwell2_static_index`:

  - This section pertains to the understanding the steady-state Maxwell's and its
    applications. Foundations for DC resistivity (DCR); Magnetometric resistivity
    (MMR), and magnetic surveys are found here.

|

- :ref:`maxwell3_fdem_index`:

  - This section pertains to understanding Maxwell's equations in the frequency
    domain. Foundations for galvanic, inductive and natural source surveys in
    frequency are presented.

|

- :ref:`maxwell4_tdem_index`:

  - This section pertains to understanding Maxwell's equations in the time domain.

|

- :ref:`geophysical_surveys_index`:

  - Self-contained folders for individual geophysical surveys are provided. For
    example DCR provides a comprehensive overview about the DC resistivity survey
    as well as links to case histories. Each Survey is linked to relevant sections
    in other portions of em.geosci so that comprehensive knowledge can be
    accessed.

|

- :ref:`inversion`:

  - This provides basic tutorial information about inversion that is applicable to
    all em surveys.

|

- :ref:`case_histories_index`:

  - These form the cornerstones of our site. They motivate the use of EM
    geophysics and they also dictate what material needs to be developed in the
    background sections. Each case history is presented with a Seven-Step
    Framework.



