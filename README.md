# PestManagement
The primary aim of this project is to develop a spread model for predicting the distribution and abundance of mammalian pests across the landscape, the ways in which animals move from their natal sites, and the effects of control intervention. In particular, the model can help managers to asses the chances of success of a management action. It also allows exploring some of the mechanisms by which mammal populations might recover after control operations. 

The project aims and objectives, the methods and results, and the discussion are presented in our paper entitled 'Pest control at a regional scale: identifying key criteria using a spatially explicit, agent-based model', Journal of Applied Ecology (In Review). Lustig A., James A., Anderson D. and Plank M. 

A key contribution of this work is the integration of a more sophisticated representation of species-habitat interactions into a generic model of spread to create dynamic maps showing future population trajectories. The model describes the behavior of individual mammals located explicitly in a map of their habitat. Key events in an individual’s lifetime comprise birth, death, and dispersal, and these are simulated as stochastic, i.e. there is uncertainty in the timing of each event. Such modeling provides detailed forecasts of mammal abundance at regular time intervals into the future. Data are colour-coded so that areas of high and low mammal density are easily distinguished. The approach developed is based on combining generic mathematical modeling frameworks with spatial information on habitat distribution, population dynamics and actual levels of control. Therefore the approach could be applied to a variety of medium size mammalian pests. In addition, the model allows exploration of how the distribution and abundance of mammals can be affected by control interventions by landholders. Important roles for this type of model are to help predict hotspots of mammalian pest activities, to suggest the most effective control strategy, and to identify important parameters and data for improving predictions. 

As a case study, we used the common brushtail possum (Trichosurus vulpecula) population across a geographically large treatment area in Te Matau a Māui/Hawke’s Bay, New Zealand. The predator management effort in this area is coordinated by Cape-to-City programme, a multi-agency initiative that aims to evaluate the economic and ecological consequences of large-scale, low-cost predator control in rural and peri-urban landscape (capetocity.co.nz). The programme involves controlling possums, as well as other mammalian pests, across 26,000 ha of predominantly private land in the Hawke’s Bay region. 

We investigated the effectiveness of different spatial and temporal distributions of trapping effort in the treatment area and highlighted  important findings for assessing the effectiveness of a pest control operation. First, there are striking differences in the effectiveness of different spatial control strategies - a well designed spatial control strategy could be up to twice as cost effective as poorly designed ones. Second, the optimal spatial strategy may depend on the total control effort. Third, for some species, e.g. the brushtail possum which has a predominantly annual reproductive strategy and relatively constant capture probability over time, control timing has only a minimal effect. Five, immigration rather than in situ breeding is likely to initiate the population recovery in treated areas after an initial knockdown. Therefore, increasing the size of treatment areas and maximizing the use of natural barriers to immigration could prolong treatment persistence. 

The data/code presented here include:
 - 2019_02_mainModel.py : python source code of the agent-based population dynamics module, which simulates pest dynamics (reproduction, dispersal and natural mortality) within a raster grid and the python source code of the module giving the probability of an animal being caught at a particular location with a given local trap density.
 - Habitat_suitability : python source code of diverse functions used to read, reformat raster grid cells. 
 - Data : simulated data that can be used as an example 
