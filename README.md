# R-IPIP50
Quickly implement and score IPIP-50 with Qualtrics and R

## What is IPIP-50?
IPIP stands for International Personality Item Pool. More specifically, the personality scale we will be working with is the [50-item IPIP representation of the Goldberg (1992) markers for the Big-Five factor structure](https://ipip.ori.org/New_IPIP-50-item-scale.htm), IPIP-50 in short. It is designed to evaluate personality on the Big 5 domains of Extraversion, Agreeableness, Conscientiousness, Emotional Stability, and Intellect/Imagination. 

## What does this repository contain?
The repo contains a .qsf file which can be imported to Qualtrics as a survey. The survey contains only one question: a matrix table with all 50 items of the IPIP-50, presented as it is on its website. It also contains an R markdown notebook, which will be used to perform the actual scoring and analysis. 

## How should I use the files?
The matrix table can be saved to your own question library for use in other surveys. The R markdown file can be used directly with data exported from Qualtrics (in .csv format; change the string in `read_csv()`to reflect the filename of the .csv that contains said exported data). 

## References 
Goldberg, L. R. (1992). The development of markers for the Big-Five factor structure. *Psychological Assessment*, 4, 26-42.
