# Description
Repository for tunning ACCESS-OM3-8km with tides

# Resources
- TPXO10 - Satellite products for tidal validation: https://www.tpxo.net/global/tpxo10
- King and Padman (2005), validation of ocean tide models around Antarctica https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2005GL023901

# Validation
- Pan-Antarctica area-weighted tidal elevation error (RMSE), tune for M2, S2, O1, K1 individually
  
# Meeting report

Last meeting: Sept 26th 2025



Meeting highlights:

- TPXO9 have very large amplitude biases for M2 and K1 components at the [continental shelf of the Weddell Sea](https://github.com/willaguiar/OM3-8km-tidal-tunning/blob/main/Validation/Jupyter/compare_TPXO9_AntTG_M2.ipynb). So we will use tidal gauges instead for validation of tidal amplitudes over the continental shelf. For off-shelf validation we can still use TPXO9.
- We have a version of the rOM3 model running with tides, and without ice shelf cavities, but the model is yet too slow/expensive/impractical for running over the 1 year length required to validate barotropic and baroclinic components. Angus is working with NRI to optimize the model by tunning core counts and expiditing the generation of reggriding weights.
- Some of the tidal gauge data is under ice shelf cavities, so it would be good to have the model running with both cavities and tides.



**Next meeting: October 30th 2025, 3:30 pm**

