# Procurement and Supply Chain Dashboard

## Business Context

In our dynamic business environment, efficient procurement and supply chain management are pivotal to reducing costs, optimizing resources, and enhancing competitiveness. The Accounts Department of our company meticulously maintains detailed invoice records for every vendor and part procured. These records provide a treasure trove of data that, when analyzed effectively, can unlock valuable insights for the company's strategic procurement decisions.

## Final Dashboard:

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/94e0c824-647d-493c-9178-51d6516f6243)

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/533fa1cd-6cd7-42bf-8c94-b1d5cd1d13aa)

## Problem Statement

The task at hand is to leverage the vast and diverse dataset encompassing multiple years, plants, business units, materials, suppliers, and more. Our goal is to derive actionable insights that empower the Procurement Department to make data-driven supply chain decisions.

## Dataset Description

The dataset comprises three distinct sets of data:

### Report Data
- Contains information about invoices, including invoice number, month, year, business unit, manufacturing plant, part details, supplier details, quantities, values, and more.

| Column Name              | Type   | Description                                             |
|--------------------------|--------|---------------------------------------------------------|
| Invoice no.              | Text   | Unique identifier for the specific invoice entry.       |
| Month                    | Text   | Month when the invoice was made, defined in numeric form (e.g., 1=Jan, 2=Feb, 3=Mar, and so on). |
| Year                     | Text   | Year when the invoice was made.                        |
| BU                       | Text   | Business Unit of the Manufactured Part.                |
| Plant                    | Text   | Manufacturing Plant of the Business Unit.              |
| Part number              | Text   | Unique Identifier of the specific type of manufactured part. |
| Description              | Text   | Description name of the Part.                         |
| MCR Mat.grp.             | Text   | MCR Material Group the Part Belongs to.               |
| Suppliernumber           | Text   | Supplier who invoiced the part.                        |
| Invoicequantity          | Number | Quantity of the parts invoiced in the invoice.         |
| Invoicevalue             | Number | Total Value of the invoice.                             |
| Invoice exch.Rate        | Number | Currency exchange rate.                                 |
| Invoicecurrency          | Text   | Currency of the invoice.                               |
| Price per price unit(IST rate) | Number | Price of one unit of parts.                            |
| Price unit               | Number | Number of Parts in a Unit.                             |
| AVGPrice PY              | Number | Average Running price (Planning Year).                  |
| AVG Price PY without CE  | Number | Average Running price (Planning Year) without Cost Impact. |
| Type                     | Text   | Type of Invoice.                                       |
| Purchasinggroup          | Text   | Code assigned to a person who is responsible for the specific purchase. |
| Commodity                | Text   | Commodity Define.                                      |

### Material Weights and Source Data
- Provides insights into part weights, casting details, supplier information, and commodity categorization. This dataset enables us to understand the materials used and their sources.

| Column Name                | Type   | Description                                             |
|----------------------------|--------|---------------------------------------------------------|
| Part no                    | Text   | Unique Identifier of the specific type of manufactured part. |
| Part Dic.                  | Text   | Description name of the Part.                         |
| Part Family                | Text   | Family Group the part belongs to.                     |
| Casting P/N                | Text   | Casting Part Number linked to the Final Part.          |
| Casting Source             | Text   | Source where the casting was done.                    |
| Casting Process            | Text   | Process of casting.                                   |
| Plant                      | Text   | Manufacturing Plant of the Business Unit.              |
| SupplierNum                | Text   | Specific Number assigned to each Supplier.             |
| Supplier Name Short        | Text   | Name Of the Supplier.                                 |
| Commodity                  | Text   | Defining Non-Ferrous/Ferrous parts.                   |
| RM Grade                   | Text   | Raw Material Alloy Grade.                             |
| Weight                     | Number | Weight of the parts per Unit.                         |
| Conversion factor (number of parts) | Number | Number of parts in one Unit.                |
| System Weight (Kg)         | Number | Average Weight per part.                              |
| Purchasing group           | Text   | Code assigned to a person who is responsible for the Part and Supplier. |

### Supplier Data
- Focuses on supplier-related information, including their location, business growth strategy, MSME classification, payment terms, and capabilities such as casting and machining.

| Column Name           | Type   | Description                                            |
|-----------------------|--------|--------------------------------------------------------|
| SL no                 | Text   | Serial Number - A unique identifier for each supplier. |
| Commodity             | Text   | Defining Non-Ferrous/Ferrous Suppliers.               |
| Supplier Number       | Text   | Specific Number assigned to each Supplier.            |
| Name                  | Text   | Name Of the Supplier.                                 |
| Buyer Code            | Text   | Code assigned to a person who is responsible for the Part and Supplier. |
| Buyer Name            | Text   | Name Of the Responsible Buyer.                        |
| City Location         | Text   | Location Of the Supplier.                             |
| Strategy Status       | Text   | Business Growth Strategy with the supplier (e.g., 'Go' for Grow & 'NoGo' for Not to Grow). |
| MSME type             | Text   | Micro, Small & Medium Enterprises category of the supplier (Turnover > 100cr). |
| Payment Terms (Days)  | Text   | Payment Release Terms with Supplier.                   |
| Casting               | Text   | Indicates if Supplier has Metal Casting Capability.    |
| Machining             | Text   | Indicates if Supplier has Metal Machining Capability.  |

## Dashboard Objectives

Our mission is to create an insightful and interactive dashboard that addresses several key objectives:

1. **Procurement Trends:** Provide a comprehensive overview of procurement trends over different months and years, segmented by business units and plants.

2. **Supplier Limitations:** Identify any limitations or constraints associated with suppliers, such as their capabilities, payment terms, and growth strategy.

3. **Product-Based Supplier Consolidation:** Determine opportunities for supplier consolidation based on part families, materials, and weights.

4. **Cost Minimization:** Analyze data to minimize cost impacts and optimize procurement strategies.

## Dashboard Features

The dashboard will feature a user-friendly interface with interactive visualizations, including:

- **Time Series Trends:** Line charts depicting procurement trends over time.
- **Supplier Heatmaps:** Heatmaps showcasing supplier capabilities and limitations.
- **Part Family Insights:** Pie charts and bar charts illustrating part family distributions.
- **Cost Optimization:** Tables and visuals highlighting cost minimization opportunities.

## Key Benefits

The Procurement and Supply Chain Dashboard will provide the following benefits:

- Enhanced Procurement Strategy: Data-driven insights for strategic procurement planning.
- Cost Optimization: Identification of cost-saving opportunities.
- Supplier Consolidation: Rationalization of suppliers based on data.
- Efficient Decision-Making: Real-time access to critical procurement information.

## Download Chiclet Slicer from [here](https://lms-new.codinginvaders.com/assets/courseware/v1/ef7030f8c0eb477b63493c6bb4a4079c/asset-v1:CodingInvaders+DATEST+1+type@asset+block/chicletSlicer.pbiviz)

## Icon Links for Supplier Data Columns

To enhance the visual representation of the Supplier Data columns in our dashboard, we have included icons for the "Commodity," "Casting," and "Machining" columns. Here are the icon links:

### Commodity Column Icons
- **Ferrous Commodity Icon:**  
  ![Ferrous Commodity Icon](https://cdn-icons-png.flaticon.com/128/4027/4027079.png)
  
- **Non-Ferrous Commodity Icon:**  
  ![Non-Ferrous Commodity Icon](https://cdn-icons-png.flaticon.com/128/4027/4027130.png)

### Casting and Machining Column Icons
- **Casting Icon:**  
  ![Casting Icon](https://w7.pngwing.com/pngs/164/44/png-transparent-die-casting-manufacturing-zinc-aluminium-metal-others-blue-text-logo.png)

- **Machining Icon:**  
  ![Machining Icon](https://prototechasia.com/wp-content/uploads/Metal-Machining.png)

These icons will be used to visually represent the commodity type, casting capability, and machining capability in the dashboard's user interface, making it more intuitive and informative for users.

------------------------------------------------------------------------------------------

#### Question 1: Non-MSME suppliers are basically the ones which have a Turnover > 100cr (1000 Million), Lower than this will be classified into different types of MSME category. How many of these suppliers do we have where we can not grow more business?

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/da29a4b2-a27d-453b-948a-d2a718a07e33)

#### Question 2: We have a forecast that the business for ferrous casting will reduce year on year, show me how many of our ferrous casting suppliers we would need to stop business in future as the demand starts coming down.

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/94e643fe-b901-476c-9948-d370cbcece74)

#### Question 3: Find out the list of Small MSME suppliers where the supply chain will not increase till tier 2 suppliers as they will have full Casting and Machining capabilities.

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/1388a30e-05ba-4ff1-bcaa-180896648cca)

#### Question 4: As per Government rules, we can't increase the payment terms more than 45 days for any type of MSME suppliers. Keeping this in mind do we have any Non-MSME suppliers where we can go above 45 days. If yes, what is the supplier name?

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/eee0984f-c4fc-411e-9ebd-c4f4b99e0f95)

#### Question 5: Pune is one of the Flood Risk Zone, to prepare our supplier for difficult scenarios a taskforce has been assigned. Taskforce wants to know how many of our suppliers are from Pune?

![image](https://github.com/sanjanapaluri/Powerbi_Projects/assets/127730680/7f69556b-d1c7-45ec-8be0-7d13c8e41272)
