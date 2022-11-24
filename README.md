# Documentation for the repository sporeprod

Supplement to the paper by Norros, Halme, Norberg and Ovaskainen: Spore production monitoring reveals contrasting seasonal strategies and a trade-off between spore size and number in wood-inhabiting fungi.


This repository contains the following files:

samples.xls – data table of spore production samples

days.xls – data table of sampling days

trunks.xls – data table of trunk (a.k.a. log) variables

species.xls – data table of species traits

spore_production_HCM.nb – commented Mathematica notebook for performing the parameter estimation for the hierarchical community model described in the paper

HCM_parameter_estimates.xls – table of posterior quantiles and support probability levels for estimated parameters


Notes on the data tables:

The table samples.xls includes also samples obtained from fruit bodies not identified to species level. These are filtered out of the data in the Mathematica script based on the column “incl?”.

Sunrise and sunset times were obtained for the city of Jyväskylä 23 km from the study site; “Jkl” refers to Jyväskylä in the names of these data columns in days.xls.

Tree species are given in Finnish in trunks.xls. Translation: kuusi = Norway spruce (Picea abies), mänty = Scotch pine (Pinus sylvestris), koivu = birch (Betula pendula or Betula pubescens), haapa = aspen (Populus tremula).

In species.xls, the column “Log vol” gives the log-transformed spore volume (fl) for each species. 
