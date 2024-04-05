# BAO data

This repo contains (part of) the BAO data of DESI (see below), SDSS DR7 MGS ([arXiv:1409.3242](https://arxiv.org/abs/1409.3242)) and SDSS DR12 ([arXiv:1607.03155](https://arxiv.org/abs/1607.03155)) as originally distributed with [CosmoMC](https://github.com/cmbant/CosmoMC); and eBOSS DR16
([arXiv:2007.08991](https://arxiv.org/pdf/2007.08991.pdf)).

# DESI BAO likelihoods

## version 1.0.0

BAO likelihoods corresponding to the arXiv release on April 5, 2024, see https://arxiv.org/abs/2404.03000, https://arxiv.org/abs/2404.03001, https://arxiv.org/abs/2404.03002.
**desi_2024_bao_all** contains all DESI BAO measurements, and should be used as a baseline.
BAO measurements in each redshift bin (that are considered independent) are also provided:
- **desi_2024_bao_bgs_z1**: BGS, 0.1 < z < 0.4
- **desi_2024_bao_lrg_z1**: LRG, 0.4 < z < 0.6
- **desi_2024_bao_lrg_z2**: LRG, 0.6 < z < 0.8
- **desi_2024_bao_lrgpluselg_z1**: LRG+ELG, 0.8 < z < 1.1
- **desi_2024_bao_elg_z2**: ELG, 1.1 < z < 1.6
- **desi_2024_bao_qso_z1**: QSO, 0.8 < z < 2.1
- **desi_2024_bao_lya**: Lya

Finally, the combined SDSS(eBOSS)+DESI Lya measurement is:
- **desi_2024_eboss_bao_lya**: Lya 