# Vancouver-Housing-price-prediction
Using multivariable linear regression, this analysis aims to predict Vancouver housing prices ranging from 2019 to early 2020 based on one sample data set.

This analysis aims to predict Vancouver housing prices with related factors ranging from 2019 to early 2020 based on one sample data set. So that the realtors could have an overview of the real estate market in Vancouver, and sellers and potential buyers would receive proper information to make a wise decision.
 
To make the prediction, we adopt a statistical methodology – multivariable linear regression – to combine different factors together and make sure the accuracy of our prediction. The data we use is collected from Vancouver homes with sale prices of at most 3 million CAD from 2019 to early 2020, before any impacts of the pandemic. As is shown in Mortgage Sandbox $^{1}$, the housing price from 2019 to early 2020 is relatively stable. Therefore, our prediction can eliminate the time series effect based on such a data set because the housing price data we have in the early stage will not have big differences from the data in the later stage. In the given data, we split 1042 data as a training set and set the rest as a testing set. We choose four variables – days on the market, total floor area, age of the house, and lot size – as our candidate variables.
 
There are some benefits of making this prediction. As is shown in ApartmentBlocks’s 2019 report $^{2}$, there is one policy recession in the real estate market in Vancouver from 2018 to 2019, which may cause buyers and sellers to lose confidence in the market. Therefore, the predicting model is so important that sellers in Vancouver could have a clearer sense of setting reasonable prices, to gain greater success, and potential buyers can also expect a price range for their specific conditions when purchasing houses.

Reference:
1. 	Mortgage Sandbox. (2019). Metro Vancouver. *Real Estate Trends and Price Forecast*. https://www.mortgagesandbox.com/vancouver-real-estate-forecast.
2. 	ApartmentBlocks. (2019). *Metro Vancouver's First Ever Policy-Induced Housing Recession*. https://www.apartmentblocks.ca/aptb-wp/wp-content/uploads/2019/12/Report_ApartmentBlocksYearEnd_2019_web.pdf
