# surfs_up

## Overview

To open a Surf n' Shake shop which will serve surfboards and ice creams to locals and tourist in Oahu, Hawaii, there is a need of investor. W. Avy is an investor who is famous for his love of surfing. But he is concerned about the weather and want to run some analytics on weather dataset.

### Purpose

The purpose of this analysis is to analyse temperature trends before opening the surf shop. Specifically, to find the temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Analysis

The date column of the Measurements table in the _hawaii.sqlite_ database is filtered to retrieve all the temperatures for the month of June and December individually. Then those temperatures are converted to list, then DataFrame is created from the list, and the summary statistics are generated for both the months individually.

## Results

### June vs December Weather Statistics

<img width="170" alt="June_Temps" src="https://user-images.githubusercontent.com/95826875/155650016-12e9642e-dfca-4efa-b19a-970f838a68c2.png"><img width="219" alt="December_Temps" src="https://user-images.githubusercontent.com/95826875/155650262-ce06f6be-af41-4f3c-abc2-28cc4845191c.png">

The key differences in weather between June and December:

- The mean recorded temperature in June is 74.9 (~75) degrees F, whereas the mean recorded temperature in December is 71 degrees F. Which suggest that June is definitely going to attract more customers than December.

- June's maximum temperature is 85 degrees F and December's maximum temperature is 83 degrees F, which does not show much of a difference concluding that the weather on Oahu is quite consistent year-around.

- The minimum temperatures has potential drop to 64 degrees F and 56 degrees F for June and December respectively, which is quite chilly in December for having ice cream. However, looking at the mean temperatures and standard deviation of 3.7, the temperatures seems to be more steady and in favor of the shop.

## Summary:

After analysing the June and December weather data, it seems that Surf & Ice Cream Shop would do well in Oahu. The weather on Oahu seems quite steady all year, therefore if the temperatures for these two months favors the Surf & Ice Cream Shop, it will do so all year. Despite the fact that temperatures in December appear to be vary, it would still provide suitable weather for both surfing and ice cream demand. But it is always better to analyse little deeper and find more supportive data. In order to do so, more queries should be performed:

### Query 1: Precipitation statistics for June

<img width="1021" alt="June Precipitation" src="https://user-images.githubusercontent.com/95826875/155657511-b5deccbe-0dfa-44c9-af3c-6ccefd1c05e5.png">

### Query 2: Precipitation statistics for December

<img width="1018" alt="December Precipitation" src="https://user-images.githubusercontent.com/95826875/155657549-a66806bc-0b77-488a-aa0f-16db2338c4ca.png">

The above two queries showing precipitation data for the month of June and December supports the idea of Surf and Ice Cream shop in Oahu. Similarly more data can be further identified to analyse the success of this investment.
