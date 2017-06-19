grbm:  good fit.  This is odd.  The grbm has better stats than the sbpl.  Rare.  All stats for grbm are better than sbpl.
   1    1   grbm       alpha               -1.23353     +/-  7.03529E-03  
   2    1   grbm       beta                -2.66344     +/-  3.42549E-02  
   3    1   grbm       tem        keV      287.541      +/-  6.72299      
   4    1   grbm       norm                0.110910     +/-  1.24623E-03

sbpl:  good fit.
   1    1   sbpl       alpha      NONE     -1.34873     +/-  5.55615E-03  
   2    1   sbpl       beta       NONE     -2.60275     +/-  2.65581E-02  
   3    1   sbpl       ebreak     keV      183.743      +/-  4.70021      
   4    1   sbpl       norm                7.99483E-02  +/-  3.36430E-04 

copl:  doens't really fit the high-energy BGO, LLE or LAT data.
   1    1   copl       cplIndex   NONE     -1.25838     +/-  6.11483E-03  
   2    1   copl       highEcut   NONE     324.163      +/-  6.49575      
   3    1   copl       norm                0.106093     +/-  9.89117E-04

grbm+lpow:  PL kept jumping around during fitting.  PL is insignificant at all slopes.  Not a good fit.  Issues with PL errors, as expected.
   1    1   grbm       alpha               -1.23385     +/-  7.03258E-03  
   2    1   grbm       beta                -2.67022     +/-  3.61811E-02  
   3    1   grbm       tem        keV      288.007      +/-  6.74596      
   4    1   grbm       norm                0.110842     +/-  1.24512E-03  
   5    2   lpow       plIndex    NONE     -0.425185    +/-  5.03778      
   6    2   lpow       norm                4.44602E-10  +/-  2.12071E-08

sbpl+lpow:  PL insignificant.  Couldn't get errors.  bad fit.
   1    1   sbpl       alpha      NONE     -1.34893     +/-  5.56085E-03  
   2    1   sbpl       beta       NONE     -2.60560     +/-  2.74348E-02  
   3    1   sbpl       ebreak     keV      184.158      +/-  4.79268      
   4    1   sbpl       norm                7.99465E-02  +/-  3.36530E-04  
   5    2   lpow       plIndex    NONE     -0.445013    +/-  10.6258      
   6    2   lpow       norm                3.30131E-10  +/-  3.39151E-08

copl+lpow:  Good errors, but not the best fit to data.  Stats weren't as good as grbm, sbpl.
   1    1   copl       cplIndex   NONE     -1.25463     +/-  1.22552E-02  
   2    1   copl       highEcut   NONE     321.400      +/-  8.70081      
   3    1   copl       norm                0.105898     +/-  1.06608E-03  
   4    2   lpow       plIndex    NONE     -1.76881     +/-  0.297844     
   5    2   lpow       norm                3.61753E-04  +/-  7.52033E-04

grbm+blackb:  Good fit, errors and stats.
   1    1   grbm       alpha               -1.22634     +/-  7.66621E-03  
   2    1   grbm       beta                -2.61850     +/-  3.39352E-02  
   3    1   grbm       tem        keV      283.985      +/-  7.72480      
   4    1   grbm       norm                0.111121     +/-  1.58158E-03  
   5    2   blackb     kT         keV      8.49007      +/-  1.93345      
   6    2   blackb     norm                2.64173E-04  +/-  8.62233E-05


sbpl+blackb:  good fit, good errors and stats.
   1    1   sbpl       alpha      NONE     -1.33231     +/-  7.70076E-03  
   2    1   sbpl       beta       NONE     -2.60958     +/-  2.89208E-02  
   3    1   sbpl       ebreak     keV      188.509      +/-  6.13028      
   4    1   sbpl       norm                7.86576E-02  +/-  5.31250E-04  
   5    2   blackb     kT         keV      9.02908      +/-  0.602031     
   6    2   blackb     norm                9.76281E-04  +/-  2.12349E-04


copl+blackb:  good fit, good errors, good stats.
   1    1   copl       cplIndex   NONE     -1.20683     +/-  1.21869E-02  
   2    1   copl       highEcut   NONE     304.205      +/-  7.82420      
   3    1   copl       norm                0.107505     +/-  1.28927E-03  
   4    2   blackb     kT         keV      6.84689      +/-  0.449850     
   5    2   blackb     norm                3.44278E-03  +/-  1.01283E-03

*** None of these BB really poked through the other model.  So it's hard to tell how significant they are.


grbm+blackb+lpow:  Can't get PL to be significant.  No errors.  Bad fit.
   1    1   grbm       alpha               -1.24788     +/-  1.80210E-02  
   2    1   grbm       beta                -2.67822     +/-  3.81512E-02  
   3    1   grbm       tem        keV      299.566      +/-  15.8246      
   4    1   grbm       norm                0.107878     +/-  3.69659E-03  
   5    2   blackb     kT         keV      27.4243      +/-  8.56322      
   6    2   blackb     norm                5.15549E-06  +/-  8.77058E-06  
   7    3   lpow       plIndex    NONE     -0.393979    +/-  4.72717      
   8    3   lpow       norm                3.07381E-10  +/-  2.33368E-08


sbpl+blackb+lpow:  PL insignificant.  Can't get it to be significant.  Bad fit.  No errors.
   1    1   sbpl       alpha      NONE     -1.26041     +/-  1.39321E-02  
   2    1   sbpl       beta       NONE     -2.60198     +/-  2.74218E-02  
   3    1   sbpl       ebreak     keV      174.202      +/-  5.25982      
   4    1   sbpl       norm                7.95610E-02  +/-  4.36612E-04  
   5    2   blackb     kT         keV      6.66459      +/-  0.295002     
   6    2   blackb     norm                6.35462E-03  +/-  1.28965E-03  
   7    3   lpow       plIndex    NONE     -0.448140    +/-  11.0337      
   8    3   lpow       norm                3.31827E-10  +/-  3.58372E-08


copl+blackb+lpow:  good fit, errors and stats.
   1    1   copl       cplIndex   NONE     -1.31355     +/-  1.65578E-02  
   2    1   copl       highEcut   NONE     384.677      +/-  18.0628      
   3    1   copl       norm                9.41659E-02  +/-  2.38260E-03  
   4    2   blackb     kT         keV      25.5011      +/-  1.63270      
   5    2   blackb     norm                3.27543E-05  +/-  8.49215E-06  
   6    3   lpow       plIndex    NONE     -1.76014     +/-  0.309807     
   7    3   lpow       norm                3.33478E-04  +/-  7.00564E-04  






