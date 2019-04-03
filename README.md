# Optical Counterparts to Gravitational Waves

_Dissertation Presented to the Graduate Faculty of The University of Texas at San Antonio In Partial Fulfillment Of the Requirements For the Degree of Doctor of Philosophy in Physics_

By Martin Beroiz.

## Abstract

The novel field of Gravitational Wave Astronomy has opened a new window to the universe.
Never before had we received gravitational waves from the distant celestial bodies carried away by space-time perturbations, until the detection of GW150914 on September 14, 2015.
But these signals, however faint, carry very little information about their positions on the sky.
The sky localization can have uncertainties that span up to a few hundreds square degrees, which makes locating the sources very difficult.

Traditional Astronomy can complement this limitation of gravitational wave detection where optical astronomy is stronger: localization.
However, this poses other technological challenges of a different kind.
In the era of multi-messenger Astronomy, a low latency response time after detection is crucial in order to have any hope of detecting the optically faint electromagnetic counterparts of the event.

The mission of the Transient Optical Robotic Observatory of the South (TOROS), in the context of multi-messenger and time-domain astronomy, is to create a facility ready to respond to gravitational wave detections for prompt follow-up observations searching for optical counterparts.

This dissertation discusses the implementation of a software pipeline for the TOROS project and the results obtained during the O1 campaign of Advanced LIGO.

### Important Notice

The git-version controlled copy of this thesis is intended as a live update of my doctoral thesis.

### Disclaimer

This may not faithfully reflect the final version of the doctoral thesis in its entirety.

For the official doctoral thesis approved and published by the University of Texas at San Antonio, please checkout version 1.1 of this repository, which best reflects the printed version.

Further versions and commits are intended to improve the software development side of the project but will seldom modify the content.

### Compilation and installation

To compile the LaTeX document, a makefile is provided. In Unix-like systems, type:

    $ make

This will create auxiliary files in `obj/` folder and the final pdf file in there as well.

    $ make install

simply copies the final document `thesis.pdf` at the makefile directory level.

**(c) Copyright 2017 Martin Beroiz All rights reserved.**
