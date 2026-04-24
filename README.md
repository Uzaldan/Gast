Using tools from 
https://github.com/Kiizon/flippscrape - This will create a set of data for Walmart and Freshco specfically for my own use currently

https://github.com/FriendlyUser/flipp_flyer_parser - This will be used to parse the data that save on foods has since that is referenced in their blog and the other tool doesn't seem to collect save on's data

I plan to make a tool for collating sales over the long term from grocery stores in my area.
The goal of this is to increase the visibility of sales and also to highlight how "good" a sale actually is.


The flow of this tool is going to be: Pull data using both tools -> standardize and trim the data present so it can be used -> intake the data into a database that the tool will create and refine based on predefined categories ie. Dairy -> using historical price data (based on previous pulls)
the tool will track if the deal is better or worse -> This information will be served up as a interactive graphic that pulls images based on a google search of the item description along side an average price best price and worst price, with a cuttoff on the months tracked to avoid old data 
making the tool useless with inflation. 

This is just a first pass on the description more will be added later.
