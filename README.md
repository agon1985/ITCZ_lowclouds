# ITCZ_lowclouds

JGRA TWI-ITCZ paper scripts README
Calculate Tv from T and q using CDO *or a programming language of choice
Calculate monthly climatologies for all ERA5 and CASCCAD data using CDO*
“pgf_forcings_monclm_savenc.ipynb” – Calculates PGF fields for each of the four SBLM experiments and vertically resolved meridional Tv gradients and saves netCDF files (without tapering); Applies a Hann filter at the north and south boundaries for PGF forcing fields and saves netCDF files.
“dyn_forcings_monclm_savenc. ipynb” – Applies a Hann filter at the north and south boundaries for u, v, and h forcing fields and saves netCDF files.
Run SBLM model for each experiment (all months are run in for each Fortran compile)
“tv_sst_FullTv_paper.ipynb” – produces cross sections of Tv and meridional Tv gradients
“pgf_gp_estimates_curves.ipynb” – produces PGF and geopotential plots
“cv_hovm_allmon.ipynb” – produces convergence and convergence ratio plots
“tv_dtv_dp_paper.ipynb” – produces lapse rates plots
“Sc_profiles_CASCCAD.ipynb” – produces low cloud plots

Supplemental figures
“pgf_estimates_suppl.ipynb” – Calculates PGF fields using Full Tv and the estimate based on MSLP and SST
Same script #7
Same as script #8
“uvrvw_curves_final.ipynb” – Produces latitude line plots of u, v, vort, and conv as well as correl. and RMSD
“uv_budget_fulltv_final.ipynb” – SBLM u and v momentum budget plots
Same as script #10
