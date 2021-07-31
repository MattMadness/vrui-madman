# Vrui 4.6 "Mad Man"

This repository contains a variant of [Vrui](https://web.cs.ucdavis.edu/~okreylos/ResDev/Vrui/) 4.6 that is tweaked to actually compile and install, but to also work with the KeckCAVES ARSandbox.

Some of the changes include:

* Proper including of a missing library in Images/Image.h
* Use of the Clang compiler

In order for the whole ARSandbox to work, you need other specific versions of the other software components:

* Kinect 3.7
* SARndbox 3.6

I have a bootstrap script that gets the entire thing set up automatically, it is available [here](https://github.com/MattMadness/arsb-bootstrap). I highly recommend you use it to save your time.
