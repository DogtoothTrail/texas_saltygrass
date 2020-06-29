# texas_saltygrass

## general information
This repository houses data depicting the nutritive and growth responses to salinity in four Texas grasses. The dataset corresponds to the article *Soil salinity has species-specific effects on the growth and nutrient quality of four Texas grasses* by Bell and Smith in *Rangeland Ecology and Management*. [link to article to be added following publication]

## authors
Abigail Bell (arbell2009@gmail.com) and Nick Smith (nick.gregory.smith@gmail.com)

## DOI badge

## folder descriptions:
### /data
This folder contains all the data files from the experiment.

## file descriptions:
### /data/cn_data.csv
This file contains sample data gathered from elemental analysis. The specific column information is:

- *sample_id*: The abbreviated name created for identifying each sample analyzed. Nomenclature for a sample id is structured as species.block.treatment.organ
- *sample_weight*: The weight of a sample (in milligrams) that was analyzed. 
- *nitrogen_weight*: The weight of a sample’s total nitrogen (in milligrams) detected by the analyzer.
- *nitrogen_percent*: The percentage of nitrogen in a single sample calculated by dividing the sample’s nitrogen_weight by the same sample’s sample_weight
- *carbon_weight*: The weight of a sample’s total carbon (in milligrams) detected by the analyzer
- *carbon_percent*: The percentage of carbon in a single sample calculated by dividing the sample’s carbon_weight by the same sample’s sample_weight
- *species*: The initials of the common names of the four grass species used in this experiment. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *block*: The identification number of the replicate block the sample was harvested from. There were a total of six replicate blocks used in this experiment
- *treatment*: The concentration of the salinity treatment that the sample was grown under (in dS/m). Can be one of four treatments (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
- *organ*: The organ of the grass sample analyzed, observed as either shoots (S) or roots (R)


### /data/germination_data.csv
This file contains the data on species germination. The specific column information is: 

- *species*: The initials of the common names of the four grass species used in this experiment. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *treatment*: The concentration of the salinity treatment that the sample was germinated under (in dS/m). Can be one of four treatments (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
- *germination*: An indication of if the seed planted in a single well of the germination tray germinated. 1 = germination, 0 = no germination

### /data/mass_data.csv
This folder contains the data on sample mass. The specific column information is: 
- *pot*: The abbreviated name identifying the pot from which each sample was harvested and weighed. Nomenclature for a sample id is structured as species.block.treatment.organ
- *mass*: The total mass of a sample (in grams)
- *organ*: The organ of the grass sample harvested, observed as either shoots (S) or roots (R)
- number_of_plants: The number of surviving plants harvested and weighed from a single sample pot
- *species*: The initials of the common names of the four grass species used in this experiment. LB = Little bluestem, SG = Sideoats grama, BG = Blue grama, and BM = Bermudagrass
- *block*: The identification number of the replicate block the sample was harvested from. There were a total of six replicate blocks used in this experiment
- *treatment*: The concentration of the salinity treatment that the sample was grown under (in dS/m). Can be one of four treatments (0 dS/m, 8 dS/m, 16 dS/m, or 24 dS/m)
