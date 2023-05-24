+ ## 👉Business Case: 
 The Accounts Department of the Company maintains the invoice level details of all vendors for each part procured. The Business Planner receives invoice data from the Accounts Department for each vendor and collects the supplier and part level information separately from the Purchase Department. The Business Planner has to study the relevant data and identify the Procurement trends, Supplier limitations, Product based supplier consolidation and minimise cost impact to company.

+ ## 👉Problem Statement:
 As the collected Data is of different years for multiple Plants grouped by different Business Units. The parts are either made of Aluminium or Ferrous of different raw material grade alloys, with the source being either Tier 1 supplier or Tier 2 supplier. Considering all these factors, create a dashboard which is insightful on all these factors and can help the Procurement Department make better supply chain strategic decisions.
+
+ ## 👉Dataset Description:
 -Report Data Files(Report 2019,2020,2021)
 -Material weights and source
 -Supplier data

+ ## 👉 Tools Used: 
- 𝐌𝐢𝐜𝐫𝐨𝐬𝐨𝐟𝐭 𝐏𝐨𝐰𝐞𝐫 𝐁𝐢 (with Some DAX functions)

+ ## 👉 Analysis Procedure:
+ 🎀 Data Cleaning 
+ 🎀 Data Transformation
+ 🎀 Data Modeling 
+ 🎀 Data Visualization
+ 🎀 Findings
+ 🎀 Recommendations

+ This dataset provided by the Coding Invaders LMS platform. The dataset is then connected to Power BI Desktop for analysis. Power Query is utilized to transform and clean the data, ensuring it is in a suitable format for analysis.

+ ## 👉 Findings:
+ Ploted a Gauge Chart for suppliers and kept the max values as 35
+ Created a interactive button with Chiclet Slicer and created a link with the help of custom cloumn
+ Created a DAX function for tonnage using lookupvalue() and divided by 1000 to convert the weights into tons.
+ So far in past 2 years GI has highest RM Grade Tonnage with 1180.81 Tons from supplier group SSI and pur group as Rc
+ Created 2 Tooltip for RM and Casting Source assigning this tooltips to “Part Family Purchase volume” and “Part Family Tonnage” visuals.
+ In the year 2020 268.85 Tons of raw material was consumed by the biggest casting source for the “Flyweight” part family of source A Alloys.
+ Danny purchase volume as has fallen down for the month of October in 2020 compared to the previous year for all his suppliers, his highest purchase volume supplier in 2019 is 10.3M ,BIPL.
+ strategy Status: This is interally define classification supplier to decide future business prospects with GO and NOGO(can grow business , not grow business).
 + MSME bascially divided into 3 types
1. Micro
2. Small
3. Medium 
Any MSME type suppliers must be paid with 45 days as per governmet rules,Non MSME are considered as big companies this rule does not applies.
 
 + ## 👉 Recommendations :
 + -Supplier Overview : Gives us suppliers status and its capabilities. This will help the responsible buyer get a fouced quick insight for the suppliers.
 + -Volume Movement : Help analyze the purchase volume and tonnage volume movement throughout different years for past comparisions and business planning.
