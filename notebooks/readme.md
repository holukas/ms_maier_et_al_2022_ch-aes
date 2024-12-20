**Processing Overview**
**===================**

Date: 9 Dec 2021
Script version: 'v7'

This folder combines all results from 20211130 with new results. Results from 20211130 remain unchanged.

Gap-filled fluxes:
- N2O: use 2019.B.9 and 2020.B.9 from QCF0_drivers
- CH4: use XXX and XXX from QCF01_gapfilling_CH4

---

# QCF0_drivers
- contains driver analysis based on fluxes where quality flag QCF = 0 (best quality fluxes only)


## Drivers: NEWLY ADDED in this run
- XXXX.B.10 runs, with maximum number of variables (all available variables included except 'PA')


## Drivers: General Process
- XXXX.B.1 ... most minimal variable set
- XXXX.B.2 ...  + adds more directly measured meteo variables
- XXXX.B.3 ...  + adds rolling variants
- XXXX.B.4 ...  + adds lagged variants
- XXXX.B.5 ...  + adds 'veg.height'
- XXXX.B.6 ...  + adds management 'bulk' and its 'timesince'
- XXXX.B.7 ...  + adds timestamp features (info from the timestamp as separate columns e.g. DOY)
- XXXX.B.8 ...  ~ changes management to 'all', with separate 'timesince' variables for each management (each management type is included as boolean feature: 0 or 1)
- XXXX.B.9 ...  + adds 'lai'; + adds 'PREC' and its rolling and lagged variants
- XXXX.B.9 `allFeatures` ... data file that contains all features used  **NEWLY ADDED** (for NEE)
- XXXX.B.10 ... + 'TA', 'RH', 'Rg', 'VPD', and their rolling and lagged variants  <-- this is the maximum number of variables  **NEWLY ADDED** (for N2O and CH4 fluxes only)
- XXXX.B.10 `allFeatures` ... data file that contains all features used  **NEWLY ADDED**  (for N2O and CH4)

The files with the suffix `allFeatures` contains all available features, including rolling and lagged variants.
- For NEE, `B.9` already contained all features.
- For N2O and CH4, `B.10` contained all features. In their `B.9` some features were not included, e.g. 'TA' and 'RH'.

## QCF0_drivers: N2O
### 2019
- 2019.B.1 ... most minimal variable set, includes 'WFPS_0.05', 'TS_0.05' and the 'daynight' flag
- 2019.B.2 ... all of the above, + 'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2019.B.3 ... all of the above, + rolling variants
- 2019.B.4 ... all of the above, + lagged variants
- 2019.B.5 ... all of the above, + 'veg.height'
- 2019.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2019.B.7 ... all of the above, + timestamp features
- 2019.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2019.B.9 ... all of the above, + 'lai', + 'PREC' and its rolling and lagged variants
- 2019.B.10 ... all of the above, + 'TA', 'RH', 'Rg', 'VPD', and their rolling and lagged variants  **NEWLY ADDED**
### 2020
- 2020.B.1 ... most minimal variable set, includes 'WFPS_0.05', 'TS_0.05' and the 'daynight' flag
- 2020.B.2 ... all of the above, + 'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2020.B.3 ... all of the above, + rolling variants
- 2020.B.4 ... all of the above, + lagged variants
- 2020.B.5 ... all of the above, + 'veg.height'
- 2020.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2020.B.7 ... all of the above, + timestamp features
- 2020.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2020.B.9 ... all of the above, + 'lai', + 'PREC' and its rolling and lagged variants
- 2020.B.10 ... all of the above, + 'TA', 'RH', 'Rg', 'VPD', and their rolling and lagged variants  **NEWLY ADDED**


## QCF0_drivers: CH4
### 2019
- 2019.B.1 ... most minimal variable set, includes 'WFPS_0.05', 'TS_0.05' and the 'daynight' flag
- 2019.B.2 ... all of the above, + 'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2019.B.3 ... all of the above, + rolling variants
- 2019.B.4 ... all of the above, + lagged variants
- 2019.B.5 ... all of the above, + 'veg.height'
- 2019.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2019.B.7 ... all of the above, + timestamp features
- 2019.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2019.B.9 ... all of the above, + 'lai', + 'PREC' and its rolling and lagged variants
- 2019.B.10 ... all of the above, + 'TA', 'RH', 'Rg', 'VPD', and their rolling and lagged variants  **NEWLY ADDED**
### 2020
- 2020.B.1 ... most minimal variable set, includes 'WFPS_0.05', 'TS_0.05' and the 'daynight' flag
- 2020.B.2 ... all of the above, + 'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2020.B.3 ... all of the above, + rolling variants
- 2020.B.4 ... all of the above, + lagged variants
- 2020.B.5 ... all of the above, + 'veg.height'
- 2020.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2020.B.7 ... all of the above, + timestamp features
- 2020.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2020.B.9 ... all of the above, + 'lai', + 'PREC' and its rolling and lagged variants
- 2020.B.10 ... all of the above, + 'TA', 'RH', 'Rg', 'VPD', and their rolling and lagged variants  **NEWLY ADDED**


## QCF0_drivers: NEE
### 2019
- 2019.B.1 ... most minimal variable set, includes 'Rg', 'TA', 'VPD' and the 'daynight' flag
- 2019.B.2 ... all of the above, + 'TS', + 'WFPS', + 'PA', + 'RH', + 'PREC'
- 2019.B.3 ... all of the above, + rolling variants
- 2019.B.4 ... all of the above, + lagged variants
- 2019.B.5 ... all of the above, + 'veg.height'
- 2019.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2019.B.7 ... all of the above, + timestamp features
- 2019.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2019.B.9 ... all of the above, + 'lai'
### 2020
- 2020.B.1 ... most minimal variable set, includes 'Rg', 'TA', 'VPD' and the 'daynight' flag
- 2020.B.2 ... all of the above, + 'TS', + 'WFPS', + 'PA', + 'RH', + 'PREC'
- 2020.B.3 ... all of the above, + rolling variants
- 2020.B.4 ... all of the above, + lagged variants
- 2019.B.5 ... all of the above, + 'veg.height'
- 2019.B.6 ... all of the above, + management 'bulk', + timesince management 'bulk' 
- 2019.B.7 ... all of the above, + timestamp features
- 2019.B.8 ... all of the above, ~ changed management to 'all', + timesince for each management (each management type as boolean feature)
- 2019.B.9 ... all of the above, + 'lai'


---

# QCF01_gapfilling_sameVarsAsMDS
- This is the gap-filling comparison: RF vs MDS
- RF used the same fluxes as MDS, fluxes where QCF = 0 or QCF = 1
- **both methods used the same data basis and variables**, i.e. there is no additional despiking in RF etc...

## Used Variables:
- 2019.C.1 ... 
    - N2O: used 'TS_0.05', 'WFPS_0.05' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**
    - CH4: used 'TS_0.05', 'WFPS_0.05' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**
    - NEE: used 'Rg', 'TA' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**
- 2020.C.1 ... 
    - N2O: used 'TS_0.05', 'WFPS_0.05' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**
    - CH4: used 'TS_0.05', 'WFPS_0.05' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**
    - NEE: used 'Rg', 'TA' and 'VPD' (no rolling or lagged variants)  **NEWLY ADDED**

---

# QCF01_gapfilling_N2O_CH4
- gapfilling for N2O and CH4, using fluxes where QCF = 0/1
- using QCF = 0 has not enough measured values for "reliable" gap-filling

- 2019.G.1 ... uses same vars as 2019.B.6 **NEWLY ADDED**
- 2020.G.1 ... uses same vars as 2020.B.6 **NEWLY ADDED**
