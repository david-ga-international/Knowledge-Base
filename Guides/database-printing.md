# Printing Labels from a Database

[🏠 Home](../index.md) > [Guides](./index.md) > Database Printing

## Introduction to Database Printing

Connecting your label templates to a database allows for efficient batch printing of labels with variable information. This powerful feature eliminates manual data entry, reduces errors, and streamlines the labeling process for laboratories handling large numbers of samples.

This guide explains how to set up database connections in popular label design software programs and print labels using data from external sources such as Excel spreadsheets, CSV files, or other database formats.

## Benefits of Database-Connected Printing

- **Eliminate manual data entry**: Automatically populate labels with information from your database
- **Reduce transcription errors**: Information flows directly from your database to your labels
- **Batch printing**: Print multiple unique labels in a single print job
- **Integration with LIMS**: Connect directly to your Laboratory Information Management System
- **Maintain data integrity**: Ensure consistency between your database and physical sample labeling

## Database Printing in BarTender

BarTender offers robust database connectivity features, especially in the Professional and higher editions.

### Connecting to a Database

1. After designing your label template, double-click on either a text box or barcode to open its properties dialog box
2. Click on the icon to the right of the box **Type** in the **Data Source** tab, which by default reads "Embedded Data"

![BarTender Data Source](../Resources/images/bartender-data-source.png)

3. Select **Database Field** from the dropdown menu and click **Finish**
4. Click **Database Connection Setup** and select your Database Type (e.g., Excel)

![BarTender Database Setup](../Resources/images/bartender-database-setup.png)

5. Click **Select File** and browse to the location where your database is stored
6. Select the file you would like to retrieve your data from and click **Open**
7. Click **Next**, then **Finish**, then **OK**
8. Click on the arrow next to **Field Name** to select the column in your Excel file you would like to associate with your textbox or barcode, then click **Close**

![BarTender Field Selection](../Resources/images/bartender-field-selection.png)

### Connecting Multiple Objects to the Same Database

To connect another text box or barcode to the same database:

1. Double-click on the text box or barcode
2. Click on the symbol next to the **Type** field and select **Database Field**
3. Click **Next**
4. Select the column you'd like to connect to the text box or barcode from the **Field Name** dropdown menu
5. Click **Finish**, then **Close**

### Printing from the Database

1. Click **Print** to open the Print dialog box
2. In the **Selected Records** field, you can choose how many database entries you'd like to print

![BarTender Print Records](../Resources/images/bartender-print-records.png)

3. Leave the value at **1...** if you'd like to print all entries of your database
4. To print only a specific range (e.g., only the first 50 entries), type **1-50**
5. You can select how many copies per database entry will be printed by changing the value in **Copies per Serial Number**
6. Click on **Preview** to verify that the correct records and the correct number of copies per record will be printing before starting the print job

## Database Printing in ZebraDesigner Pro

ZebraDesigner Professional edition provides database connectivity features similar to BarTender.

### Connecting to a Database

1. Design your label template with the text and barcode objects you need
2. Right-click on a text or barcode object and select **Properties**
3. Click on the **Data Source** tab
4. Select **Database** as the data source type
5. Click **Next** to launch the Database Connection Wizard
6. Select your database type (Excel, Access, Text File, etc.)
7. Follow the wizard to connect to your database file
8. Select the table or worksheet containing your data
9. Click **Next** and then **Finish**
10. Select the database field to connect to this object
11. Click **OK** to complete the connection

### Printing from the Database

1. Click **File > Print** or press **Ctrl+P**
2. In the Print dialog, set the **Quantity** to determine how many labels to print
3. Select **All** to print all database records or **Selection** to print specific records
4. To print a range of records, select the **From/To** option and specify the range
5. Click **Print** to send the job to the printer

## Database Printing in Cablabel S3 Pro

Cablabel S3 Pro version includes database connectivity features.

### Connecting to a Database

1. Go to **File > Database Connection**
2. Select your database type from the available options
3. Navigate to and select your database file
4. Configure any required connection parameters
5. Click **OK** to establish the connection
6. Double-click on a text or barcode object on your template
7. In the properties dialog, click on the **Data Sources** tab
8. Select **Database Field** as the source
9. Select the appropriate field from your connected database
10. Click **OK** to complete the connection

### Printing from the Database

1. Click **File > Print** or the print icon in the toolbar
2. In the Print dialog, select the **Database** tab
3. Choose **All Records** or specify a range of records to print
4. Set the number of copies per record if needed
5. Click **Print** to begin printing

## Best Practices for Database Printing

### Database Preparation

1. **Clean your data**: Ensure your database has no duplicates, missing values, or formatting issues
2. **Use consistent formats**: Standardize date formats, units, and other values
3. **Include all required fields**: Make sure your database contains all information needed for your labels
4. **Use appropriate field names**: Clear, descriptive field names make it easier to select the right data
5. **Consider field lengths**: Ensure text fields aren't too long for your label design

### Testing Before Production

1. **Print a sample**: Always print a small batch as a test before printing hundreds of labels
2. **Verify data accuracy**: Check that the right data appears in the right fields
3. **Scan test barcodes**: Verify that barcodes scan correctly
4. **Check record sequence**: Ensure records print in the expected order

### Troubleshooting Common Issues

**Issue: No records appear to be available for printing**
- Solution: Check that your database connection is valid
- Solution: Verify that the database file is accessible and not locked by another program

**Issue: Text appears truncated on labels**
- Solution: Increase the size of the text object
- Solution: Enable text wrapping or scaling options
- Solution: Use a smaller font size

**Issue: Barcodes don't scan**
- Solution: Check that the data format is appropriate for the barcode type
- Solution: Verify that the barcode size is adequate for your scanner
- Solution: Ensure adequate quiet zones around barcodes

## Advanced Database Features

### Using Database Filters

Most label software allows filtering records before printing:

1. In the database setup or print dialog, look for filter options
2. Create a condition (e.g., Department = "Biology")
3. Only records matching this filter will be available for printing

### Using Data Processing Functions

Transform database data before printing with built-in functions:

1. In the object properties after connecting to a database field
2. Look for data processing or script options
3. Common functions include:
   - Text case conversion (UPPER, lower, Title Case)
   - Date formatting
   - Number formatting
   - Text concatenation or substring extraction

### Integrating with LIMS Systems

For advanced laboratory environments:

1. Check if your label software supports ODBC or SQL connections
2. Work with your IT department to establish secure connections
3. Consider middleware solutions if direct connections aren't possible
4. Test thoroughly in a non-production environment first

## Additional Resources

- [BarTender Database Tutorial](../Resources/bartender-database-tutorial.md)
- [ZebraDesigner Database Guide](../Resources/zebradesigner-database-guide.md)
- [LIMS Integration Overview](../Solutions/lims-integration.md)
- [Excel Formatting Tips for Label Databases](../Resources/excel-formatting-tips.md)

---

[Back to Guides](./index.md) | [Software Guides](./software-guides.md) | [FAQ](../Resources/faq.md) 