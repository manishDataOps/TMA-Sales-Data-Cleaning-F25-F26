## ⚙️ Data Transformation Using Power Query (M Language)

The dataset was processed using Power Query M language to handle multiple raw Excel files and transform them into a structured format.

### 🔄 Key Steps Performed:

1. **Folder-Based Data Ingestion**

   * Loaded multiple Excel files from a folder
   * Extracted only relevant sheets dynamically

2. **Data Cleaning & Structuring**

   * Removed null and empty rows
   * Transposed data to fix layout issues
   * Promoted headers dynamically

3. **Dynamic Column Identification**

   * Automatically detected key columns such as Year, Month, MFR, and Category

4. **Unpivot Transformation**

   * Converted cross-tabular format into normalized tabular format

5. **Manufacturer Grouping**

   * MM + PTL → MM(G)
   * EIC + TAFE → EIC(G)
   * ESC + Kubota → ESC(G)

6. **Data Aggregation**

   * Grouped and summed volume data for analysis

### 📌 Outcome:

A clean, structured, and analysis-ready dataset suitable for Power BI, SQL, and business analytics.
