# PPM result for SMGs and SFG control samples.

The PPM result is comprised of 2 main files:

- `274unique_SMG_assocwith_ovcandidates.fits`
- `3005unique_SFG_assocwith_ovcandidates.fits`

Contains 54 the most reliable overdensity candidates meet Category A&B and over 3000 sources meet Category E.

![Figure/image.png](https://github.com/chance-deng/PPM-analysis-for-COSMOS-Web-field/blob/main/Figure/image.png)

---

### SMG PPM catalog: `274unique_SMG_assocwith_ovcandidates.fits`

| Column | Description |
| --- | --- |
| `ID` | SMG beacon identifier. |
| `zfinal` | Final redshift in the matched SMG catalog; the value `-99` denotes an unavailable value. |
| `RAdeg`, `DEdeg` | SMG beacon right ascension and declination (J2000, deg). |
| `z` | Redshift used for the SMG beacon in the PPM association. |
| `z_ov`, `ez_ov` | Overdensity-peak redshift and its redshift uncertainty. |
| `sig_ov` | Overdensity significance. |
| `Nselected` | Number of selected sources, used as an estimate of the (proto)cluster richness. |
| `R_PPM_arcmin` | PPM projected-radius estimate (arcmin). |
| `R_w_arcmin`, `R_w_kpc` | Radius where the overdensity falls to 1% of its peak value (arcmin and kpc). |
| `peak_ra`, `peak_dec` | Projected overdensity-peak position (J2000, deg). |
| `theta_w_arcmin` | Projected offset between the SMG and overdensity peak (arcmin). |
| `peak_ov_density` | Overdensity value at the projected peak position. |
| `flux_850` | 850-um flux density of the SMG. |
| `Separation` | Angular separation of matched catalog objects (arcsec). |

### SFG-control PPM catalog: `3005unique_SFG_assocwith_ovcandidates.fits`

| Column | Description |
| --- | --- |
| `id` | SFG beacon identifier from COSMOS2025. |
| `ra`, `dec` | SFG beacon right ascension and declination (J2000, deg). |
| `z` | SFG beacon redshift. |
| `peak_ra`, `peak_dec` | Projected overdensity-peak position (J2000, deg). |
| `R_w_arcmin`, `R_w_kpc` | Radius where the overdensity falls to 1% of its peak value (arcmin and kpc). |
| `theta_w_arcmin` | Projected offset between the SFG and overdensity peak (arcmin). |
| `R_PPM_arcmin` | PPM projected-radius estimate (arcmin). |
| `peak_ov_density`, `beacon_ov_density` | Overdensity values at the peak and beacon positions. |
| `candidate_z_mean`, `candidate_z_rms` | Candidate overdensity redshift and redshift uncertainty. |
| `candidate_rmax_median` | Median maximum radius across the candidate peak interval (arcmin). |
| `candidate_richness` | Number of selected sources, used as a richness estimate. |
| `candidate_significance` | Overdensity significance. |
| `delta_z` | Absolute redshift difference between the candidate peak and beacon. |
| `Separation` | Angular separation of matched catalog objects (arcsec). |
