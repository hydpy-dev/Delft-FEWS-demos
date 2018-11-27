# Delft-FEWS HydPy-Lahn

Delft-FEWS sample configuration for a HydPy model at the river Lahn in Germany.

![Lahn overview](./_images/01_overview.png)


## Getting started
Prerequisites:
* install [HydPy framework](https://github.com/hydpy-dev/hydpy) including Python
* install Java Runtime Environment (JRE) or Java Development Kit (JDK) suitable for Delft-FEWS 2017.02 (e.g. version 1.8), preferably 64 bits 
* get [Delft FEWS 2017.02](https://oss.deltares.nl/web/delft-fews) 
* get these demo data

Setup:
* copy these demo data to your file system
* adapt file `global.properties` to your local conditions:
  * PYTHON_PATH: path pointing to your local Python installation
* add the Delft-FEWS binaries to Delft-FEWS_HydPy-Lahn/bin
* copy appropriate Delft-FEWS launcher EXE to Delft-FEWS_HydPy-Lahn and rename it according to the INI file to use (respect the installed Java version 32B vs. 64B)

  
* adapt INI file   
  * vm.location: path pointing to your local Java installation
  * further adaptions if wanted