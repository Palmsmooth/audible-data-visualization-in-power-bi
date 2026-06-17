# Create Visualization
## Step 1: Create a Slicer (Filter Control) to Filter Data by The Author Field
- Go to the Visualization tab > Select the Slicer icon

<img src="image\Select the Slicer icon.png" width="100%" height="40%">

- Drag Book Author into the Field section

<img src="image\Drag Book Author into the Field section.png" width="100%" height="40%">

- Next, three icons will appear on the visual. Click the ellipsis (…), then click ‘Search’ to enable the Search option

<img src="image\click ‘Search’ to enable the Search option.png" width="100%" height="40%">

- Type ‘Rowling’ > Check ‘J.K. Rowling’ to filter the entire page to only J.K. Rowling’s data

<img src="image\Type ‘Rowling’.png" width="100%" height="40%">

---

## Step 2: Create a Visual Component to Display The Bookshelf Data
- Go to the Visualization tab > Click the Chiclet Slicer button

<img src="image\Select the Slicer icon in The Bookshelf.png" width="100%" height="40%">

- Go to the Field tab at the bottom right of the screen

<img src="image\Go to the Field tab at the bottom right of the screen.png" width="100%" height="40%">

- Drag Book_ID into the Category field > Drag Book Cover URL into the Image field

<img src="image\Drag Book_ID into the Category field.png" width="100%" height="40%">
<img src="image\Display Book_ID.png" width="100%" height="40%">
<img src="image\Drag Book Cover URL into the Image field.png" width="100%" height="40%">
<img src="image\Display Book_ID and image_url.png" width="100%" height="40%">

- In the Format tab (next to the Field tab) > General > Change Columns to 6

<img src="image\Change Columns to 6.png" width="100%" height="40%">


- Scroll down to the Image section > Change Image Split to 90 (you may need to adjust the number to see which works best with your Image URL)

<img src="image\Change Image Split to 90.png" width="100%" height="40%">

---

## Step 3: Create a Visual Component to Display Transactions by Country
- Go to the Visualization tab > Select the Maps button

<img src="image\Select the Maps button.png" width="100%" height="40%">

- In the Field tab > Drag Country into the Location field > Drag Book_ID into the Size field (Power BI will automatically aggregate it as Count of Book_ID)

<img src="image\Drag Country into the Location field.png" width="100%" height="40%">
<img src="image\Display Country.png" width="100%" height="40%">
<img src="image\Drag Book_ID into the Size field.png" width="100%" height="40%">
<img src="image\Power BI will automatically aggregate it as Count of Book_ID.png" width="100%" height="40%">

- In the Format tab > Go to Data Colors > Click the button under Default color > Set the lowest value to yellow and the highest value to purple

<img src="image\Go to Data Colors.png" width="100%" height="40%">
<img src="image\Click the button under Default color.png" width="100%" height="40%">
<img src="image\Set the lowest value to yellow and the highest value to purple.png" width="100%" height="40%">
<img src="image\Display Map.png" width="100%" height="40%">

---

## Step 4: Create a Visual Component to Display Sales Information
- Go to the Visualization Tab > Select the Matrix button

<img src="image\Select the Matrix button.png" width="100%" height="40%">

- Drag the Book Title column into the Rows field

<img src="image\Drag the Book Title column into the Rows field.png" width="100%" height="40%">
<img src="image\Display the Book Title..png" width="100%" height="40%">

- Drag THBPrice into the Values field twice (Microsoft Power BI will automatically aggregate it as the Sum of THBPrice)

<img src="image\Drag THBPrice into the Values field.png" width="100%" height="40%">
<img src="image\DisplayTHBPrice.png" width="100%" height="40%">
<img src="image\Drag THBPrice into the Values field twice.png" width="100%" height="40%">


- Then change one of the THBPrice columns to display as a percentage

<img src="image\THBPrice.png" width="100%" height="40%">


- Click the drop-down arrow icon > Show value as > Percent of grand total

<img src="image\change one of the THBPrice columns.png" width="100%" height="40%">
<img src="image\Percent of grand total.png" width="100%" height="40%">

- Go to the Format Tab > Conditional Formatting > Turn on Data Bar > Advanced Controls > Positive Bar > Change the color to green

- Then convert this visual back to a Table so that we can use Tooltip when hovering over the Book

---

## Step 5: Create a Tooltip for The Sales Information Visual to Display Detailed Book Information and Sales Trends
- Tooltip Page Configuration
    - Click the + at the bottom tab to create a Tooltip Page
    <img src="image\Click the + at the bottom tab to create a Tooltip Page.png" width="100%" height="40%">

    - Click on the blank canvas in the center > Go to the Format Tab on the right > Page Information > 1) Rename the Page > 2) Turn on the Tooltip button
    <img src="image\Turn on the Tooltip button.png" width="100%" height="40%">
    <img src="image\Tooltip button.png" width="100%" height="40%">

    - In the Format Tab > Page Size > Type: Tooltip
    <img src="image\Type Tooltip.png" width="100%" height="40%">

    - Click the View Tab at the top > Page View > Actual Size
    <img src="image\Actual Size.png" width="100%" height="40%">

- Create Visualization for tooltip: Rating, Book Narrator
    - Go to the Visualization Tab > Select the Card button
    <img src="image\Select the Card button.png" width="100%" height="40%">

    - Drag the Rating column into the Fields area > Click the small drop-down arrow > Change the Aggregation to Average
    <img src="image\Drag the Rating column into the Fields area.png" width="100%" height="40%">
    <img src="image\Change the Aggregation to Average.png" width="100%" height="40%">
    
    - Go to the Format Tab > Data label > Set Text size to 20
    <img src="image\Go to the Format Tab and Data label.png" width="100%" height="40%">
    <img src="image\Set Text size to 20.png" width="100%" height="40%">

    - To rename the field, double-click the field name 
    <img src="image\To rename the field, double-click the field name.png" width="100%" height="40%">

    - Copy the existing Card visual, then replace it with Book Narrator
    <img src="image\then replace it with Book Narrator.png" width="100%" height="40%">
    <img src="image\First.png" width="100%" height="40%">
    <img src="image\rename Book Narrator.png" width="100%" height="40%">

- Create Visualization for tooltip: Books Sold Trend
    - Go to the Visualization Tab > Select the Line Chart button
    <img src="image\Go to the Visualization Tab and Select the Line Chart button.png" width="100%" height="40%">

    - Drag MonthName into the Axis field > Add Book Title to the Legend field > Drag Book_ID into the Values field (Count of Book_ID)
    <img src="image\Drag MonthName into the Axis field.png" width="100%" height="40%">
    <img src="image\Drag Book_ID into the Values field (Count of Book_ID).png" width="100%" height="40%">
    <img src="image\Add Book Title to the Legend field.png" width="100%" height="40%">
    <img src="image\rename Count of book to Books Sold.png" width="100%" height="40%">

    - Click on the blank Canvas, then turn off Keep all filters so the Tooltip will only appear when hovering over the Book Title
    <img src="image\Click on the blank Canvas, then turn off Keep all filters so the Tooltip will only appear when hovering over the Book Title.png" width="100%" height="40%">

    - Drag Book Title into the field below Keep all filters
    <img src="image\Drag Book Title into the field below Keep all filters.png" width="100%" height="40%">

    - Rename Page2 to Tooltip2
    <img src="image\rename Page2 to tooltip2.png" width="100%" height="40%">

- Apply the Tooltip to the Sales Information Table
    - Go back to the main page > Click on the Table Visual
    <img src="image\Go back to the main page, Click on the Table Visual.png" width="100%" height="40%">
    
    - Go to the Format Tab > Turn on the Tooltip section > Type: Report Page > Page: Select the name of the tooltip page you created

---

## Step 6: Create a Visual Component to Display The Top 5 Best-Selling Books
- Go to the Visualization Tab > Select the Multi-row card button

<img src="image\Go to the Visualization Tab and Select the Multi-row card button.png" width="100%" height="40%">

- Drag Book Title, Book ID, and THBPrice into the Fields area.
Change the Aggregation of Book ID to Count of Book ID.
(THBPrice will automatically be aggregated as Sum.)

<img src="image\Drag Book Title.png" width="100%" height="40%">
<img src="image\Drag Book ID.png" width="100%" height="40%">
<img src="image\Change the Aggregation of Book ID to Count of Book ID.png" width="100%" height="40%">
<img src="image\Drag THBPrice.png" width="100%" height="40%">

- Go to the Filter Tab (on the left of the Visualization Tab) > Click on the Book Title filter > Filter Type: Top N > Show items: 5 > By Value: Book ID

<img src="image\Show items 5.png" width="100%" height="40%">
<img src="image\Apply filter.png" width="100%" height="40%">

- Click the ... button > Select Sort Descending > Sort by: Count of Book ID

<img src="image\Select Sort Descending.png" width="100%" height="40%">
<img src="image\Sort by Count of Book ID.png" width="100%" height="40%">

---

## Step 7: Create Card Visuals to Display Total Revenue and Books Sold

<img src="image\Create Card Visuals.png" width="100%" height="40%">
<img src="image\Count of Books.png" width="100%" height="40%">
<img src="image\Books Sold.png" width="100%" height="40%">
<img src="image\Total Revenue.png" width="100%" height="40%">
<img src="image\Display Total Revenue.png" width="100%" height="40%">

---

## Step 8: Create a Slicer (Filter Control) to Filter Data by Month

<img src="image\Create a Slicer (Filter Control).png" width="100%" height="40%">
<img src="image\MonthName.png" width="100%" height="40%">
<img src="image\Sort descending.png" width="100%" height="40%">

---

## Step 9: Disable the Interaction when Selecting a Book So That The Total Revenue Card is not Affected by The Book Filter (but It Should Still Respond to The Month Filter)
- Click on the Chiclet Slicer > Go to the Format tab at the top > Click Edit Interactions
<img src="image\Click Edit Interactions.png" width="100%" height="40%">
<img src="image\Click None.png" width="100%" height="40%">
<img src="image\Click another None.png" width="100%" height="40%">
<img src="image\Click else another None.png" width="100%" height="40%">
<img src="image\Click Edit Interactions to close.png" width="100%" height="40%">

---
