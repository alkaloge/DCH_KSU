cmsrel CMSSW_10_6_5;
cd CMSSW_10_6_5/src/;cmsenv

git clone https://github.com/alkaloge/DCH_KSU.git
scram b -j 4

# to execute the code
cd DCH
testDCH.sh // this is a wrapper that will select the channels and save a ntup for further processing