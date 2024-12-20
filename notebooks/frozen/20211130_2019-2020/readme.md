# Processing Overview


Date: 30 Nov 2021
Script version: 'v7'

**Note: All used measured fluxes are with quality flag QCF = 0 (best) and ustar-filtered**

Gap-filled N2O and CH4: XXX_2019.B.9, XXX_2020.B.9


## Changes to previous run
- files from this run have the identifier `B` in filename
- this run should have a better (more understandable) sequence of added variables
- correct enddate for 2019
- no rolling variants for 'lai' and 'veg.height'
- no lagged variants for 'lai' and 'veg.height'


## General Process
- XXXX.B.1 ... most minimal variable set
- XXXX.B.2 ... + adds more directly measured meteo variables
- XXXX.B.3 ... + adds rolling variants
- XXXX.B.4 ... + adds lagged variants
- XXXX.B.5 ... + adds 'veg.height'
- XXXX.B.6 ... + adds management 'bulk' and its 'timesince'
- XXXX.B.7 ... + adds timestamp features (info from the timestamp as separate columns e.g. DOY)
- XXXX.B.8 ... ~ changes management to 'all', with separate 'timesince' variables for each management (each management type is included as boolean feature: 0 or 1)
- XXXX.B.9 ... + adds 'lai'; + adds 'PREC' and its rolling and lagged variants  <-- this is the maximum number of variables


## N2O
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


## CH4
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


## NEE
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
