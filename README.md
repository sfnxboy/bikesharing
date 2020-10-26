# bikesharing

For this project, we'll use data from the Citi Bike program in New York City. This data includes a variety of fields, which we'll get to shortly. The data you'll download will be contained in a flat file, a CSV. Go to the Citi Bike System Data page (https://www.citibikenyc.com/system-data). In the "Citi Bike Trip Histories" section, click the link that say "downloadable diles for Citi Bike trip data."

In Tableau, you have a variety of different options when it comes to data sources.You can have flat files such as CSV, PDF, and TXT files, as well as other data sources like databases and data streams. (These will mostly be SQL databases.)
There are two primary ways that Tableau connects to the data you provide: through live data or extract data. Both have their benefits and uses, so let's dive a little deeper into each.
Live data is primarily databases such as MySQL and Microsoft SQL Server. Live data is just what it sounds like: live data. This type of data is updated every time you view the dashboard, since it's possible that the data has changed in your database.
Extract data is primarily when you use files such as CSV, TXT, or PDF. These files remain unchanged unless you pull a new extract of the data. For example, if you update the file, you would have to update it in Tableau as well.
For our analysis, we'll import the CSV file, which contains all the data we'll need for this project. Therefore, we'll technically be working with extract data for our project.

### Tableau Formats

In Tableau, there are three primary formats you need to be familiar with: worksheets, dashboards, and stories.

Worksheets are the building blocks of our visualizations from which we are able to create dashboards and stories. A worksheet is made up of a single graph or plot, which we will learn how to create later on. Worksheets are customizable, but require almost no actual code.

You may have seen a visualization dashboard before, whether in Tableau, PowerBI, or a number of other popular tools. In Tableau, dashboards are a collection of worksheets formatted to present data in a way that is easy to read. There are many things you can do with Tableau dashboards, which we'll discuss later.

Tableau stories are simply Tableau dashboards that include narration of what is occuring with the data. We'll dive deeper into stories later, but for now you should know that they are extremely helpful for identifying important analytic points.

When creating Tableau stories, or data visualizations in general, there's a general process that should be followed. You can use this process for most visualizations you'll create.

1. Select your questions. During this step, you'll consider which results you want to share with your audience. What do they want to see? How can we use that information to make their decision making process easier?

2. Execute independent research. You'll need to look at other relevant pieces of information to build a bigger picture. Search other sources to find information that will make your visualization more powerful.

3. Craft your Tableau story. This is when you create your story, primarily from worksheets and other visuals, with descriptions for each of them.

4. Create a written analysis. The written analysis is intended to provide additional insight into what we're trying to convey to our audience. This is a good place to add extra detail so that everyone can get on the same page.
