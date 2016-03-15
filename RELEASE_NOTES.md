# 2016-03-15

This is a pre-pre-alpha release.  All data is from "The Verse in
Numbers", version 2.1 (November 2014) (hereinafter referred to as
"TVIN"), available at http://pics.fireflyprops.net/TVIN-2.1.pdf.

So far only the following has been done:

## The Verse.stc:

* White Sun has been placed at an appropriate right ascension,
  declination, and distance according to the star map on page
  1.01.

* Spectral classes of stars are as given in TVIN.

* Spectral classes of protostars are assumed to be G0, on the
  assumption that helioforming would strive to make them as close
  to Sol as possible.

* Radii are as given in TVIN.

* Absolute magnitudes are derived from luminosities as given in
  TVIN.

* Orbits of stars and protostars are as given in TVIN.
  Eccentricities are all set to 0.

* The epoch is set to the Julian date for July 1, 2511.

* Mean anomaly -- where the object is at the time of the epoch
  (see below) -- is random, except for the following:

  * Georgia and Red Sun are in each other's L3 points, so Red Sun's
    anomaly is set to Georgia's anomaly plus 180 degrees.

  * At the time of the epoch, Lux and Murphy were at closest
    approach (page 2.45), so the anomalies of Lux and Georgia are
    equal, and the anomaly of Murphy (relative to Georgia) is 180
    degrees from the anomaly of Lux (from White Sun).  This puts
    White Sun, Lux, Murphy and Georgia in a straight line.

* Rotation periods are uniformly set to 720 hours (30 solar days).


## SSC files (White Sun.ssc etc.):

* Radius and orbits are as given in TVIN, except for Ithaca and
  Priam.  According to TVIN, Ithaca and Priam orbit a common
  barycenter, but I don't have that working yet, so Priam is a
  moon of Ithaca.

* Mean anomalies are set randomly between 0 and 360 degrees.
  
* Color of planets and moons is set to green ([0 1.0 0]) for
  terraformed worlds, yellow ([1.0 1.0 0]) for worlds where
  terraforming is in progress, and red ([1.0 0 0]) for
  non-terraformed worlds.

* Oblateness of all worlds is 0.

* All orbits have an inclination of 0.

* Rotation period is uniformly set to Earth normal (23.9344694
  hours) for terrestrial worlds, and the same minus 10 hours for
  gas giants.  This makes sense for terraformed worlds but can
  probably be varied for non-terraformed worlds and gas giants.

* Obliquity (axial tilt) is set to 0.0.  It should be -23.45
  degrees, but that makes moon orbits tilted as well.  There's a
  way around this, I just haven't done it yet.
  
* Other parameters are set to what appear to be reasonable values.

* Gas giants (Elphame, Daedalus, etc.) have a randomly-assigned
    texture from Celestia's included exosolar planet textures.
