### Project Problem and Hypothesis
PROBLEM STATEMENT: Developing a budget for the purchase of a property in Brooklyn is difficult due to market changes and attributes specific to a property. How can a buyer develop a budget (predict sales price) for a specific type of property in a specific area?

HYPOTHESIS: The attributes of a property (location, size, etc.) in previous 2016 sales can predict the sales price of similar properties that go on sale in the future and inform a buyer’s budget.

The model should predict Sales Price (a continuous value) of future Brooklyn properties given a certain set of property attributes (variables).

Ideally, the model would help buyer’s develop a budget for a specific type of property that may not yet be available for sale. Address, Tax Class and Gross Square Feet are the variables that I expect will have the most impact on predicting the Sales Price.


### Datasets
I will be examining 2016 Brooklyn Rolling Sales data from the NYC open data project:
http://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page

Data Dictionary:
http://www1.nyc.gov/assets/finance/downloads/pdf/07pdf/glossary_rsf071607.pdf

### Domain knowledge
I’ve casually searched for property sales in Brooklyn in the hopes of developing a plan to purchase. I’ve observed huge variations in price based on location, size, etc., and experienced difficulty in predicted what Sales Price could be expected for a property.

My research until now has been anecdotal, but my interest/intuition may help me identify errors and bias in the data.

A google search yielded these models already exist:

Corcoran’s report:
http://media.corcoran.com/pdf/reports/2015_Q3/Brooklyn_Q32015.pdf

Compass Market app:
https://www.compass.com/research/

### Project Concerns
I’m not quite sure how to approach selecting a model that is appropriate. 

The project assumes that granular details of the property (such as interior design, state of disrepair, etc.) will be accounted for by the Tax Class.

I wish I could easily see all of the previous Sale Prices of a property. I don’t think it would provide any insight to the prediction I’m hoping my model will make, but I think it would be interesting in developing further hypotheses. 

If the model is not accurate buyers would not budget appropriately for sales and either have a surplus of funds (funds they could have invested elsewhere) or a deficiency in funds when a property with their chosen attributes becomes available.

If the model is accurate buyers can budget properly and invest their money more wisely (or however they choose).

Some of the data seems to be incorrect, or needs to be qualified in some way (there are many instances of $10 sales).

### Outcomes
I expect the output to be a dollar amount within a range (the range being the confidence interval).
I think the project can be relatively simple.
I haven’t strictly defined how the project would be a considered a success, but I expect that I will train the model and compare against some test data. If the model predicts accurately within a certain confidence interval it’s a success. Because the data is ‘rolling sales’, meaning it will be updated through the end of 2016, I can continue to train and test as more data is collected.
If the project is a bust I’ll take a look at the data to confirm there isn’t some flaw that exists there, take a look at my method for building the model to see if there’s a flaw there, and then consider the domain to consider whether there are more variables I should have collected.

