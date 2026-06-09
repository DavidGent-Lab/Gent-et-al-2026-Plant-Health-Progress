# Gent-et-al-2026-Plant-Health-Progress
Data set and associated SAS code needed to reproduce analyses from Gent et al (2026) paper in Plant Health Progress https://doi.org/10.1094/PHP-12-25-0270-BR

The data set is from three years of experiments conducted to understand how late-season fungicide applications influence suppression of powdery mildew and various hop quality measurements on the variety Nugget in Oregon.

These files are provided to enable full reproducibility of the statistical analysis presented in the paper. We make no warranties regarding these programs.

Corresponding author: David H. Gent dave.gent@usda.gov

# Files

cone_quality.csv 

--This is the data associated with hop chemistry and other quality measurements. Period sympbols indicate data was missing or not relevant. This convention is used in all of the .csv files.

cone_disease.csv

--This is the data associated with the incidence of cones with powdery mildew. 

leaf_disease.csv

--This is the data associated with the incidence of leaves with powdery mildew, including relative area under the disease progress curve (RAUDPC).

# Variable Description
Variable names in the data set and SAS program are as follows:

**cone_quality.csv**

Year: Year the experiment was conducted; ranges from 2018 to 2020.

Date: Harvest date in MM/DD/YY format.

Field: Coded field name used for each year of the experiment.

Block: Roman numeral indicate replication (block) I to VII.

Treatment: Numerical code associated with the timing of the last fungicide application. 1 is the earliest (e.g, 30 July in 2018) and 4 is latest (e.g., 1 September in 2018). 

DM: Dry matter, expressed as a percentage

_Alpha: Percent alpha-acids, expressed on a weight-by-weight basis

_Beta: Percent beta-acids, expressed on a weight-by-weight basis. This variable was not reported in the paper, but is provided because it was meassured too.

HSI: Hop storage index

Oil: total ml of oil in 100 g of cones. This variable was not reported in the paper.

Color: Cone color, recorded on a 1 to 10 scale as per Twomey et al. 2015.


**cone_disease**

Year: Year the experiment was conducted; ranges from 2018 to 2020.

Date: Harvest date in MM/DD/YY format.

Block: Roman numeral indicate replication (block) I to VII.

Treatment: Numerical code associated with the timing of the last fungicide application. 1 is the earliest (e.g, 30 July in 2018) and 4 is latest (e.g., 1 September in 2018). 

Plant: Numerical value indicating plant number, the sub-sampling factor in this study.

PM_Cones: Number of cones (out of 15) with powdery mildew.

Incidence: incidence of cones with powdery mildew expressed as a proportion.


**leaf_disease.csv**
Year: Year the experiment was conducted; ranges from 2018 to 2020.

Date: Date of leaf disease rating in in MM/DD/YY format.

SU: Sampling unit, indicated as Leaf for all observations. This factor is not used in this analysis.
 
Block: Roman numeral indicate replication (block) I to VII.

Treatment: Numerical code associated with the timing of the last fungicide application. 1 is the earliest (e.g, 30 July in 2018) and 4 is latest (e.g., 1 September in 2018). 

Plant: Numerical value indicating plant number, the sub-sampling factor in this study.

PM: Number of leaves (out of 10) with powdery mildew.

RAUDPC: Relative area under the disease progress curve. Values are entered for the first rating date each year, simply for convenience. 






