# Global Dashboard Data Preparation

In our quest to create a Global Dashboard with key metrics that serve all stakeholders in their decision-making, we have embarked on the crucial initial step of ensuring that the data is complete, clean, and can be seamlessly connected to our dashboard. To achieve this, we have collaborated with various analysts who are responsible for providing data from different regions and sources.

## Final Dashboard:
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/6eb45469-1cb5-4899-a193-28d08cea7b18)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/45334043-2f5d-4033-ad82-b9fe00fea7aa)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/163d1a02-c34a-4a13-aa4c-1df0b318661e)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/411ea44c-9ec5-40a5-aadf-715d716f2fc2)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/a62fd0fa-26d3-45b1-9bce-2b478c1fcbea)

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

#### Question 1: What is the Total Count of records in the Main Table?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/62ac5f93-f99a-40d8-840f-c9c2254bf5a3)

#### Question 2: Which country has the highest count of Invoices?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/9a4dcf28-cf01-492c-b8b1-dcbda4c181c9)

#### Question 3: What is the Count of Invoices for Singapore?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/a5e3734d-cdc5-4e6e-b92f-70a34513108d)

#### Question 4: If you view the data on the basis of the highest Invoice amount, which country will come at the top?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/e220ba67-43aa-4164-ac9d-e9adfa54ace7)

#### Question 5: Which Invoice number shows the highest amount?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/9c9aef3b-e07a-4394-a389-535ab9b7e691)


#### Question 6: Does the APAC region have the lowest Total Amount?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/8815bdda-96cb-4dc0-8372-b45f2f93a659)

#### Question 7: What is the Total Amount for the Base month (in Millions) ?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/ad184e40-3caf-493b-9534-528fbf92dbee)

#### QUestion 8: : What is the Payslip Count for Base Month (in Millions) ?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/d58a79a3-3966-4dd2-b84b-1e0d67329091)

#### Question 9: What is the % share of the Top 2 Vendors? Name the Vendors?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/a9b2f573-a886-4e94-9574-63b5113aa68c)

#### Question 10: What is the % share of the Top 2 Vendors? Name the Vendors?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/8db3eccc-4f51-4227-affe-36e3f4cf9f6f)

#### Question 11: Which Region shows the biggest bubble, if size of the bubble is represented by the Total Amount?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/32b46e03-3333-43a4-a608-b152857b8345)

#### Question 12: : What is the total Processing Cost for the Month of March 2020 for LATAM?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/0a545baa-c345-4c06-95c7-d939c3688dfa)

#### Question 13: How much Rebate did the Vendor ‘Vtl Inc.’ provide in Dec 2020?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/c6bb857f-e1e6-439c-ac60-1a66a3bc382a)

#### Question 14: : Which month shows the highest Payslip count for the EMEA region?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/40ba921c-5906-4065-8425-3ba5766fb869)

#### Question 15: What is the Payslip count for Canada in Dec 2020?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/22eb23dc-c2ee-48e6-9615-0abb86e3bd7f)

#### Question 16: How much value does the line chart show on Aug 2020, if you filter on North America?
![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/d130259a-4eb4-4acb-97f0-c530c1b64d3a)
