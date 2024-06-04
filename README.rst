What Is It ?
============


.. image:: https://github.com/SciKit-Surgery/what-is-it/raw/master/what-is-it.gif
   :height: 128px
   :target: https://scikit-surgery.github.io/what-is-it/
   :alt: Logo

|

.. image:: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg
   :target: CODE_OF_CONDUCT.md

.. image:: https://img.shields.io/twitter/follow/scikit_surgery?style=social
   :target: https://twitter.com/scikit_surgery?ref_src=twsrc%5Etfw
   :alt: Follow scikit_surgery on twitter

Author: Stephen Thompson

what-is-it is a browser based game. It was developed primarily to study and
communicate the problem of "limited field of view", how does only seeing
part of an object effect our ability to identify the object? Limited field of
view is a common problem in key hole surgery where the surgeon is only
able to see a tiny part of the anatomy through a key hole camera.

To make what-is-it playable for non surgeons we've used drawings of
everyday objects taken from The from Google's `Quickdraw`_ data set.
Each drawing is drawn by a human and
correctly identified by Google's AI.

The game starts with complete images, and a multiple choice list from which
you can select the most likely answer. Once you've warmed up
(got 3 correct answers in a row)
we introduce an image mask based on a
medical ultrasound probe to make it harder. We used an ultrasound probe
as a second aspect of the game design was to study ways to simulate
ultrasound imaging for the general public.
The presence of speckle type noise is
often cited as a difficulty in using ultrasound imaging.

Play it `here`_

what-is-it is developed with the support of the `Wellcome EPSRC Centre for Interventional and Surgical Sciences`_ as part of the `SciKit-Surgery`_ software project.

Licensing and copyright
-----------------------

Copyright 2019 Stephen Thompson.
What is It? is released under the BSD-3 license. Please see the `license file`_ for details.


Acknowledgements
----------------

Supported by `Wellcome`_ and `EPSRC`_.

.. _`Quickdraw`: https://github.com/googlecreativelab/quickdraw-dataset
.. _`Wellcome`: https://wellcome.ac.uk/
.. _`EPSRC`: https://www.epsrc.ac.uk/
.. _`here`: https://scikit-surgery.github.io/what-is-it/
.. _`license file`: https://github.com/SciKit-Surgery/what-is-it/blob/master/LICENSE
.. _`SciKit-Surgery`: https://github.com/SciKit-Surgery/
.. _`Wellcome EPSRC Centre for Interventional and Surgical Sciences`: http://www.ucl.ac.uk/weiss

