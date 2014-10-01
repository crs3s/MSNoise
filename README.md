MSNoise
=======

A Python Package for Monitoring Seismic Velocity Changes using Ambient Seismic Noise.


[![Build Status](https://travis-ci.org/ROBelgium/MSNoise.png)](https://travis-ci.org/ROBelgium/MSNoise)
[![Analytics](https://ga-beacon.appspot.com/UA-55331253-1/MSNoise/readme)]

MSNoise is the first complete software package for computing and monitoring relative velocity variations using ambient seismic noise. 
MSNoise is a fully-integrated solution that automatically scans data archives and determines which jobs need to be done whenever the scheduled task is executed. 

MSNoise is a joint project of the Royal Observatory of Belgium (Thomas Lecocq and Corentin Caudron) and ISTerre + IPGP (Florent Brenguier)

Documentation
---------------
Currently, the full documentation can be found on: http://www.msnoise.org.


Packaging
----------
Currently, MSNoise is *NOT* a regular Python Package, which means:

* It doesn't have a setup.py file.
* It should not be installed in the lib/site-packages folder of the current python installation.
* It will create folder *within* its root folder (CROSS_CORRELATION, STACKS, MWCS, DTT folders). Thus:
* It should be installed in a folder that is writable to the user.

This should change in the future. Until then, when multiple users want to use MSNoise on the same machine, it would be better to have a copy of MSNoise for each (even: one copy for each "project").



Getting Help
-------------
The best way to get help is to subscribe to the Mailing List and ask your question directly there. It is available on 
http://mailman-as.oma.be/mailman/listinfo/msnoise and the archive is either http://mailman-as.oma.be/pipermail/msnoise/ or 
on http://news.gmane.org/gmane.science.geophysics.msnoise for a nice view.



Disclaimer
----------

Although we have cross-checked the whole code, we cannot warranty it is exempt of bugs. The package is provided as-is, we will not be held responsible for any use you make of it, nor for the results and conclusions you may find using MSNoise.

Licence
----------

Although MSNoise is provided freely on the internet and every individual may use it, we do not allow anyone to provide commercial service (read -paid in any way-), like training or teaching without contacting the original authors first. The authors and the contact email address are in the __init__.py file of the package.