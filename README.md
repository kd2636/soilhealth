# soilhealth

There are various portal related to agriculture for providing solutions to problem of farmers, but there are generalized solutions given to them mostly. Also, sometimes apps are dealing with one or two components of farming only. So we are trying to integrate all these components int one and give detailed and scheduled solutions to farmers, integrating packages of practices. In this application real time info will be given to farmers from feild preparation to their predicted yield.

Provide analysis like sowing rate, spacing, fertlizers to be used to farmers on basis of soil health card.
Risk management, giving message to famers when floo or cyclone is about to hit.
Giving suggestions to farmers for plating best crop and their variety and intercrops and variety.
Giving farmers yield prediction and profit prediction using random forest model fitting.
The present Apps only give generalized option about crops and farmers but our app gives targeted ressult to farmers analysing their Soil Health Card and predicting their yield per hectare if they follow our suggestion.

Simply speaking our app leverages Soil Health Card information for farmers. The Soil Health card, issued by Govt. of India does not have much useful for information that farmers can directly use. Our app uses SH info and provides info like Variety, inter-crop, seed spacing and sowing period. Using these info we predict the yield and predicted profit to farmer using random forest model. We also provide real time prediction of cyclone and flood to farmers.


Soil Health Card is prepared by agricultural scientist under Soil Health Card scheme of Govt. of India. It contains information like the variety of crops and intercrop that can be grown on a farmers land based on its agro-climatic region and value of N,P,K ratio of farmer's land. This info is pretty rudimentary considering farmer's view.

So our App's aim is to use this SHC infomation and make it directly useful to farmers. Based on SHC data we provide info like variety of crops, intercrop and their sowing period. We also provide info of land prepration, fertilizer to be used, spacing between crops and rate of sowing seed. Thesee information and nation wide standars based on the agro climatic region where the farm is. The USP of our app is yield prediction and cyclone and flood forecasting.



server.js -- server file
public folder, error.html, -- static file with index.html and error page repectively
View folder -- User template
yield.R -- random forest yield prediction
data.csv -- data used for yield prediction, based on agro climatic region of west Gujarat
flood-cyclone.py -- script for scraping wesite for flood and cyclone forecast
