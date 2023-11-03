# Global Dashboard Data Preparation

In our quest to create a Global Dashboard with key metrics that serve all stakeholders in their decision-making, we have embarked on the crucial initial step of ensuring that the data is complete, clean, and can be seamlessly connected to our dashboard. To achieve this, we have collaborated with various analysts who are responsible for providing data from different regions and sources.

## Final Dashboard: 

## Task 1: Importing Data from Google Sheets

We initiated the data acquisition process by requesting all analysts to put their respective datasets into a standard format and share them on Google Sheets. Once we received the data, we established a real-time connection to these Google Sheets to ensure that our dashboard's metrics stay updated automatically without manual intervention.

### Steps for Importing Data from Google Sheets:

**Step 1: Publish Google Sheets as a Web Page**
1. Share the Google Sheets document with the setting "Anyone with the link can view."
2. Navigate to 'File' => 'Publish to the web.'
3. Choose 'Entire document' and 'Web page' and click 'Publish.'

**Step 2: Enter Data into Power BI**
1. Open Power BI Desktop and create a new file.
2. Click 'Get data' and select 'Web' as the source.
3. Paste the URL from the Google Sheets document into the dialogue box.
4. Choose the Google Sheets URL as the data source.
5. Select the relevant tables (Regional tables, Payslips, and Mapping sheet) and click 'Load.'

**Step 3: Clean and Rename Tables in Query Editor**
1. Open the Power Query Editor to clean and organize the imported data.
2. Rename the tables to match the names in the original dataset.
3. Remove any blank rows.
4. Remove the first column if unnecessary.
5. Set the first row as headers for each table.
6. Repeat these steps for all imported tables.
7. Click 'Close and Apply' to save the changes.

## Task 2: Combining Regional Invoice Details

In the Power Query view, we combined the Regional Invoice details tables into one main table called 'Main Table.' This consolidation enables us to work with a unified dataset for analysis and visualization.

### Steps to Combine Regional Invoice Details:

1. Append two Regional tables into one table, naming it 'Main Table.'
2. We performed basic cleaning, which involved replacing all blanks and nulls in numeric fields with 0. Additionally, we ensured that numeric fields displayed two decimal points where necessary.

----------------------------------------------------------------------------------------------------------------
