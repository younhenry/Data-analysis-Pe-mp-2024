This subfolder contains the raw data in a single txt file

The file has the following columns:


*species: Bacterial species used (Pe, L. plantarum, or A. pasterianus)

*antifungal: chemical treatment used to harm bacteria (methylparaben, propionic acid, or no chemical control).
Note that methylparaben is called Nipagin in the table here, its most commonly used synonym. In the script, it is transformed back to "methylparaben".

*treatment: unused column, similar to the "antifungal" column, but grouping nipagin and propionic as a single level, vs the control

*replicate: all growth tests were performed in 3 replicated wells

*time_factor: time past since the start of the experiment before plating, as a two-levels factor

*time: time past since the start of the experiment before plating, as a numerical variable

*dil_x: unused columns in the analysis. They indicate the raw colony counts at different dillutions.
dil 1 is 20x dilution of a microplate culture well, further steps are with 20x dilution. Plating was done with 3uL droplets.

*CFU: Number of CFU per mL, calculated from the raw colony counts.