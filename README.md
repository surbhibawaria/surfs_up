# surfs_up

## Overview

To open a Surf n' Shake shop serving surfboards and ice creams to locals and tourist in Oahu, Hawaii, there is a need of investor backing. W. Avy is an investor who is famous for his love of surfing. But he is concerned about the weather and want to run some analytics on weather dataset.

### Purpose

The purpose of this analysis is to analyse temperature trends before opening the surf shop. Specifically, to find the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Analysis

The date column of the Measurements table in the _hawaii.sqlite_ database is filtered to retrieve all the temperatures for the month of June and December individually. Then those temperatures are converted to list, then DataFrame is created from the list, and the summary statistics are generated for both the months individually.

## Results

### June vs December Weather Statistics

<img width="170" alt="June_Temps" src="https://user-images.githubusercontent.com/95826875/155650016-12e9642e-dfca-4efa-b19a-970f838a68c2.png"><img width="219" alt="December_Temps" src="https://user-images.githubusercontent.com/95826875/155650262-ce06f6be-af41-4f3c-abc2-28cc4845191c.png">

The key differences in weather between June and December:

- The mean recorded temperature in June is 74.9 (~75) degrees F, whereas the mean recorded temperature in December is 71 degrees F. Which suggest that June is definitely going to attract more customers.
- 
- June's maximum temperature is 85 degrees F and December's maximum temperature is 83 degrees F, which does not show much of a difference concluding that the weather on Oahu is quite consistent year-around.

- The minimum temperatures has potential drop to 64 degrees F and 56 degrees F for June and December respectively, which is quite chilly. However, looking at the mean temperatures and standard deviation of 3.2 and 3.4 the temperatures seems to be more steady.

## Summary:


