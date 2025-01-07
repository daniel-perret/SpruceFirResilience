# Data files

This folder contains three data files derived from publicly-available FIA data and climate data from ClimateNA (Wang et al. 2016). These contain all data used to train the mortality, regeneration, and recruitment models presented in the main manuscript. All data fields and variable names are described below.

### Mortality data (*mortdat.csv*)

*TRE_CN* -- unique tree identifier

*SPCD* -- species code (19 = subalpine fir; 93 = Engelmann spruce)

*SURV* -- survival status (0 = died, 1 = survived)

*PLT_CN* -- unique plot identifier

*ECOSUBCD* -- Level IV ecoregion subsection code

*PREVDIA* -- Tree diameter (cm DBH) at initial measurement

*PREV_CR* -- Tree crown ratio at initial measurement

*prev.damage* -- binary code indicating whether tree was damaged at initial measurement (0 = undamaged, 1 = damaged)

*PREV_BAH* -- stand density at initial measurement, measured as basal area per hectare

*area.fire.prop* -- proportion of spruce-fir forest area in ecoregion subsection that experienced fire-related mortality. See main manuscript text for further explanation.

*area.id.prop* -- proportion of spruce-fir forest area in ecoregion subsection that experienced fire-related mortality. See main manuscript text for further explanation.

*MAT_maxanom** -- maximum mean annual temperature anomaly experienced during remeasurement period relative to reference conditions. "z" indicates conversion to a z-score.

*CMD_maxanom** -- maximum mean climatic moisture deficit anomaly experienced during remeasurement period relative to reference conditions. "z" indicates conversion to a z-score.

*MAT_ref_mean* -- average mean annual temperature during reference period (30 years prior to initial measurement)

*CMD_ref_mean* -- average mean climatic moisture deficit during reference period (30 years prior to initial measurement)

*REMPER* -- years between remeasurements.

*mult.comp.coexist* -- joint trajectory estimated at the ecoregion subsection level between 2000-2009 and 2010-2019 FIA inventories. See main text for further explanation.


### Regeneration and recruitment data (*seeddat.csv* and *sapdat.csv*)

*PLT_CN* -- unique plot identifier

*SPCD* -- species code (19 = subalpine fir; 93 = Engelmann spruce)

*SEED.PRES* / *SAP.PRES* -- binary code indicating seedling or sapling presence or absence (0 = absence, 1 = presence)

*fire.sev* -- proportion of trees live at time 1 killed by fire at remeasurement

*PREV_BAH* -- stand density at initial measurement, measured as basal area per hectare

*ECOSUBCD* -- Level IV ecoregion subsection code

*MAT_maxanom** -- maximum mean annual temperature anomaly experienced during remeasurement period relative to reference conditions. "z" indicates conversion to a z-score.

*CMD_maxanom** -- maximum mean climatic moisture deficit anomaly experienced during remeasurement period relative to reference conditions. "z" indicates conversion to a z-score.

*MAT_ref_mean* -- average mean annual temperature during reference period (30 years prior to initial measurement)

*CMD_ref_mean* -- average mean climatic moisture deficit during reference period (30 years prior to initial measurement)
















