# PPM result for SMGs and SFG control samples.

The PPM result is comprised of 4 main files:

- `SMGs_PPM.fits`
- `mcombined_unique.fits`
- `zcombined_unique.fits`
- `zmcombined_unique.fits`

Contains 52 the most reliable overdensity candidates meet Category A&B and over 1500 sources meet Category E.

![Figure/image.png](https://github.com/chance-deng/PPM-analysis-for-COSMOS-Web-field/blob/main/Figure/image.png)

---

## 1.SMG: SMGs_PPM.fits

| No. | Header name	      | Description
| --- | ----------------- | --------------------------------------------------------- | 
| 1   | `ID_COSMOS2025`     | Beacon(SMG)'s id from COSMOS2025 catalog                        |
| 2   | `ID_A3COSMOS`       | Beacon(SMG)'s id from A<sup>3</sup>COSMOS catalog, data version 20220606 |
| 3   | `peak_ra`     | Over-dnesity peak projected coordinates (RA[J2000] deg)                        |
| 4   | `peak_dec`       | Over-dnesity peak projected coordinates (Dec[J2000] deg) |
| 5   | `candidate_z_mean`     | redshift of the over-density peak $z_{ov}$                        |
| 6   | `candidate_z_rms`       | The overdensity redshift uncertainty $z_{rms}$ |
| 7   | `candidate_rmax_median`     | The average of the maximum distances in the peak interval of this (proto)cluster is used as the estimate of its projected radius $R_{PPM}$, in units of arcmin                        |
| 8   | `candidate_richness`       | The number of these sources is taken as the estimate of the (proto)cluster richness N<sub>select</sub> |
| 9   | `candidate_significance`     | The significance of the overdensity $\sigma$                        |
| 10   | `delta_z`       | Redshift peak offset \|z<sub>ov</sub>-z<sub>beacon</sub>\| |
| 11   | `peak_ov_density`     | The overdensity value $\delta$ of the over-density peak projected coordinates                       |
| 12   | `R_w_arcmin`       | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of arcmin |
| 13   | `R_w_kpc`     | The overdensity value $\delta$ at the peak dropping to one percent of the peak value size in units of kpc                        |
| 14   | `theta_w_arcmin`       | Projected positional offset between SMGs and overdensity peaks, in units of arcmin |

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
