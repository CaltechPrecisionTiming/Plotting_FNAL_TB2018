**1. Setup** <br />

```
cmsrel CMSSW_9_2_4
cd CMSSW_9_2_4/src/
eval `scramv1 runtime -sh`
git clone git@github.com:CaltechPrecisionTiming/Plotting_FNAL_TB2018.git
```

**2. Plotting macro:** <br />
		macros/goodplot_June2018TB_1mm.C

**3. Running command:** <br />
		macros/Run505To517.sh 

**4. InputDir (change if needed):** <br />
		/eos/cms/store/group/phys_susy/razor/Timing/2018_06/data/VME/RECO/v5_combine/
    
Change if needed.

**5. OutputDir:** <br />
		/eos/user/j/jmao/www/TB_June2018_BiasVoltageScan/
    
Change to your personal cernbox directory.

Remember to make the directory before running the script:

```
mkdir /eos/user/j/jmao/www/TB_June2018_BiasVoltageScan
mkdir /eos/user/j/jmao/www/TB_June2018_BiasVoltageScan/xybins
mkdir /eos/user/j/jmao/www/TB_June2018_BiasVoltageScan/xybins/C
mkdir /eos/user/j/jmao/www/TB_June2018_BiasVoltageScan/xybins/pdf
mkdir /eos/user/j/jmao/www/TB_June2018_BiasVoltageScan/xybins/png
```

**6. Setup Cernbox sharing website:** 

https://cernbox-manual.web.cern.ch/cernbox-manual/en/web/

Remember to add /eos/user/j/jmao/www/.htaccess file to enable directory content:<br />
```Options +Indexes```

After this setup, you could share your plots with links easily.
