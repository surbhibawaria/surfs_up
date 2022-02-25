# surfs_up

## Overview

To open a Surf n' Shake shop serving surfboards and ice creams to locals and tourist in Oahu, Hawaii, there is a need of investor backing. W. Avy is an investor who is famous for his love of surfing. But he is concerned about the weather and want to run some analytics on weather dataset.

### Purpose

The purpose of this analysis is to analyse temperature trends before opening the surf shop. Specifically, to find the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Analysis

The date column of the Measurements table in the hawaii.sqlite database is filtered to retrieve all the temperatures for the month of June and December individually. Then those temperatures are converted to list, then DataFrame is created from the list, and the summary statistics are generated for both the months individually.

## Results

The three key differences in weather between June and December:

### June Weather Statistics

<img width="170" alt="June_Temps" src="https://user-images.githubusercontent.com/95826875/155650016-12e9642e-dfca-4efa-b19a-970f838a68c2.png">


### December Weather Statistics

<img width="219" alt="December_Temps" src="https://user-images.githubusercontent.com/95826875/155650054-480bfd11-e294-4176-97d9-c4c851229bb5.png">



## Summary:

