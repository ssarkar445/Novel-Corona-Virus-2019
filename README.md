# Novel-Corona-Virus-2019
EDA for Novel Corona Virus 2019
Context
From World Health Organization - On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China. The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people.

So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community.

Johns Hopkins University has made an excellent dashboard using the affected cases data. This data is extracted from the same link and made available in csv format.

Content
2019 Novel Coronavirus (2019-nCoV) is a virus (more specifically, a coronavirus) identified as the cause of an outbreak of respiratory illness first detected in Wuhan, China. Early on, many of the patients in the outbreak in Wuhan, China reportedly had some link to a large seafood and animal market, suggesting animal-to-person spread. However, a growing number of patients reportedly have not had exposure to animal markets, indicating person-to-person spread is occurring. At this time, it’s unclear how easily or sustainably this virus is spreading between people - CDC

This dataset has daily level information on the number of affected cases, deaths and recovery from 2019 novel coronavirus. Please note that this is a time series data and so the number of cases on any given day is the cumulative number.

The data is available from 22 Jan, 2020.

Column Description
2019ncovdata.csv

Sno - Serial number
Date - Date and time of the observation in MM/DD/YYYY HH:MM:SS
Province / State - Province or state of the observation (Could be empty when missing)
Country - Country of observation
Last Update - Time in UTC at which the row is updated for the given province or country. (Not standardised currently. So please clean them before using it)
Confirmed - Number of confirmed cases
Deaths - Number of deaths
Recovered - Number of recovered cases
Acknowledgements
Johns Hopkins university has made the data available in google sheets format here. Sincere thanks to them.

Thanks to WHO, CDC, NHC and DXY for making the data available in first place.

Picture courtesy : Johns Hopkins University dashboard

Inspiration
Some insights could be

Changes in number of affected cases over time
Change in cases over time at country level
Latest number of affected cases
