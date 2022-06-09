# solas-summer-school-co2flux-practical

Practical created by: Tobias Steinhoff (NORCE, Norway (ICOS-OTC)), Ute Schuster (Univeristy of Exeter) and Marcel du Plessis (University of Gothenburg) for the *Data handling - pCO2 and carbon flux computation* practical at the SOLAS Virtual Summer School (2022), Jun 13 - 17, 2022


## SOLAS summer school, air-sea CO2 flux practical

During this practical you will (a) learn about the marine carbon cycle with specific emphasis on the atmosphere-ocean exchange of CO2 and its impacts, and then (b) work with observational data in six break-out groups. Three groups will investigate spatial variability by working with observations along a south-to-north Atlantic research vessel transect, and three groups will investigate the temporal variability by working with observations from a fixed point mooring in the North Atlantic Ocean covering nearly a whole annual cycle. 


#### The main outcomes will be:

* Understanding observed variability in surface ocean parameters like the partial pressure of CO2 (pCO2).
* Understanding the driving factors that change surface ocean properties.
* Learning to calculate CO2 flux between the ocean and the atmosphere and what drives it.


We expect you to work together as a group, which means that not everyone has to do everything. It is more important that you discuss the tasks and your findings in the group. We will jump around the groups to assist with the practical. If you have a question, don’t hesitate to call one of us. After the group work we will reconvene in the big round and discuss your findings.



## Spatial variability

** Dataset:**

We prepared a dataset from the German research vessel R/V Polarstern when it was transecting from Punta Arenas/Chile to Bremerhaven/Germany. All necessary information can be found in the presentation or at the end of this handout. The dataset contains data for the following surface ocean parameters:

* Date and Time (UTC)
* Temperature (SST, °C)    
* Salinity (SSS, PSU)
* Atmospheric pressure (mbar)
* Sea surface pCO2 (µatm)
* Atmospheric pCO2 (µatm)
* Dissolved oxygen (µmol/L)
* Oxygen saturation (%)
* Wind speed @ 10m height (m/s)

The data set is available as .csv or .txt file:

** Questions: **

### Load the dataset and plot the oceans variables against latitude

1. What spatial variability can you identify?
2. Can you think of reasons for the observed spatial variability?

3. EXTRA: You can use oxygen to get an idea about biological processes that drive the ocean’s pCO2 change. However, the absolute oxygen concentration is temperature dependent, therefore you should use the oxygen saturation. A 100% saturation means that the ocean surface oxygen is in equilibration with atmospheric oxygen. Values above 100% means that the ocean is supersatured and lower values indicate undersaturation.

### Calculate the CO2 flux between the ocean and the atmosphere using a flux parameterization of your choice (we use Nightingale (2000) in the equations below).

1. Describe your observation (what was expected, what is unexpected,...)
2. Describe the role of the delta pCO2 and wind speed on the magnitude and direction of the flux


## Temporal variability

** Dataset:**

We downloaded data from a mooring near Bermuda from SOCAT (Expocode:316420130417, Sutton et al., 2013) showing an annual cycle of surface measurements of CO2. All necessary information can be found in the presentation or at the end of this handout. The dataset contains data for the following surface ocean parameters:

* Date and Time (UTC)
* Temperature (SST, °C)    
* Salinity (SSS, PSU)
* Atmospheric pressure (mbar)
* Sea surface pCO2 (µatm)
* Atmospheric pCO2 (µatm)
* Wind speed @ 10m height (m/s)

The data set is available as .csv or .txt file.

** Questions: **

### Load the dataset and plot the oceans variables against latitude

1. What temporal variability can you identify?
2. Can you think of reasons for the observed temporal variability?


### Calculate the CO2 flux between the ocean and the atmosphere using a flux parameterization of your choice (we use Nightingale (2000) in the equations below)

1. Describe your observation (what was expected, what is unexpected,...)
2. Describe the role of the delta pCO2 and wind speed on the magnitude and direction of the flux
