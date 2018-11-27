# Delft-FEWS HydPy-Lahn

Delft-FEWS sample configuration for a HydPy model at the river Lahn in Germany.

![Lahn overview](./_images/01_overview.png)


## Getting started
Prerequisites:
* install the [HydPy framework](https://github.com/hydpy-dev/hydpy) including Python
* install the Java Runtime Environment (JRE) or Java Development Kit (JDK) suitable for Delft-FEWS 2017.02 (e.g. version 1.8), preferably 64 bits 
* get [Delft FEWS 2017.02](https://oss.deltares.nl/web/delft-fews) 
* get these demo data

Setup (typical setup of a Delft-FEWS instance):
* copy these demo data to your file system
* adapt the file `global.properties` to your local conditions:
  * `PYTHON_PATH`: path pointing to your local Python installation
* add the Delft-FEWS binaries to the directory Delft-FEWS_HydPy-Lahn/bin
* copy the appropriate Delft-FEWS launcher EXE to Delft-FEWS_HydPy-Lahn and rename it according to the INI file to be used (respect the installed Java version 32B vs. 64B)
* adapt the INI file (_`FewsDemo_HydPy_Lahn_xVV.ini`)  
  * `vm.location`: path pointing to Java installation to be used
  * further adaptions if wanted