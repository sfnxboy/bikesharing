# bikesharing

For this project, we'll use data from the Citi Bike program in New York City. This data includes a variety of fields, which we'll get to shortly. The data you'll download will be contained in a flat file, a CSV. Go to the Citi Bike System Data page (https://www.citibikenyc.com/system-data). In the "Citi Bike Trip Histories" section, click the link that say "downloadable diles for Citi Bike trip data."

In Tableau, you have a variety of different options when it comes to data sources.You can have flat files such as CSV, PDF, and TXT files, as well as other data sources like databases and data streams. (These will mostly be SQL databases.)
There are two primary ways that Tableau connects to the data you provide: through live data or extract data. Both have their benefits and uses, so let's dive a little deeper into each.
Live data is primarily databases such as MySQL and Microsoft SQL Server. Live data is just what it sounds like: live data. This type of data is updated every time you view the dashboard, since it's possible that the data has changed in your database.
Extract data is primarily when you use files such as CSV, TXT, or PDF. These files remain unchanged unless you pull a new extract of the data. For example, if you update the file, you would have to update it in Tableau as well.
For our analysis, we'll import the CSV file, which contains all the data we'll need for this project. Therefore, we'll technically be working with extract data for our project.
