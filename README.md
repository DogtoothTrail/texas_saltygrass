# texas_saltygrass

## general information
This repository houses data depicting the nutritive and growth responses to salinity in four Texas grasses. The dataset corresponds to the article *Soil salinity has species-specific effects on the growth and nutrient quality of four Texas grasses* by Bell and Smith in *Rangeland Ecology and Management*. [link to article to be added following publication]

## authors
Abigail Bell (arbell2009@gmail.com) and Nick Smith (nick.gregory.smith@gmail.com)

## DOI badge

## folder descriptions
### /data
This folder contains all the data files from the experiment.

## file descriptions
### /data/cn_data.csv
This file contains data from Carbon/Nitrogen elemental analysis. The specific column information is:

- *sample_id*: a unique name for identifying each sample. Nomenclature for a sample id structured as species.block.treatment.organ
- *sample_weight*: weight of a sample (mg)
- *nitrogen_weight*: weight of a sample’s total nitrogen (mg) detected by the analyzer
- *nitrogen_percent*: percent nitrogen in sample (% or [mgN/mgSample])
- *carbon_weight*: weight of a sample’s total carbon (mg) detected by the analyzer
- *carbon_percent*: percent carbon in sample (% or [mgC/mgSample])
- *species*: initials of the common names for the four grass species studied. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *block*: identification number for one of the six replicate blocks the sample was harvested from
- *treatment*: concentration of salinity treatment sample was grown under (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
- *organ*: organ of the grass sample analyzed, either shoots (S) or roots (R)


### /data/germination_data.csv
This file contains the data on species germination. The specific column information is: 

- *species*: initials of the common names for the four grass species studied. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *treatment*: concentration of salinity treatment sample was grown under (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
- *germination*: indication if seed in a single well of tray germinated. 1 = germination, 0 = no germination

### /data/mass_data.csv
This folder contains the data on sample mass. The specific column information is: 
- *pot*: a unique name for identifying each sample. Nomenclature for a sample id structured as species.block.treatment.organ
- *mass*: mass of a sample (g)
- *organ*: organ of the grass sample harvested, either shoots (S) or roots (R)
- number_of_plants: number of surviving plants harvested and weighed from a single sample pot
- *species*: initials of the common names for the four grass species studied. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *block*: identification number for one of the six replicate blocks the sample was harvested from
- *treatment*: concentration of salinity treatment sample was grown under (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
