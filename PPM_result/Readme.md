# PPM result for SMGs and SFG control samples.

The PPM result is comprised of 2 main files:

- `274unique_SMG_assocwith_ovcandidates.fits`
- `3005unique_SFG_assocwith_ovcandidates.fits`

Contains 54 the most reliable overdensity candidates meet Category A&B and over 3000 sources meet Category E.

![Figure/image.png](https://github.com/chance-deng/PPM-analysis-for-COSMOS-Web-field/blob/main/Figure/image.png)

---

## 1.SMG: 274unique_SMG_assocwith_ovcandidates.fits

| No. | Header Name | Description |
| :-- | :---------- | :---------- |
| 1 | `ID` | Beacon(SMG)'s id from COSMOS2025 catalog |
| 2 | `RAdeg` | Right Ascension of the beacon(SMG) source (J2000, degrees) |
| 3 | `DEdeg` | Declination of the beacon(SMG) source (J2000, degrees) |
| 4 | `z` | Redshift of the beacon(SMG) source |
| 5 | `z_ov` | Redshift of the over-density peak $z_{ov}$ |
| 6 | `ez_ov` | The overdensity redshift uncertainty $z_{rms}$ |
| 7 | `sig_ov` | The significance of the overdensity $\sigma$ |
| 8 | `Nselected` | The number of these sources is taken as the estimate of the (proto)cluster richness $N_{select}$ |
| 9 | `R_PPM_arcmin` | The average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin |
| 10 | `R_w_arcmin` | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 11 | `R_w_kpc` | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc |
| 12 | `peak_ra` | Over-density peak projected coordinates (RA[J2000] deg) |
| 13 | `peak_dec` | Over-density peak projected coordinates (Dec[J2000] deg) |
| 14 | `theta_w_arcmin` | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |
| 15 | `peak_ov_density` | The overdensity value $\delta$ of the over-density peak projected coordinates |
| 16 | `flux_850` | Flux density at 850 $\mu$m |

---

## 2.Main sequence(SFG):

### 2.1 mass match SFGs: mcombined_unique.fits

| No. | Header name	      | Description
| --- | ----------------- | --------------------------------------------------------- | 
| 1   | `ID_COSMOS2025`     | Beacon(SFG)'s id from COSMOS2025 catalog                        |
| 2   | `peak_ra`     | Over-dnesity peak projected coordinates (RA[J2000] deg)                        |
| 3   | `peak_dec`       | Over-dnesity peak projected coordinates (Dec[J2000] deg) |
| 4   | `candidate_z_mean`     | redshift of the over-density peak $z_{ov}$                        |
| 5   | `candidate_z_rms`       | The overdensity redshift uncertainty $z_{rms}$ |
| 6   | `candidate_rmax_median`     | The average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin                        |
| 7   | `candidate_richness`       | The number of these sources is taken as the estimate of the (proto)cluster richness N<sub>select</sub> |
| 8   | `candidate_significance`     | The significance of the overdensity $\sigma$                        |
| 9   | `delta_z`       | Redshift peak offset \|z<sub>ov</sub>-z<sub>beacon</sub>\| |
| 10   | `peak_ov_density`     | The overdensity value $\delta$ of the over-density peak projected coordinates                       |
| 11   | `beacon_ov_density`     | The overdensity value $\delta$ of the SMG projected coordinates                        |
| 12   | `R_w_arcmin`       | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 13   | `R_w_kpc`     | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc                        |
| 14   | `theta_w_arcmin`       | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |

---

### 2.2 redshift match SFGs: zcombined_unique.fits


| No. | Header name	      | Description
| --- | ----------------- | --------------------------------------------------------- | 
| 1   | `ID_COSMOS2025`     | Beacon(SFG)'s id from COSMOS2025 catalog                        |
| 2   | `peak_ra`     | Over-dnesity peak projected coordinates (RA[J2000] deg)                        |
| 3   | `peak_dec`       | Over-dnesity peak projected coordinates (Dec[J2000] deg) |
| 4   | `candidate_z_mean`     | redshift of the over-density peak $z_{ov}$                        |
| 5   | `candidate_z_rms`       | The overdensity redshift uncertainty $z_{rms}$ |
| 6   | `candidate_rmax_median`     | The average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin                        |
| 7   | `candidate_richness`       | The number of these sources is taken as the estimate of the (proto)cluster richness N<sub>select</sub> |
| 8   | `candidate_significance`     | The significance of the overdensity $\sigma$                        |
| 9   | `delta_z`       | Redshift peak offset \|z<sub>ov</sub>-z<sub>beacon</sub>\| |
| 10   | `peak_ov_density`     | The overdensity value $\delta$ of the over-density peak projected coordinates                       |
| 11   | `beacon_ov_density`     | The overdensity value $\delta$ of the SMG projected coordinates                        |
| 12   | `R_w_arcmin`       | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 13   | `R_w_kpc`     | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc                        |
| 14   | `theta_w_arcmin`       | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |

---

### 2.3 redshift match SFGs: zmcombine_unique.fits

| No. | Header name	      | Description
| --- | ----------------- | --------------------------------------------------------- | 
| 1   | `ID_COSMOS2025`     | Beacon(SFG)'s id from COSMOS2025 catalog                        |
| 2   | `peak_ra`     | Over-dnesity peak projected coordinates (RA[J2000] deg)                        |
| 3   | `peak_dec`       | Over-dnesity peak projected coordinates (Dec[J2000] deg) |
| 4   | `candidate_z_mean`     | redshift of the over-density peak $z_{ov}$                        |
| 5   | `candidate_z_rms`       | The overdensity redshift uncertainty $z_{rms}$ |
| 6   | `candidate_rmax_median`     | The average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin                        |
| 7   | `candidate_richness`       | The number of these sources is taken as the estimate of the (proto)cluster richness N<sub>select</sub> |
| 8   | `candidate_significance`     | The significance of the overdensity $\sigma$                        |
| 9   | `delta_z`       | Redshift peak offset \|z<sub>ov</sub>-z<sub>beacon</sub>\| |
| 10   | `peak_ov_density`     | The overdensity value $\delta$ of the over-density peak projected coordinates                       |
| 11   | `beacon_ov_density`     | The overdensity value $\delta$ of the SMG projected coordinates                        |
| 12   | `R_w_arcmin`       | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 13   | `R_w_kpc`     | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc                        |
| 14   | `theta_w_arcmin`       | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |

---
