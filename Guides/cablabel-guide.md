# Creating Sheet Format Templates in Cablabel S3 Light & Pro

[🏠 Home](../index.md) > [Guides](./index.md) > Cablabel S3 Guide

## Introduction to Cablabel S3

Cablabel S3 is a powerful label design software developed by cab, compatible with cab label printers and suitable for a wide range of labeling applications. This guide will walk you through the process of creating sheet format templates in both Cablabel S3 Light and Pro versions.

## Step-by-Step Template Creation Process

### Step 1: Launch Cablabel S3 and Create a New Label

1. Open the Cablabel S3 software
2. Select **New Label** from the pane on the left side of the screen

![Cablabel New Label](../Resources/images/cablabel-new-label.png)

### Step 2: Configure Label Settings

1. In the new template dialog:
   - Select measuring unit (**mm** or **inch**) from the dropdown menu
   - Enter the label dimensions in the fields on the right
   
2. No other specifications need to be changed, unless you are using a label which is more than one across. In that case, please enter the correct amount of Label columns.

![Label Settings](../Resources/images/cablabel-label-settings.png)

**Note:** For accurate dimensions, refer to our [GA International Formatting Appendix](https://cdn.labtag.com/wp-content/uploads/GA-International-Appendix-EN012020-January-28-2020.pdf) to find the specific dimensions for your label format.

### Step 3: Finish Setup and Create Template

1. Click **Next** to continue
2. The blank label template will appear on your screen, ready for content

![Blank Template](../Resources/images/cablabel-blank-template.png)

## Adding Content to Your Template

### Adding Text

1. Click on **Text** in the top left corner of the interface
2. Click anywhere on your template to open the Text properties dialog
3. Enter the text you'd like to appear on your template
4. Select the font properties you'd like to use (font, size, style, etc.)
5. Click **OK** once you are done

![Adding Text](../Resources/images/cablabel-add-text.png)

### Adding Barcodes

1. Click on **Barcode** in the top left corner of the interface
2. Click anywhere on your template to open the Barcode properties dialog
3. Enter the value you'd like to encode in the box at the bottom of the screen
4. Select the 1D or 2D barcode type you'd like to use from the pane on the left-hand side of the window
5. Click **OK** once you are finished

![Adding Barcode](../Resources/images/cablabel-add-barcode.png)

## Controlling Barcode Display Options

### Human-Readable Text Display

To control whether the human-readable text appears with your barcode:

1. Double-click on the barcode to open its properties
2. Select the **Barcode** tab at the top of the new window
3. To hide the human-readable portion, uncheck the box labeled **Human readable**
4. Click **OK** to apply the changes

![Human Readable Settings](../Resources/images/cablabel-human-readable.png)

**Note:** Unlike some other label design software, Cablabel S3 doesn't offer extensive options for positioning the human-readable text. It's either displayed in the default position or not displayed at all.

## Adjusting Printer Settings

### Speed and Darkness Settings

To adjust print quality settings:

1. Click on **File** and select **Print**
2. Click on the **Printer Settings** button
3. Navigate to the appropriate tab (varies by printer model)
4. Adjust the **Heat** or **Temperature** setting to control darkness
5. Adjust the **Speed** setting as needed
6. Click **OK** to apply the settings
7. Click **Print** to proceed with printing

![Printer Settings](../Resources/images/cablabel-printer-settings.png)

## Advanced Features

### Working with Variables

To create dynamic text fields:

1. Create a text or barcode object
2. Right-click on the object and select **Properties**
3. In the Value field, click the **Variables** button
4. Choose the variable type (database field, counter, date/time, etc.)
5. Configure the variable settings and click **OK**

### Using Database Connections

Cablabel S3 Pro allows connecting to databases:

1. Go to **File > Database Connection**
2. Select your database type (Excel, Access, SQL, etc.)
3. Configure the connection parameters
4. After connection, database fields become available as variables
5. Link database fields to text or barcode objects as described in the Variables section

## Exporting and Importing Templates

### Saving Templates

1. Go to **File > Save** or **File > Save As**
2. Choose a location and enter a filename
3. Select the file format (*.c3l for Cablabel S3 format)
4. Click **Save**

### Exporting for Different Printers

If you need to use the same design on different printers:

1. Go to **File > Save As**
2. Select **Exchange Format** (*.x3l) from the file type dropdown
3. This format allows the design to be opened and adapted for different printer models

## Troubleshooting

### Common Issues and Solutions

**Issue: Print quality problems**
- Solution: Adjust darkness/heat and speed settings in the printer configuration
- Solution: Ensure the proper media type is selected in printer settings

**Issue: Barcode scanning issues**
- Solution: Increase barcode size or module width
- Solution: Check quiet zones around the barcode
- Solution: Ensure proper contrast (especially important for thermal transfer printing)

**Issue: Text or barcodes appear distorted**
- Solution: Check that the correct printer driver is selected
- Solution: Verify the label size matches the actual media being used

## Additional Resources

- [Cablabel S3 Official Documentation](https://www.cab.de/en/marking/software/cablabel-s3/)
- [Printer Settings Guide](./printer-settings.md)
- [Database Printing Guide](./database-printing.md)
- [Barcode Specifications Guide](../Resources/barcode-specifications.md)

---

[Back to Guides](./index.md) | [Software Guides](./software-guides.md) | [FAQ](../Resources/faq.md) 