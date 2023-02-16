Matlab functions for determining in vivo creatine CEST exchange rates. Two-step Bloch-McConnell (BM) fitting is implemented to quantify the exchange rates from the pure CrCEST lineshape, B1-dependent CrCEST, and the pH response with different B1 values. 
Step 1:
The first step for all three methods is extracting  parameters for the magnetization transfer (MT) lineshape using function Step1_BackgroundFit.m. The MT paremeters will be saved to BGpara file in the following order
Water T1 (s); water T2(s); MT T2 (ms); MT fraction with respect to water; MT offset (ppm)

Step 2:
1. CrCEST lineshape fitting: Step2_lineshape_fitting.m 
2. Multiple B1 CrCEST signal: Step2_pwrdependentfit.m
3.CrCEST signal change due to pH reduction (0.2) as a function of exchange rate :Step2_phresponse.m
