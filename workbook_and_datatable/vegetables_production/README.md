## Product Value Estimator

A **UiPath** automation that reads product data from an existing **Excel workbook**, calculates the **estimated value** of each product, formats the calculated values, and generates analytical reports using Excel.

The practice project demonstrates the use of **Workbook**, **DataTable**, and **Excel** activities to process and analyze spreadsheet data. It reads product information from the input workbook, adds a new column named **Estimated Value**, calculates the value by multiplying **Quantity** by **Price per Kg** for each record, and writes the updated DataTable to a **new worksheet** within the same workbook.

After updating the data, the automation performs additional Excel operations by:

- Format the **Estimated Value** column as **Currency**.
- Create a **Pivot Table** using the updated data in the workbook.
- Generate an **Excel Chart** based on the Pivot Table to visually summarize the product data.

This project demonstrates how UiPath can be used not only for data processing but also for automating common Excel reporting and data visualization tasks.

> **Note:** This project is a practice exercise completed by following the UiPath Academy course **Excel Automation with the Modern Experience in Studio**.

![Product Value Estimator Project view](./images/productvalueestimator.gif)