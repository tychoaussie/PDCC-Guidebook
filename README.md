# PDCC-Guidebook
Simple guide for creating dataless SEED files for a new seismic station using PDCC
It is not always an easy task to create a dataless SEED file for a new seismic station, especially when you haven't done it before.
This guidebook is a supplement to the IRIS PDCC utility, and does not replace the already good IRIS PDCC user manual.
What this guidebook does, is show you how to clone and modify an existing dataless SEED for a basic three component station.
Whereas the PDCC manual shows you how to navigate around the PDCC utility, this guidebook is created to show you which fields within
the blockettes are important, how they relate to one another, and how to change them such that what you end up with is a set of metadata
that correctly interprets the seismic data from units of counts, into accurate and calibrated ground motion. The "response" of a given
channel is a product of several stages: 
There is the instrument itself, with it's own sensitivities and frequency response.
There are the intermediate circuitry: This could be a pre-amplifier or filter.
There is the digitizer itself: Ultimately it converts the signal voltage into a measurement in terms of counts.
All of these things are described within the dataless SEED. 
This guide book takes you through the creation of the very first edition of your dataless SEED. Once it is created, PDCC can be used
to update the SEED as the sensor calibrations or channel configurations change.

Supplemental files include:
Sample calibration sheets for a typical S-13 short-period electromechanical seismic station with 24-bit digitizer.
Utilizes a simple two-pole and zero response description.
Sample SAC poles & zeros files for the Geotech S-13 that match the above cal sheets.
Excel worksheet for calculating the critical fields for the three channels. This document will accompany the guide book
in order to assist you in calculating the appropriate fields.
