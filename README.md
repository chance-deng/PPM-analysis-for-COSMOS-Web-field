# PPM-analysis-for-COSMOS-Web-field

We use a sample of 449 SMGs from the $A^{3}COSMOS$ catalog and control samples of main-sequence star-forming galaxies (SFGs) from COSMOS2025 in the COSMOS-Web JWST field, we apply the Poisson Probability Method (PPM) to identify overdensity structures. We upload here the results of PPM analysis performed on all samples (based on COSMOS2025 and $A^{3}COSMOS$). For detailed explanations of these parameters, please refer to the paper: XXX

Details for PPM:

Castignani+2014:[https://iopscience.iop.org/article/10.1088/0004-637X/792/2/113](https://iopscience.iop.org/article/10.1088/0004-637X/792/2/113).

Details for catalog:

$A^{3}COSMOS$:[https://sites.google.com/view/a3cosmos](https://sites.google.com/view/a3cosmos);[http://vizier.cds.unistra.fr/viz-bin/VizieR?-source=J/A+A/685/A1](http://vizier.cds.unistra.fr/viz-bin/VizieR?-source=J/A+A/685/A1)

COSMOS2025:[https://cosmos2025.iap.fr/catalog.html](https://cosmos2025.iap.fr/catalog.html)

---

![PPM workflow](workflow.png)

---

## 1.SMG: $\delta$ 400_final.fits

Main parameters:

ID_1: Beacon(SMG)'s id from $A^{3}COSMOS$ catalog;

candidate_z_mean: redshift of the over-density peak $z_{ov}$;

candidate_z_rms: the overdensity redshift uncertainty $z_{rms}$;

candidate_rmax_median: the average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{ppm}$, in units of arcmin;

candidate_richness: the number of these sources is taken as the estimate of the (proto)cluster richness $N_{selected}$;

candidate_significance: the significance of the overdensity $\sigma$;

delta_z: Redshift peak offset $|z_{ov}-z_{beacon}|$;

peak_ov_density_1: the overdensity value $\delta$ of the over-density peak projected coordinates;

beacon_ov_density_1: the overdensity value $\delta$ of the SMG projected coordinates;

peak_ra_1: over-dnesity peak projected coordinates (RA[J2000] deg);

peak_dec_1: over-dnesity peak projected coordinates (Dec[J2000] deg);

R_w_arcmin_1: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin;

R_w_kpc_1: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc;

theta_w_arcmin_1: Projected positional offset between SMGs and overdensity peaks, in units of arcmin.

---

## 2.Main sequence(SFG):

### 2.1 mass match SFGs: mcombined_unique.fits

Main parameters:

ID_1: Beacon(SFG)'s id from $COSMOS2025$ catalog;

candidate_z_mean: redshift of the over-density peak $z_{ov}$;

candidate_z_rms: the overdensity redshift uncertainty $z_{rms}$;

candidate_rmax_median: the average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{ppm}$, in units of arcmin;

candidate_richness: the number of these sources is taken as the estimate of the (proto)cluster richness $N_{selected}$;

candidate_significance: the significance of the overdensity $\sigma$;

delta_z: Redshift peak offset $|z_{ov}-z_{beacon}|$;

peak_ov_density: the overdensity value $\delta$ of the over-density peak projected coordinates;

beacon_ov_density: the overdensity value $\delta$ of the SMG projected coordinates;

peak_ra: over-dnesity peak projected coordinates (RA[J2000] deg);

peak_dec: over-dnesity peak projected coordinates (Dec[J2000] deg);

R_w_arcmin: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin;

R_w_kpc: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc;

theta_w_arcmin: Projected positional offset between SMGs and overdensity peaks, in units of arcmin.

---

### 2.2 redshift match SFGs: zcombined_unique.fits

Main parameters:

ID_1: Beacon(SFG)'s id from $COSMOS2025$ catalog;

candidate_z_mean: redshift of the over-density peak $z_{ov}$;

candidate_z_rms: the overdensity redshift uncertainty $z_{rms}$;

candidate_rmax_median: the average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{ppm}$, in units of arcmin;

candidate_richness: the number of these sources is taken as the estimate of the (proto)cluster richness $N_{selected}$;

candidate_significance: the significance of the overdensity $\sigma$;

delta_z: Redshift peak offset $|z_{ov}-z_{beacon}|$;

peak_ov_density: the overdensity value $\delta$ of the over-density peak projected coordinates;

beacon_ov_density: the overdensity value $\delta$ of the SMG projected coordinates;

peak_ra: over-dnesity peak projected coordinates (RA[J2000] deg);

peak_dec: over-dnesity peak projected coordinates (Dec[J2000] deg);

R_w_arcmin: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin;

R_w_kpc: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc;

theta_w_arcmin: Projected positional offset between SMGs and overdensity peaks, in units of arcmin.

---

### 2.3 redshift match SFGs: zmcombine_unique.fits

Main parameters:

MSG_ID: Beacon(SFG)'s id from $COSMOS2025$ catalog;

candidate_z_mean: redshift of the over-density peak $z_{ov}$;

candidate_z_rms: the overdensity redshift uncertainty $z_{rms}$;

candidate_rmax_median: the average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{ppm}$, in units of arcmin;

candidate_richness: the number of these sources is taken as the estimate of the (proto)cluster richness $N_{selected}$;

candidate_significance: the significance of the overdensity $\sigma$;

delta_z: Redshift peak offset $|z_{ov}-z_{beacon}|$;

peak_ov_density: the overdensity value $\delta$ of the over-density peak projected coordinates;

beacon_ov_density: the overdensity value $\delta$ of the SMG projected coordinates;

peak_ra: over-dnesity peak projected coordinates (RA[J2000] deg);

peak_dec: over-dnesity peak projected coordinates (Dec[J2000] deg);

R_w_arcmin: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin;

R_w_kpc: the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc;

theta_w_arcmin: Projected positional offset between SMGs and overdensity peaks, in units of arcmin.

---
