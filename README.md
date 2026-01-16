# PPM-analysis-for-COSMOS-Web-field

---

We use a sample of 449 SMGs from the $A^3COSMOS$ catalog and control samples of main-sequence star-forming galaxies (SFGs) from COSMOS2025 in the COSMOS-Web JWST field, we apply the Poisson Probability Method (PPM, [Castignani+2014](https://iopscience.iop.org/article/10.1088/0004-637X/792/2/113)) to identify overdensity structures. We upload here the results of PPM analysis performed on all samples (based on COSMOS2025 and A3COSMOS). For detailed explanations of these parameters, please refer to the paper: XXX

Details for catalog:

[A3COSMOS](https://sites.google.com/view/a3cosmos); [Data version 20220606](http://vizier.cds.unistra.fr/viz-bin/VizieR?-source=J/A+A/685/A1)

[COSMOS2025](https://cosmos2025.iap.fr/catalog.html)

---
# PPM Workflow.

For detailed steps, please refer to the paper: XXX

![PPM workflow](workflow.png)

---

# PPM result for SMGs and SFG control samples.

The PPM result is comprised of 4 main files:

- `SMGs_PPM.fits`
- `mcombined_unique.fits`
- `zcombined_unique.fits`
- `zmcombined_unique.fits`

Contain over 1500 overdensity candidates meet Category E.

![Figure/image.png](https://github.com/chance-deng/PPM-analysis-for-COSMOS-Web-field/blob/main/Figure/image.png)

## 1.SMG: SMGs_PPM.fits

| No. | Header name	      | Description
| --- | ----------------- | --------------------------------------------------------- | 
| 1   | ID_COSMOS2025     | Beacon(SMG)'s id from $A^{3}COSMOS$ catalog                        |
| 2   | ID_A3COSMOS       | Beacon(SMG)'s id from $A^{3}COSMOS$ catalog, data version 20220606 |
| 3   | peak_ra     | over-dnesity peak projected coordinates (RA[J2000] deg)                        |
| 4   | peak_dec       | over-dnesity peak projected coordinates (Dec[J2000] deg) |
| 5   | candidate_z_mean     | redshift of the over-density peak $z_{ov}$                        |
| 6   | candidate_z_rms       | the overdensity redshift uncertainty $z_{rms}$ |
| 7   | candidate_rmax_median     | the average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin                        |
| 8   | candidate_richness       | the number of these sources is taken as the estimate of the (proto)cluster richness $N_{select}$ |
| 9   | candidate_significance     | Beacon(SMG)'s id from $A^{3}COSMOS$ catalog                        |
| 10   | delta_z       | Redshift peak offset |$z<sub>ov</sub>-z<sub>beacon</sub>$| |
| 11   | peak_ov_density     | the overdensity value $\delta$ of the over-density peak projected coordinates                       |
| 12   | R_w_arcmin       | the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 13   | R_w_kpc     | the overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc                        |
| 14   | theta_w_arcmin       | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |

---

## 2.Main sequence(SFG):

### 2.1 mass match SFGs: mcombined_unique.fits

Main parameters:

ID_COSMOS2025: Beacon(SFG)'s id from $COSMOS2025$ catalog;

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

ID_COSMOS2025: Beacon(SFG)'s id from $COSMOS2025$ catalog;

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

ID_COSMOS2025: Beacon(SFG)'s id from $COSMOS2025$ catalog;

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

## JWST RGB cut image

We provide two sets of cropped James Webb Space Telescope (JWST) images for each overdensity candidate, both centered on the central coordinates of the candidate, with fields of view (FOV) of 10 arcmin and 10 arcsec, respectively.
