This repository contains data and code needed to perform the analyses and figures in our manuscript:

"Pseudomonas entomophila is highly pathogenic to fruit flies in the absence of methylparaben" (by Youn Henry, Jaime González, Christine La Mandola, Tadeusz J. Kawecki)

####################################
General info
####################################

*analyses are separated into three folders, with one script each.
	-One folder is dedicated to the analysis of in vitro growth of bacteria in the presence of antifungal or not
	-A second folder is dedicated to the analysis of survival, Pe load and offspring survival
	-A thrid folder is dedicated to the analysis of indirect transmission of Pe through the environement

*data in .txt format are in the `data` folder, R script in Rmd format (including notes with some information about the analysis) in the `R` folder.

*The R code uses the `here` package (see also [here](https://github.com/jennybc/here_here)). This means all file paths are relative, and the analysis should work on your computer no questions asked, whether you use the R project or not, no code line to change as long as you download the entire repo.

*If you run the script for the first time, time-consuming outputs like models will be saved in the same folder as the script so you don't have to re-run them everytime.

*If you don't need to run the code but simply look at it and its outputs, a knitted html document allows to visualize that without running anything.
