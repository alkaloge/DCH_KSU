## clone<br>

cmsrel CMSSW_10_6_5<br>
cd CMSSW_10_6_5/src/;cmsenv<br>

git clone https://github.com/alkaloge/DCH_KSU.git <br>
mv DCH_KSU/TauPOG .<br>
scram b -j 4<br>

## to execute the code<br>
cd DCH_KSU/DCH<br>

. testDCH.sh // this is a wrapper that will select the channels and save a ntup for further processing<br>
