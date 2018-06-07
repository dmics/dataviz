## Data Visualization

### Tableau
#### Description
Tableau is a freemium suite of data visualization tools. You can easily swap out different columns of data and try different types of visualizations for the same dataset. Using Tableau, you can also publish your visualizations (single visualizations or 'Dashboards' of multiple charts) on the web and embed them on websites.

### Dataset
TKTKTKTK include dl link

#### Scenario
TKTKTKT

## Importing Data into Tableau
Open Tableau and click **text file** on the left to connect to a csv (comma separated value) file. Select `TKTKTKTKT` and wait a minute for it to load.

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





- genres overall
- relationships between genres
- compare winner & non-winner budgets
- compare genres nominated over time



###
* Click on ‘Sheet 1’ in the bottom left corner of the screen.

On the left, you’ll see all of the data in the spreadsheets. “Dimensions” are columns with words in them - meaning there are different categories in each row.

“Measures” means that the columns have numbers in them - meaning you can rank, order, and size things according to the numbers.

* Click on “Principal Place of Slave Purchase” (under dimensions) and drag it up to the ‘Columns’ space at the top of the screen.

* Click on ‘Total Slaves Disembarked’ (under measures) and drag it up to the ‘Rows’ space at the top of the screen.

This will give you a bar chart showing the total number of enslaved people who embarked from each place. We can get more detail though, so lets try another visualization.

* In the top right corner of the screen, click ‘Show Me’ to show all of the possible visualizations. Each visualization requires different things (for example, at least one dimension and one measure, or a date and a measure), so some are grayed out.

* Click on ‘treemaps’ (on the left in the fourth row down) to create a new visualization that sizes boxes according to the total number of disembarked people in each place. If we’re interested in where these enslaved people were headed, we can investigate that as well.

* Click on ‘Principal Region of Slave Landing’ and drag it into the ‘Detail’ box within the larger ‘Marks’ box, which is between the data sidebar and the main screen.

We now have two levels of information - we can see the large segments that show how many people were taken from each East African place, and each small box within shows where those people were taken.

**What are you able to see in this?**

#### Adding Final Details

* Change the colors: Add ‘Principal Place of Slave Purchase’ again and drag it into the ‘Color’ box (which is located in the ‘Marks’ box)
* Add landing the labels: Add ‘Principal Region of Slave Landing’ agan and drag it into the ‘Label’ box

### See the number of enslaved people taken from East Africa over time.

There's a small box in the bottom left with a bar chart and a + symbol. Click that to create a new visualization.

* Click on “Total Slaves Embarked” (under measures) and drag it up to the ‘Rows’ space at the top of the screen.

* Click on ‘Total Slaves Disembarked’ (under measures) and drag it up to the ‘Rows’ space at the top of the screen.

* Click on the 'abc' icon to the left of “Date of Departure” (under dimensions) and select ‘Change Data Type’ and then select ‘Date’. Drag ‘Date of Departure’ to the ‘Columns’ space at the top of the screen.

* In the top right corner of the screen, click ‘Show Me’ and then select ‘lines (continuous)’. This will give you two line charts, one for ‘Total Slaves Embarked’ and one for ‘Total Slaves Disembarked.’ While these two charts are usable on their own, we want to merge the two together to create a single visualization.

* Click and hold on the upper left corner of the bottom line chart. You will notice as you move your mouse pointer into the leftmost field the box is highlighted. The mouse pointer should change to the ‘move arrow’ icon. Drag the bottom chart directly into the same leftmost field box as the top chart to merge them together.

This will give you a line chart showing the total number of enslaved people who embarked and the number that ultimately disembarked.

**What are you able to see in this?**


### Where are enslaved people from particular places being taken?

* Open a new sheet using the button in the bottom left of the screen

* Click on “Principal Place of Slave Purchase” (under dimensions) and drag it up to the ‘Columns’ space at the top of the screen.

* Click on “Principal Place of Slave Landing” (under dimensions) and drag it up to the ‘Columns’ space at the top of the screen.

* Click on “Total Slaves Disembarked” (under measures) and drag it up to the ‘Rows’ space at the top of the screen.

This will give you a bar chart showing the total number of enslaved people who embarked from each place. This is a large amount of information, so let’s try to focus in on one region to get more detail.

* Hover over ‘Principal Place of Slave Purchase’ and then click the triangle to bring up a dropdown menu and select ‘Filter’. Click ‘None’ to clear the fields and select ‘Mozambique’. This will narrow the visualization to just Mozambique as the principal place of purchase. Go back to ‘Principal Place of Slave Purchase’ and select the dropdown menu again. Select ‘Filter’ and add ‘Quillmane’. This will create two bar charts, one for Mozambique and one for Quillmane.

To make the visualization easier to work with, the bar chart can be sorted in ascending or descending order using the toolbar at the top of the book.

* There are options to sort the graph just to the left of the center of the top toolbar. Click the sort descending icon (there's an arrow pointing down with the larger bars at the top of the graph).

#### Adding Final Details

Additional information can be added to your chart without pulling more fields into the main body.

* Select ‘Slave Deaths During Middle Passage’ and drag it to the ‘Tooltip’ box under ‘Marks’. Now hover over any of the bars in the chart. You can see there are now four levels of information, our three original fields and ‘Slave Deaths during Middle Passage’.

## Analyzing and Sharing
Take a moment and chat with your partner:
What are you able to see from your chart? Did it look about the way you expected? Were there any surprises? Sharing your vizualizations

To share:

1. Go to *File > Save to Tableau Public As...* and save the file under the name you'd like. This may require you to sign in with a (free) Tableau Public account.
1. This will open a web browser window to your chart on the Tableau website. At the bottom, you'll see a *Share* button that will give you shareable links.

-----
### Return to [LEADR's Resources list](https://leadr-msu.github.io/)
