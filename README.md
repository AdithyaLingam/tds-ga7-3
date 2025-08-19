# Supply Chain Correlation Analysis

This repository contains a correlation analysis of supply chain dataset variables:

- **Supplier_Lead_Time**
- **Inventory_Levels**
- **Order_Frequency**
- **Delivery_Performance**
- **Cost_Per_Unit**

## Files in this Repository

- `correlation.csv` → CSV file containing the correlation matrix values.  
- `heatmap.png` → Heatmap screenshot generated in Excel using conditional formatting.  
- `README.md` → This file with documentation.

## Steps to Reproduce (Excel)

1. **Enable Analysis ToolPak**
   - File → Options → Add-ins → Manage: Excel Add-ins → Go  
   - Tick **Analysis ToolPak** → OK  

2. **Generate Correlation Matrix**
   - Data → Data Analysis → Correlation  
   - Input Range: select all 5 columns (A:E)  
   - Check **Labels in first row**  
   - Output to new worksheet  

3. **Create Heatmap**
   - Copy correlation values (not labels) to a clean sheet  
   - Home → Conditional Formatting → Color Scales → Red-White-Green  

4. **Export Results**
   - Save correlation matrix as `correlation.csv`  
   - Take screenshot of heatmap (400x400 to 512x512 px) → save as `heatmap.png`  

---

📧 Contact: **24f1002079@ds.study.iitm.ac.in**
