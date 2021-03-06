# Project4_Hydrophone
Project 4 For BME 450 Winter 2020

Code URL: https://github.com/etomlin27/Project4_Hydrophone/blob/master/Tomlin_Project4_Hydrophone.ipynb
README URL: https://github.com/etomlin27/Project4_Hydrophone/blob/master/README.md

## Problem Statement:

To understand the effect of various weather and natural phenomenon on ambient noise in the ocean envronment, it is necessary to be able to analize audio signals taken underwater. These signals area available via the Ocean Observatories Project' publically available hydrophone arrays attached to their ocean observitory platforms. Using a power spectral density versus frequency chart, the effects of weather can be visualized. Additionally, frequency spectrograms can allow a visual comparison between other sources of background noise including underwater geological activity including volcanic activity or earthquakes, marine mammal vocalizations, and airgun streamers.

## Backround/ Solution/ Results:

Graphical analysis of two observatories taken at known times of weather patterns of interest can allow some conclusions to be drawn. Figures 1a-4b show the PSD versus frequency graphs for each of the two observitory hydrophone arrays during the chosen time period. PSD was caculated using formula (1).

Equation (1):
![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/PSDEquation.JPG)

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/ShelfRain.png)

*Figure 1a: Oregon Shelf Rainy PSD Profile.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/OSRain.png)

*Figure 1b: Offshore Rainy PSD Profile.*

Examining the effect of rain on the PSD graph yields smoothing of the PSD value to around 55.

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/ShelfWind.png)

*Figure 2a: Oregon Shelf Windy PSD Profile.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/OSWInd.png)

*Figure 2b: Offshore Windy PSD Profile.*

Examining the effect of wind on the PSD graph yields a decaying waveform with PSD values averaging around 50, but with wide band spikes at cartain frequencies.

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/ShelfCalm.png)

*Figure 3a: Oregon Calm PSD Profile.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/OSCalm.png)

*Figure 3b: Offshore Calm PSD Profile.*

Using the calm days as a baseline, it can be seen that a non-weather influenced PSD graph is similar to the windy decaying waveform, but with less broad range of PSD values across the frequency spectrum.

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/ShelfStrorm.png)

*Figure 4a: Oregon Shelf Stormy PSD Profile.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/OSStorm.png)

*Figure 4b: Offshore Stormy PSD Profile.*

Stormy conditions produce the most dramatic change in the PSD as it has the smoothing effect on the curve from the rain and the broadining of the band from the wind. 

### Part 2

In understanding frequency analysis of ocean noise to gain proficiency in verifying the source of signals, it is useful to compare the spectrograms of the frequency profiles for mammal activity (figure 5), airgun noise (figure 6), and earthquakes (figure 7).

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/Mammal.png)

*Figure 5: Marine Mammal Frequency Spectrogram.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/Airgun.png)

*Figure 6: Airgun Frequency Spectrogram.*

![alt text](https://github.com/etomlin27/Project4_Hydrophone/blob/master/Quake.png)

*Figure 7: Geologic Frequency Spectrogram.*

Consistant with the Wentz curve, we can see that the eartquake activity is very low frequency, in the <120 Hz range, Airguns are in the middle with a pulsing profile, and Mammal has the widest spread.

## Conclusion:

It is important to have multiple sites of data to determine the effect of weather on the PSD profile to elimitna possible local factors that may interfere with results. Proximity to shipping lanes, bouys, general water depth, and marine mammal communities may all effect the results. By comparing two different sites, conclusions can be drawn by comparing the change at each for the different weather conditions. Rain has the most noticeable effet on the PSD whith its flattening of the curve.

## References:

https://ooinet.oceanobservatories.org/
https://www.noaa.gov/
https://water.usgs.gov/edu/activity-howmuchrain-metric.html
https://stackoverflow.com/
