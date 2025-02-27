# Travel_Booking_SCD2_Merge_Project

## What is this?
This project implements a **Slowly Changing Dimension Type 2 (SCD2) Merge** process using **Databricks and GCP** to manage historical changes in travel booking data.

## What do we do in it?
- Process travel booking data with versioning.
- Load data into a **staging Delta table**.
- Apply **SCD Type 2 logic** to track historical changes.
- Merge updated records into a **target Delta table** while maintaining history.

## How to Run
1. Upload travel booking data to the designated source location in **DBFS**.
2. Run `Travel_Booking_SCD2_Merge.ipynb` to process and merge records while preserving historical changes.

