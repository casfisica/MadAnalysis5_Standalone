# MadAnalysis5_Standalone

## Installation instructions (Taken from https://launchpad.net/madanalysis5)
<par>
MadAnalysis 5 requires several external libraries in order to properly run:
 - Python 2.6 or a more recent version (but not the 3.X series)
 - The GNU GCC compiler
 - GNU make

To benefit from all options coming with the MadAnalysis 5 program, the following (optional) libraries have to be installed:
 - ROOT v5.27 or a more recent version. Root 6 is recommended.
 - Zlib headers and libraries (automatic installation: typing 'install zlib' in a madanalysis shell)
 - FastJet 3.0 or more recent (automatic installation: typing 'install fastjet' in s madanalysis shell)
 - latex and pdflatex compilers
 - the PAD (see http://madanalysis.irmp.ucl.ac.be/wiki/PublicAnalysisDatabase)
 - Delphes (automatic installation: typing 'install delphes' in a madanalysis shell)
 </par>


### Installation script:
```bash
#Source thisroot.sh !root6!
source /home/camilo/HEPTools/ROOT/root/Root6Python2_7/bin/thisroot.sh
#Download MadAnalysis5
wget https://launchpad.net/madanalysis5/trunk/v1.6/+download/ma5_v1.6.tgz
#Unzip 
tar xfv ma5_v1.6.tgz
cd madanalysis5
#Run MadAnalysis
bin/ma5
#Install all libraries as says in Installation instructions

```
