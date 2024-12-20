# Processing Overview


Date: 29 Nov 2021 (changes to previous run: corrected WFPS)
Script version: 'v6'

Gap-filled N2O and CH4: 2019.7, 2020.7


## General Process
- XXXX.1 ... minimal variable set
- XXXX.2 ... + 'bulk' management and timesince 'bulk' management
- XXXX.3 ... + additional meteo data
- XXXX.4 ... + vegetation height and LAI
- XXXX.5 ... + timestamp features, + rolling variants
- XXXX.6 ... + lagged variants
- XXXX.7 ... changing management: each management type is included as its own feature (option 'all' instead of 'bulk') and their timesince variants


## NEE
### 2019
- 2019.1 ... minimal variable set, includes 'Rg', 'TA', 'VPD' and the 'daynight' flag
- 2019.2 ... all of the above, +management 'bulk', +timesince management 'bulk'
- 2019.3 ... all of the above, +'RH', 'PA', 'PREC', 'TS_0.05', 'TS_0.15', 'TS_0.30', 'WFPS_0.05', 'WFPS_0.15', 'WFPS_0.30', +timesince 'PREC'
- 2019.4 ... all of the above, +'veg.height', 'lai'
- 2019.5 ... all of the above, +timestamp features, +rolling variants
- 2019.6 ... all of the above, +lagged variants
- 2019.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)
### 2020
- 2020.1 ... minimal variable set, includes 'Rg', 'TA', 'VPD' and the 'daynight' flag
- 2020.2 ... all of the above, +management 'bulk', +timesince management 'bulk'
- 2020.3 ... all of the above, +'RH', 'PA', 'PREC', 'TS_0.05', 'TS_0.15', 'TS_0.30', 'WFPS_0.05', 'WFPS_0.15', 'WFPS_0.30', +timesince 'PREC'
- 2020.4 ... all of the above, +'veg.height', 'lai'
- 2020.5 ... all of the above, +timestamp features, +rolling variants
- 2020.6 ... all of the above, +lagged variants
- 2020.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)


## N2O
### 2019
- 2019.1 ... minimal variable set, includes 'WFPS_0.05', 'TS_0.05', 'PREC' and the 'daynight' flag
- 2019.2 ... all of the above, +management 'bulk', +timesince management 'bulk', +timesince 'PREC'
- 2019.3 ... all of the above, +'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2019.4 ... all of the above, +'veg.height', 'lai'
- 2019.5 ... all of the above, +timestamp features, +rolling variants
- 2019.6 ... all of the above, +lagged variants
- 2019.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)
### 2020
- 2020.1 ... minimal variable set, includes 'WFPS_0.05', 'TS_0.05', 'PREC' and the 'daynight' flag
- 2020.2 ... all of the above, +management 'bulk', +timesince management 'bulk', +timesince 'PREC'
- 2020.3 ... all of the above, +'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2020.4 ... all of the above, +'veg.height', 'lai'
- 2020.5 ... all of the above, +timestamp features, +rolling variants
- 2020.6 ... all of the above, +lagged variants
- 2020.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)


## CH4
### 2019
- 2019.1 ... minimal variable set, includes 'WFPS_0.05', 'TS_0.05', 'PREC' and the 'daynight' flag
- 2019.2 ... all of the above, +management 'bulk', +timesince management 'bulk', +timesince 'PREC'
- 2019.3 ... all of the above, +'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2019.4 ... all of the above, +'veg.height', 'lai'
- 2019.5 ... all of the above, +timestamp features, +rolling variants
- 2019.6 ... all of the above, +lagged variants
- 2019.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)
### 2020
- 2020.1 ... minimal variable set, includes 'WFPS_0.05', 'TS_0.05', 'PREC' and the 'daynight' flag
- 2020.2 ... all of the above, +management 'bulk', +timesince management 'bulk', +timesince 'PREC'
- 2020.3 ... all of the above, +'TS_0.15', 'TS_0.30', 'WFPS_0.15', 'WFPS_0.30'
- 2020.4 ... all of the above, +'veg.height', 'lai'
- 2020.5 ... all of the above, +timestamp features, +rolling variants
- 2020.6 ... all of the above, +lagged variants
- 2020.7 ... - bulk management and its timesince, + all management and its timesince (each management type as boolean feature)

