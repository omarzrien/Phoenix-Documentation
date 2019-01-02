.. post:: Dec 17, 2018

BLOG: FRC 2019 Kickoff
======================

Once again it is time to kickoff a new FRC season!

The Phoenix installer and non-Windows binary kit is available for download here...

You can also find the latest firmware CRFs at each product page (the installer also installs them).

The new features included in this season's release are listed below.  
What's great about this list is that every single feature was a request from an FRC student or mentor.
Also this year's API release is **almost entirely backwards compatible**.


New features below
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Fixes
~~~~~~~~~~~~~~~~~~~~~~
* Current Limit Errata fixed from last year on Talon SRX.
* SetYaw fixed from last year to be in degrees on Pigeon IMU.

Back-breaking API changes
~~~~~~~~~~~~~~~~~~~~~~~~~~~
* If using Motion Profile Arc, be sure to set the bAuxPID flag to true in the trajectory points.  This member variable did not exist before.
* Motion Profile Trajectory point duration is now integer (milliseconds) with [0,127] ms range.
* MotionMagicArc enum removed from LabVIEW, feature is supported using the four-parameter set().

Good luck this build season!
- Omar Zrien
