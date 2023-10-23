# ITCZ_lowclouds

JGRA TWI-ITCZ paper scripts README

Calculate Tv from T and q using Climate Data Operators (CDO, https://code.mpimet.mpg.de/projects/cdo) *or a programming language of choice

Calculate monthly climatologies for all ERA5 and CASCCAD data using CDO *

“pgf_forcings_monclm_savenc.ipynb” – calculates PGF fields for each of the four SBLM experiments and vertically resolved meridional Tv gradients and saves netCDF files (without tapering); Applies a Hann filter at the north and south boundaries for PGF forcing fields and saves netCDF files.

“dyn_forcings_monclm_savenc. ipynb” – applies a Hann filter at the north and south boundaries for u, v, and h forcing fields and saves netCDF files.
Run SBLM model for each experiment (all months are run in for each Fortran compile).

Figs. 1 and 2 – “tv_sst_FullTv_paper.ipynb” – produces cross sections of Tv and meridional Tv gradients

Figs. 3 and S2 – “pgf_gp_estimates_curves.ipynb” – produces PGF and geopotential plots

Figs. 4, 6, and S3 – “cv_hovm_allmon.ipynb” – produces convergence and convergence ratio plots

Figs. 5 and 8 – “tv_dtv_dp_paper.ipynb” – produces lapse rates plots

Figs. 7 and S7 “Sc_profiles_CASCCAD.ipynb” – produces low cloud plots

Fig. S1 – “pgf_estimates_suppl.ipynb” – calculates PGF fields using Full Tv and the estimate based on MSLP and SST

Figs. S4 and S5 – “uvrvw_curves_final.ipynb” – produces latitude line plots of u, v, vort, and conv as well as correl. and RMSD

Fig. S6 – “uv_budget_fulltv_final.ipynb” – SBLM u and v momentum budget plots
