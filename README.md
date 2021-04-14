# ModelingOdorProjection
ModelingOdorProjection
##Codes for the modeling part

Keep all the .m files in same folder.

Place the data files in the folder Data.

#To generate figure5 run make_figure5A_B_C_S5.m
Which needs the functions makeOdors, makeOdors11, makePiriform, makePiriform_Schaffer, makeXmagnitudes, makeXmagnitutesCorr and MvLogNRand
We have used some functions form Schaffers et al. Neuron 2018 for comparing the results with their model.

To generate figures 6 and 7 use make_figure6A_B, make_figure6C_D, make_figure7A_B, make_figure7C_D respectively. Which will use the functions sparsenessTR, lifetimeSparsenessTRInRegion and populationSparsenessTRInRegion.

To generate figure 8 use Odor_identity_decoding_normal_syn_degree_abs_resp and Odor_identity_decoding_normal_syn_degree_abs_resp for figure A and B respectively. generalLeav1OutDecoder function will be used to execute the codes.
