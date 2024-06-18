This subfolder contains 2 raw data tables in txt files

######################################
"data_plating_transmission" file
######################################
*ID: unique identifyier corresponding to a single vial

*infection: infection with Pe or sham infection with sterile surcrose

*food: indicates the food used by flies. T2 is the name of our standard food as described in the article, but without methylparaben (-mp diet)

*replicate: Unused column with 1-10 values. Similarly to the "ID" column, it corresponds to a single replicate vial, but within a given "infection" level.

*time: time past since the start of the experiment before plating, as a numerical variable

*dilution_x: unused columns in the analysis. They indicate the raw colony counts at different dillutions.
a single fly was crushed in 400uL of a 1:1 mix of 50% glycerol and PBS (all sterile), serial dilution by x20 steps, plating of 5uL of each dilution on Pseudomonas isolation agar

*CFU_per_fly: Number of CFU per fly, calculated from the raw colony counts.

*alive_flies: total number of remaining alive flies (same data as in the "data_survival_transmission" file)

*total_flies: total number of flies at the start of the experiment (same data as in the "data_survival_transmission" file)


######################################
"data_survival_transmission" file
######################################

ID	infection	food	replicate	time	dead_flies	alive_flies	total_flies	pupae	mold

*ID: unique identifyier corresponding to a single vial

*infection: infection with Pe or sham infection with sterile surcrose

*food: indicates the food used by flies. T2 is the name of our standard food as described in the article, but without methylparaben (-mp diet)

*replicate: Unused column with 1-10 values. Similarly to the "ID" column, it corresponds to a single replicate vial, but within a given "infection" level.

*time: time past since the start of the experiment before plating, as a numerical variable

*dead_flies: total number of dead flies since the start of the experiement

*alive_flies: total number of remaining alive flies

*total_flies: total number of flies at the start of the experiment