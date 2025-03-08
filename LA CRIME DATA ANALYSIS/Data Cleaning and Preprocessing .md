# Part 1: Data Cleaning and Preprocessing  

## 1. Column Widening  
- Use **AutoFit Column Width** (or `ALT + H + O + I`) to automatically adjust column widths so that all data is visible.  
- This ensures that no data is hidden or cut off, especially for longer text values.  

## 2. Removing Duplicates  
- **Method 1**: Use the **“Remove Duplicates”** feature in the Data Tools group in the Ribbon.  
- **Method 2**: Use `COUNTIF` to count occurrences and filter out duplicates.  
- **Method 3**: Use **Conditional Formatting** with `=COUNTIF($A$1:$A$1000, $A1) > 1` to highlight duplicates.  
- **Method 4**: Use `CONCATENATE` or `TEXTJOIN` with `COUNTIF` to track duplicates in a new column.  
- **Method 5**: Use **Conditional Formatting > Highlight Cells Rules > Duplicate Values** and then sort by color to group duplicates.  

## 3. Finding Missing Values  
- **Method 1**: Use **Conditional Formatting > New Rule > Format only cells that contain > Blanks** to highlight missing values.  
- **Method 2**: Use **Go To Special (`F5 > Special > Blanks`)** to locate missing values.  
- **Method 3**: Use `COUNTBLANK()` to quantify missing values in a column.  

## 4. Handling Missing Values  
- **Option 1**: Ignore rows with missing values if they are irrelevant to the analysis.  
- **Option 2**: Replace missing values with the **mean** using `ROUND(AVERAGE(...), 0)`.  
- **Option 3**: Replace missing values with **custom values** (`0`, `"No Data"`, `"Not Registered"`).  
- **Option 4**: For categorical data, create a new column to label missing values using `=IF(ISBLANK(A1), "No Weapon", A1)`.  

## 5. Creating Lookup Dictionaries  
- Created **lookup tables** for frequently used columns like **Crime Code, Weapon, Premise, Area, and Status**.  
- Used `UNIQUE()` or **Advanced Filtering** to generate unique lists of codes.  
- Applied `XLOOKUP`, `VLOOKUP`, and `INDEX(MATCH)` to map descriptions to codes.  
- **Victim Descent column** was enriched using external data sources.  

## 6. Text Data Cleaning  
- Cleaned text values using `CLEAN(TRIM(PROPER()))` to remove extra spaces and correct capitalization.  
- Standardized names (e.g., **“La” → “LA”**, **“77Th” → “77th”**).  

## 7. Formatting Date and Time Columns  
- Changed **TIME OCC** format to `"00:00"` by using **Format Cells > Time Format**.  
- **DATE OCC** was formatted as **Short Date**, and year/month/day were extracted using `YEAR()` and `TEXT()`.  

## 8. Correcting Data Types  
- Ensured that columns had the appropriate **data types** (numeric for rates, text for descriptions, etc.).  

## 9. Removing Low-Usability Columns  
- Removed **Crm Cd 1, Crm Cd 2, Crm Cd 3, and Cross Street** due to high missing values and low usability.  

## 10. Renaming Columns  
- Renamed columns for clarity, making the dataset **easier to understand and analyze**.  
