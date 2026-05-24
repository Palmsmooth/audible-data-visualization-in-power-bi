# Load Data & Custom Visual
## Step 1: Import Data from BigQuery into Power BI First
- Go to the top Home tab > Get Data > More > type “bigquery” in the search box > select “Google BigQuery” > then click Connect

<img src="image\Get Data and More.png" width="100%" height="40%">
<img src="image\select “Google BigQuery” then click Connect.png" width="100%" height="40%">

- Sign in with your Google Cloud account

- Choose project > dataset > table/view

<img src="image\Choose project, dataset and table.png" width="100%" height="40%">

- Click Load bottle

---

## Step 2: Importing Book Cover Data into Power BI
- Go to the top Home tab > Enter Data > input the Book ID and Book Cover URL fields
    
    - You can get the book image URL from https://www.bookdepository.com/
    <img src="image\www.bookdepository com.png" width="100%" height="40%">

    - Search for the book you want > right-click and select “Open image in new tab” > then copy the URL
    <img src="image\right-click and select “Open image in new tab”.png" width="100%" height="40%">
    <img src="image\then copy the URL.png" width="100%" height="40%">
    
- Rename the Column Header > enter the Table Name in the bottom-left corner > then click Load.

<img src="image\enter the Table Name in the bottom-left corner .png" width="100%" height="40%">

- Go to the Data tab on the left > click on the Book Cover URL column header

<img src="image\Go to the Data tab on the left and click on the Book Cover URL column header.png" width="100%" height="40%">

- Go to the Column Tools tab at the top > change Data Category to Image URL (very important, otherwise the image will not display)

<img src="image\change Data Category to Image URL.png" width="100%" height="40%">

- To make the newly loaded Book Cover table connect with the Transaction table, go to the Modeling tab at the top > Manage Relationships > New > select the related tables > choose the key column in each table > click OK (set Cardinality to One-to-Many or Many-to-One, as appropriate)

<img src="image\Book Cover table.png" width="100%" height="40%">

---

## Step 3: Install the custom visual named Chiclet Slicer

- Click the three-dot (…) button in the Visualizations pane on the right to import a custom visual

<img src="image\Click the three-dot (…) button in the Visualizations pane.png" width="100%" height="40%">

- Type ‘Slicer’ in Search box > Click Add button when you see ‘Chiclet Slicer’

<img src="image\Click Add button when you see ‘Chiclet Slicer’.png" width="100%" height="40%">

- The Chiclet Slicer visual icon will now appear below the three-dot (…) button in the Visualizations pane, and in this example, we will create a dashboard for J. K. Rowling

<img src="image\The Chiclet Slicer visual icon will now appear below the three-dot (…) button in the Visualizations pane.png" width="100%" height="40%">

---




