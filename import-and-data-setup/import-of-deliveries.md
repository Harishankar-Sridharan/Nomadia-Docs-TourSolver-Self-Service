# Import of Deliveries

## Introduction

Welcome! This guide is designed to make importing your delivery data into the server a smooth and successful experience.

The **Import of Deliveries**allows you to upload a list of addresses and customer information directly into the system for viewing and route optimization. By following these easy steps, you will match your spreadsheet columns to the required system fields, visualize the locations on a map, and begin optimizing your delivery routes.

## Getting Started

### Accessing the Import Area

To begin importing your deliveries, you first need to navigate to the correct reporting area.

1. From the main menu, go to **Deliveries**.
2. You are now ready to access the Delivery Report interface.

### Downloading Sample Data

If you are unsure how to format your Excel file, you can download a sample template. Using the sample data ensures your file is ready for import immediately.

1. Click on **Download**.
2. The Excel file containing sample data will be downloaded.

![](<../.gitbook/assets/Unknown image (27)>)

💡 **Tip**: Always use the sample data provided if you are new to the system structure. This often reduces potential mapping errors later on !

## Feature Explanations with Benefits

The import process includes several key steps that help ensure your data is accurately prepared for route planning:

| Feature                | Context and Benefit                                                                                                                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Data Mapping**       | This ensures that the column headings in your uploaded spreadsheet (like "Cust ID" or "Client Name") are correctly matched to the fields the server uses. This precise matching is crucial for accurate routing. |
| **Geocoding Colors**   | After importing, the system automatically tries to find the precise location (geocode) of each delivery address. Colors indicate success or failure, allowing you to quickly spot and correct errors.            |
| **Route Optimization** | This is the final step where the system calculates the most efficient order and path for your imported deliveries.                                                                                               |
|                        |                                                                                                                                                                                                                  |

## Importing Deliveries and Optimizing Routes

This task covers the process of uploading your delivery data, verifying field matching, and initiating route planning.

### Task: Importing Data and Mapping Fields

You need to tell the system which columns in your spreadsheet correspond to the systemʼs fields (like Customer ID or Name).

1. Click on **import**to begin the process of importing your delivery data into the server.

![](<../.gitbook/assets/Unknown image (28)>)



1. A mapping window will appear, prompting you to match your Excel fields with the required server fields.

![](<../.gitbook/assets/Unknown image (29)>)



1. If a field is already matched correctly (as happens if you use the test link), you can skip mapping for that field.
2. **To reset or adjust a field mapping**(using Customer ID and Name as an example):

* If a field is currently mapped, you may choose to **ignore**it.

![](<../.gitbook/assets/Unknown image (30)>)



* Click on **show all**to view all possible field options.

![](<../.gitbook/assets/Unknown image (31)>)



* Click on **customer ID**option to map the customer ID column.

![](<../.gitbook/assets/Unknown image (32)>)



* If you need to change the Name field, Click on **ignore**under the current name mapping.

![](<../.gitbook/assets/Unknown image (33)>)



* Click on **name**to complete the mapping for the name field.

![](<../.gitbook/assets/Unknown image (34)>)

### Reviewing Data and Optimizing Routes

After confirming the data mapping, you can proceed to the map view and start planning.

1. Click on **next**once the mapping is complete.

![](<../.gitbook/assets/Unknown image (35)>)

1. The map view will appear, displaying your locations with geocoding colors.

![](<../.gitbook/assets/Unknown image (36)>)

1. Review the locations and their colors.
2. If you see gray locations, those addresses were not found by the system. You may need to review and correct those addresses in your original data before optimizing the route for accuracy.

![](<../.gitbook/assets/Unknown image (37)>)

1. Click on **optimize my routes** to begin the route calculation.

![](<../.gitbook/assets/Unknown image (38)>)

1. Once you start the optimization, the system will begin the calculation process.

![](<../.gitbook/assets/Unknown image (39)>)

### Understanding Geocoding Status

When the map view appears, colors guide you to understand if your addresses were successfully located (geocoded):



* **Yellow color** indicates that the location was successfully geocoded at the sheet level.

![](<../.gitbook/assets/Unknown image (40)>)



* **Gray color** indicates that the location was not geocoded.

![](<../.gitbook/assets/Unknown image (41)>)

## Productivity Tips

Here are a few ways to make your data import faster and more accurate:

* **Prioritize Yellow**: When reviewing the map view, you know that yellow locations are reliable (geocoded at the sheet level). Focus your attention on any locations marked **Gray**.
* **Master Mapping Efficiency**: If you need to quickly change how a field is matched, remember you can choose to **ignore** the current mapping and then select the correct field name immediately. This is quicker than correcting the data in your spreadsheet outside of the system.
