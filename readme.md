## Data Visualization

### Tableau
#### Description
Tableau is a freemium suite of data visualization tools. You can easily swap out different columns of data and try different types of visualizations for the same dataset. Using Tableau, you can also publish your visualizations (single visualizations or 'Dashboards' of multiple charts) on the web and embed them on websites.

### Dataset
Download the [Academy Award nominated movies scraped from Wikipedia](https://github.com/dmics/dataviz/blob/master/aa-movies-multicolumnstarring.csv).


## Importing Data into Tableau
Open Tableau and click **text file** on the left to connect to a csv (comma separated value) file. Select aa-movies-multicolumnstarring.csv and wait a minute for it to load.

Once it has loaded, it should appear in the bottom half of the screen. Make sure everything looks correct.

On the bottom of the screen, there will be an orange box that says "Sheet 1." Click on that to open up a worksheet that will allow you to make some visualizations.

On the left, you’ll see all of the data in the spreadsheets. “Dimensions” are columns with words in them - meaning there are different categories in each row.

“Measures” means that the columns have numbers in them - meaning you can rank, order, and size things according to the numbers.

### Runtime over time
Notice 'Runtime' is recognized as a string and listed under dimensions. We need to use it as a numbered measures, so we'll hover over Runtime, click on the small down arrow, and click Change Data Type > Number (Decimal). Then click on the arrow again and 'Convert to Measure'

Drag 'Year' into Columns

Drag 'Run Time' into Rows

Click on the lines graph chart on the right (if there isn't a listing of charts, click on 'Show Me' at the top. )

If you haven't already noticed, Tableau has automatically added together all of the runtime and is showing the sum minutes of films. That's probably not what we want. At the top, hover over Run Time, click on the down arrow, hover over Measure, and select Average.

### Winning Budgets vs Non-winning Budgets
