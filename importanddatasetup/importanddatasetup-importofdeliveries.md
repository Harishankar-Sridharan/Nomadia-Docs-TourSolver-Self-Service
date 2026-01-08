# Import of Deliveries

## 1. Introduction

Welcome! This guide is designed to make importing your delivery data into the server a smooth and successful experience.

The Import of Deliveries allows you to upload a list of addresses and customer information directly into the system for viewing and route optimization. By following these easy steps, you will match your spreadsheet columns to the required system fields, visualize the locations on a map, and begin optimizing your delivery routes.

***

## 2. Initial Configuration

#### Accessing My Deliveries

To begin importing your deliveries, you first need to navigate:

1. From the main menu to **My Deliveries**.
2. You are now ready to import your **Data.**

#### Downloading Sample Data

If you are unsure how to format your Excel file, you can download a sample template. Using the sample data ensures your file is ready for import immediately.

1. Click on **Download**.
2. The Excel file containing sample data will be downloaded.

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/ImportandDataSetup-ImportofDeliveries_timestamp_0_to_14%E2%80%930_to_18.gif" alt=""><figcaption></figcaption></figure>

💡 **Tip** : Always use the sample data provided if you are new to the system structure. This often reduces potential mapping errors later on!

***

## 3. Feature Explanations with Benefits

The import process includes several key steps that help ensure your data is accurately prepared for route planning:

| Feature                | Context and Benefit                                                                                                                                                                                              |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Data Mapping**       | This ensures that the column headings in your uploaded spreadsheet (like "Cust ID" or "Client Name") are correctly matched to the fields the server uses. This precise matching is crucial for accurate routing. |
| **Geocoding Colors**   | After importing, the system automatically tries to find the precise location (geocode) of each delivery address. Colors indicate success or failure, allowing you to quickly spot and correct errors.            |
| **Route Optimization** | This is the final step where the system calculates the most efficient order and path for your imported deliveries.                                                                                               |

## 4. Importing Deliveries and Optimizing Routes

This task covers the process of uploading your delivery data, verifying field matching, and initiating route planning.

#### Importing Data and Mapping Fields

You need to tell the system which columns in your spreadsheet correspond to the systemʼs fields (like Customer ID or Name).

1. Click on **import** to begin the process of importing your delivery data into the server

<figure><img src="../.gitbook/assets/image (7) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. A mapping window will appear, prompting you to match your Excel fields with the required server fields.
3. If a field is already matched correctly (as happens if you use the template), you can skip mapping for that field.

**To reset or adjust a field mapping (using Customer ID and Name as an example):**

4. If a field is currently mapped, you may choose to ignore it.
5. Click _ignored_ to map the field to a different constraint of TourSolver.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/ImportandDataSetup-ImportofDeliveries_timestamp_1_to_58%E2%80%932_to_00.gif" alt=""><figcaption></figcaption></figure>

6. Click on **show all** to view all possible field options.

<figure><img src="../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

7. Click on the **Customer ID** option to map it.

<figure><img src="../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

8. If you need to change the Name field, click on ignore under the current name mapping.

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

9. Click on **Name** to complete the mapping for the name field

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

#### Reviewing Data and Geocoding results

After confirming the data mapping, you can proceed to the map view to review geocoding results.

1. Click on **Next** once the mapping is complete

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

2. The map view will appear, displaying your locations with geocoding colors

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

3. Review the **locations** and their **colors**.
4. If you see Gray locations, those addresses were not found by the system. You may need to review and correct those addresses in your original data before optimizing the route for accuracy

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

5. Click on **Optimize my routes** to begin the route calculation

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

6. Once you **start the optimization**, the system will begin the calculation process.

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

## 5. Understanding Geocoding Status

When the map view appears, colors guide you to understand if your addresses were successfully located (geocoded):

* **Yellow color** indicates that the location was successfully geocoded at the street level.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

* Green color indicates that the location was successfully geocoded at the building level.

<figure><img src="../.gitbook/assets/msedge_I56jJ1SpJB.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image%20(31).png" alt=""><figcaption></figcaption></figure>

* **Gray color** indicates that the location was not geocoded.

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image%20(32).png" alt=""><figcaption></figcaption></figure>

***

## 6. Productivity Tips

Here are a few ways to make your data import faster and more accurate:

* 💡 **Prioritize Yellow:** When reviewing the map view, you know that yellow locations are reliable (geocoded at the sheets). Focus your attention on any locations marked **Gray**.
* 💡 **Master Mapping Efficiency:** If you need to quickly change how a field is matched, remember you can choose to **ignore** the current mapping and then select the correct field name immediately. This is quicker than correcting the data in your spreadsheet outside of the system.

