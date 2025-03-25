# Creating Sheet Format Templates in BarTender™

[🏠 Home](../index.md) > [Guides](./index.md) > BarTender Template Guide

## Introduction to BarTender™

BarTender™ is a powerful label design and printing software widely used in laboratory environments. This guide will walk you through creating sheet format templates in BarTender™, which is essential for printing labels on sheet format media like laser or inkjet labels.

Creating sheet format templates in BarTender™ is straightforward when using the template Wizard, which guides you through the process step by step.

## Step-by-Step Template Creation Process

### Step 1: Launch BarTender™

When you launch BarTender™, the New Document Wizard will appear automatically. If it doesn't, you can access it by selecting **File > New** from the menu.

![BarTender New Document Wizard](../Resources/images/bartender-wizard-1.png)

Choose **Blank Template** to create a brand-new template, or select an existing BarTender™ document if you want to modify an existing template.

### Step 2: Select Your Printer

Choose your printer from the list of available printers. Make sure you select the printer you'll be using to print your labels.

![Select Printer](../Resources/images/bartender-wizard-2.png)

### Step 3: Specify Custom Settings

For sheet format templates, select **Specify Custom Settings** to create your template from scratch.

![Specify Custom Settings](../Resources/images/bartender-wizard-3.png)

### Step 4: Set Page Size and Orientation

Choose your page size (Letter 8.5" x 11" or A4 210mm x 297mm) and orientation (Portrait or Landscape) to match your label sheets.

![Page Size and Orientation](../Resources/images/bartender-wizard-4.png)

### Step 5: Choose Label Shape

Specify the shape of your labels. Most laboratory labels are rectangular, but BarTender™ also supports rounded corners and circular labels.

![Label Shape](../Resources/images/bartender-wizard-5.png)

### Step 6: Specify Margins

Enter the top, bottom, left, and right margin sizes for your label sheet. You can find this information in our formatting appendix:

[GA International Formatting Appendix](https://cdn.labtag.com/wp-content/uploads/GA-International-Appendix-EN012020-January-28-2020.pdf)

![Margin Settings](../Resources/images/bartender-wizard-6.png)

### Step 7: Specify Columns and Rows

Enter the number of columns and rows of labels on your sheet. This information is also available in our formatting appendix, referenced by the template number.

![Columns and Rows](../Resources/images/bartender-wizard-7.png)

### Step 8: Set Label Size

BarTender™ will automatically calculate the label size based on your previous settings. If you need to make minor adjustments:

1. Select **Set Manually**
2. Enter the desired width and height values for your labels

![Label Size](../Resources/images/bartender-wizard-8.png)

### Step 9: Set Printing Order

Specify the printing order for your labels, usually "Top-Left" and "Horizontally" for most applications.

![Printing Order](../Resources/images/bartender-wizard-9.png)

### Step 10: Choose Background (Optional)

You can choose a background color or picture for your labels if desired. This step is optional and can be skipped for most laboratory labels.

![Background Settings](../Resources/images/bartender-wizard-10.png)

### Step 11: Review Template Summary

The final window provides a summary and preview of your label template. Review the settings to ensure everything is correct.

![Template Summary](../Resources/images/bartender-wizard-11.png)

### Step 12: Finish and Begin Designing

Click **Finish** to exit the Wizard. Now you can start adding text, barcodes, and other elements to your label template.

![Template Editor](../Resources/images/bartender-wizard-12.png)

## Adding Content to Your Template

### Adding Text

1. Click the **Text** tool in the toolbar
2. Click on the label where you want to add text
3. Type your text
4. Use the Properties panel to format the text (font, size, style, etc.)

### Adding Barcodes

1. Click the **Barcode** tool in the toolbar
2. Click on the label where you want to place the barcode
3. Select the barcode type from the Barcode Properties dialog
4. Enter the data to be encoded or link to a data source
5. Adjust barcode properties as needed

### Adding Images

1. Click the **Picture** tool in the toolbar
2. Click on the label where you want to add the image
3. Browse to and select your image file
4. Use the Properties panel to resize and position the image

## Additional Tips and Settings

### Changing Ruler Units

To change the ruler settings (e.g., from mm to inches):

1. Go to **File > Page Setup**
2. Click the **Units** tab
3. Select your preferred unit of measurement
4. Click **OK**

![Ruler Settings](../Resources/images/bartender-ruler-settings.png)

### Making Additional Changes to the Template

You can modify your template layout at any time by:

1. Double-clicking on a blank portion of your label template
2. Clicking the **Wizard** button in the bottom left of the window
3. Following the steps to adjust your template settings

![Relaunch Wizard](../Resources/images/bartender-relaunch-wizard.png)

### Displaying Encoded Information with Barcodes

To control whether the human-readable text appears with your barcode:

1. Double-click on the barcode
2. Select **Human Readable** in the left-hand pane
3. Choose your preferred option:
   - **None**: No human-readable text
   - **Below**: Text appears below the barcode
   - **Above**: Text appears above the barcode
4. Use the Placement, Alignment, Vertical and Horizontal Offset options to position the text

### Connecting to a Database

For printing from a database:

1. Double-click on a text box or barcode to open its properties
2. Click on the icon to the right of the box in the Data Source tab (default reads "Embedded Data")
3. Select **Database Field** from the dropdown menu
4. Follow the Database Connection Wizard to connect to your data source

For detailed instructions on database connectivity, see our [Database Printing Guide](./database-printing.md).

## Saving Your Template

Remember to save your template once you are done designing it:

1. Go to **File > Save** or **File > Save As**
2. Choose a location and enter a filename
3. Click **Save**

We recommend using a naming convention that includes the label product number for easy reference.

## Additional Resources

- [BarTender Software Official Documentation](https://www.seagullscientific.com/support/downloads/manuals-and-guides/)
- [Database Printing Guide](./database-printing.md)
- [Printer Settings Guide](./printer-settings.md)
- [Thermal Printer Guide](../Resources/printer-guide.md)

---

[Back to Guides](./index.md) | [Software Guides](./software-guides.md) | [FAQ](../Resources/faq.md) 