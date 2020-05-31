# Deviation firmware for RC transmitters
Custom version for Devo 7E
  * No standard GUI
  * Layout editor
  * Permanent timer
  * Datalog
  * Extra switches no stock (like devo7e-256)
  * Layout for 10 toggles
  * 3 Position toggles for channels
  * Flysky AFHDS 2A protocol with battery voltage, cell voltage and number of cells, without extended telemetry
  * Bayang protocol with channel LOAD (Boldclash B03-Pro stock TX)
  * Custom Frsky and DSM telemetry for Flysky AFHDS 2A and Bayang
  
The Deviation firmware project is hosted at http://www.deviationtx.com

## Current build status
[![Build Status](https://travis-ci.org/DeviationTX/deviation.png?branch=master)](https://travis-ci.org/DeviationTX/deviation?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/DeviationTX/deviation/badge.svg?branch=master)](https://coveralls.io/github/DeviationTX/deviation?branch=master)

There you can find links to:
  * pre-built binaries: http://www.deviationtx.com/downloads-new/category/1-deviation-releases
  * the wiki: http://www.deviationtx.com/wiki
  * the forums for asking questions: http://www.deviationtx.com/forum

Building Deviation requires setting up a cross-compiler.  On certain
transmitters (like the devo7e), the firmware takes up nearly 100% of the
available ROM, and we have found that only specific versions of the
cross-compiler can build it successfully.

To facilitate building Deviation consistently, we have provided Docker images
to guarantee consistent builds across platforms.  Instruction for building with
Docker can be found here: http://www.deviationtx.com/wiki/development/docker

While not recommended, other methods of building Deviation are documented
here: http://www.deviationtx.com/wiki/development
