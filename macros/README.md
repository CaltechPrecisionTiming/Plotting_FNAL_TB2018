**Example command** <br />

```
run=505To517
root -l -b -q goodplot_June2018TB_1mm.C+\(\""${run}"\",\"0\",\"1\",\"1\",\"LP2_10\",80.0,160.0,200.0,600.0,11.0,23.0,16.0,28.0,16.5,19.5,20.0,23.0,\"_LP2_10\"\)  > log.log

```

**1. run number:** <br />

Set input file name.

**2. 0:** <br />

Photek channel.

2018 June FNAL test beam setup:

If SiPM time channle < 8, it's 0.

Otherwise, it's 16.

**3. 1:** <br />

SiPM amplitude channel.

**4. 1:** <br />

SiPM time channel.

**5. LP2_10:** <br />

Threshold of time stamp picking.

**6. 80.0, 160.0:** <br />

Photek amplitude cut in mV.

**7. 200.0, 600.0:** <br />

SiPM amplitude cut in mV.
    
**8. 11.0, 23.0:** <br />

Tile position in X axis (mm).

**9. 16.0, 28.0:** <br />

Tile position in Y axis (mm).
    
**10. 16.5, 19.5:** <br />

SiPM position in X axis (mm).

**11. 20.0, 23.0:** <br />

SiPM position in Y axis (mm).
    
**12. _LP2_10:** <br />

Lable to all the plots.


