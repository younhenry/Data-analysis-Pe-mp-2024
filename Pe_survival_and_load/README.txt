This subfolder contains 3 raw data tables in txt files

######################################
"data_plating" file
######################################

*ID: unique identifyier corresponding to a single vial

*nipagin: presence or absence of methlyparaben (here called Nipagin)

*pathogen: infection with Pe or sham infection with sterile surcrose

*OD600: Optical Density of the bacterial suspension used for infections. Here, it is written as a numerical variable.

*OD600_factor: Optical Density of the bacterial suspension used for infections. Here, it is written as categorical factor.

*vial_change: indicates whether flies were daily changed to a new vial, or whether they stayed in the same vial fore the entire duration of experiment

*replicate: Unused column with a, b, or c values. Similarly to the "ID" column, it corresponds to a single replicate vial within a given combination of nipagin x pathogen x OD600 x vial_change treatments.

*time: time past since the start of the experiment before plating, as a numerical variable

*dilution_x: unused columns in the analysis. They indicate the raw colony counts at different dillutions.
2 flies collected at 24, 96 and 188h, externally washed with EtOH 70%, crushed in 400uL of 1:1 LB glycerol mix, diluted twice, and 10uL plated in fist dilution. Further dilutions are 20x step dilutions.

*CFU_per_fly: Number of CFU per fly, calculated from the raw colony counts.


######################################
"data_survival" file
######################################

*ID: unique identifyier corresponding to a single vial

*nipagin: presence or absence of methlyparaben (here called Nipagin)

*pathogen: infection with Pe or sham infection with sterile surcrose

*OD600: Optical Density of the bacterial suspension used for infections. Here, it is written as a numerical variable.

*OD600_factor: Optical Density of the bacterial suspension used for infections. Here, it is written as categorical factor.

*vial_change: indicates whether flies were daily changed to a new vial, or whether they stayed in the same vial fore the entire duration of experiment

*replicate: Unused column with a, b, or c values. Similarly to the "ID" column, it corresponds to a single replicate vial within a given combination of nipagin x pathogen x OD600 x vial_change treatments.

*time: time past since the start of the experiment before plating, as a numerical variable

*dead_flies: total number of dead flies since the start of the experiement

*alive_flies: total number of remaining alive flies

*total_flies: total number of flies at the start of the experiment

*events: number of death events at a given timepoint


######################################
"data_offspring" file
######################################

*nipagin: presence or absence of methlyparaben (here called Nipagin)

*pathogen: infection with Pe or sham infection with sterile surcrose

*OD600: Optical Density of the bacterial suspension used for infections. Here, it is written as a numerical variable.

*OD600_factor: Optical Density of the bacterial suspension used for infections. Here, it is written as categorical factor.

*change: indicates the day at which the vial was used by flies. "1" means this is the first fresh vial after the infection (so from 24h to 48h post infection), "2" means the second vial (from 48h to 72h post infection) etc..

*vials_with_dead_larvae: number of vials with more than 5 dead larvae

*more_than_5_pupae:  number of vials with more than 5 dead larvae

*total_vials:  total number of vials (at a given timepoint for a given combination of treatment)