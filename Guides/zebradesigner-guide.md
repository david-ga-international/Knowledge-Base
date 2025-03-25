# Creating Sheet Format Templates in ZebraDesigner

[🏠 Home](../index.md) > [Guides](./index.md) > ZebraDesigner Guide

## Introduction to ZebraDesigner

ZebraDesigner is a powerful and user-friendly label design software specifically developed for Zebra printers. While primarily designed for thermal transfer and direct thermal printing on roll format labels, ZebraDesigner can also be used to create sheet format templates for laser and inkjet printing. This guide will walk you through the process of creating sheet format templates in ZebraDesigner.

## Step-by-Step Template Creation Process

### Step 1: Launch ZebraDesigner and Create a New Label

1. Open the ZebraDesigner software
2. Select **Create a new label** from the wizard
3. Click **Finish** to proceed to the printer selection screen

![ZebraDesigner New Label](../Resources/images/zebradesigner-new-label.png)

### Step 2: Select Your Printer

1. Select your printer from the drop-down list
2. Click **Next** to continue

![Select Printer](../Resources/images/zebradesigner-select-printer.png)

**Note:** For sheet format labels that will be printed on a laser or inkjet printer, you can select any printer as we will be manually defining the label dimensions.

### Step 3: Configure Label Stock Settings

1. Leave the **Select Stock** setting as it is
2. Click **Next** to continue

![Stock Settings](../Resources/images/zebradesigner-stock.png)

### Step 4: Configure Page Size Settings

1. Leave the **Page Size** setting as it is 
2. Click **Next** to continue

![Page Size](../Resources/images/zebradesigner-page-size.png)

### Step 5: Configure Label Layout

1. Leave the **Label Layout** setting as it is
2. Click **Next** to continue

![Label Layout](../Resources/images/zebradesigner-layout.png)

### Step 6: Set Label Dimensions

1. Enter the label width and label height in the **Label Dimensions** page
2. Leave all other settings as they are
3. Click **Finish** to create your template

![Label Dimensions](../Resources/images/zebradesigner-dimensions.png)

**Important:** For accurate dimensions, refer to our [GA International Formatting Appendix](https://cdn.labtag.com/wp-content/uploads/GA-International-Appendix-EN012020-January-28-2020.pdf) to find the specific dimensions for your label format.

### Step 7: Design Your Label

After completing these steps, the blank template will appear on your screen, ready for you to add content.

![Blank Template](../Resources/images/zebradesigner-blank-template.png)

## Adding Content to Your Template

### Adding Text

1. Click on the **Text** tool (usually represented by the letter "A" in the toolbar)
2. Click on your empty template where you want to add text
3. Type the text you want to appear on your label
4. Use the text formatting tools to adjust font style and size
5. Click anywhere outside the text box to set it

![Adding Text](../Resources/images/zebradesigner-add-text.png)

### Adding Barcodes

1. Click on the **Barcode** tool in the toolbar
2. Click on your empty template where you want to place the barcode
3. The barcode properties dialog will open:
   - Choose a 1D or 2D barcode type
   - Enter the information you want to encode
4. Click **Finish** to add the barcode to your template

![Adding Barcode](../Resources/images/zebradesigner-add-barcode.png)

The barcode will appear on your template. The letter "A" above the barcode allows you to create a text box and enter text manually if needed.

## Displaying Human-Readable Text with Barcodes

To control how the encoded information appears with your barcode:

1. Double-click on the barcode to open its properties
2. Click on the **Define** button next to the Barcode Type box
3. Select the **Human Readable** tab

![Human Readable Settings](../Resources/images/zebradesigner-human-readable.png)

4. Choose your preferred option:
   - Select **No interpretation** if you do not want to show any human-readable information
   - Select **Below** or **Above barcode** to place the human-readable information accordingly
   - Use **Custom font** to modify the font style and size if desired

## Adjusting Printer Settings

### Speed and Darkness Settings

To adjust print quality settings:

1. Select **File**, then **Printer Settings**
2. Navigate to the **Options** tab
3. Here you will find the speed and darkness settings

![Speed and Darkness](../Resources/images/zebradesigner-speed-darkness.png)

If your printout is too faint:
- Decrease the speed (lowest setting is 2"/sec)
- Increase the darkness (highest setting is 30)

## Advanced Features

### Connecting to a Database

ZebraDesigner Professional edition allows you to connect to databases for variable data printing:

1. Create the text or barcode object that will display database information
2. Right-click on the object and select **Properties**
3. In the Properties dialog, click on the **Data Source** tab
4. Select **Database** as the data source
5. Follow the Database Wizard to connect to your database

For more detailed instructions, see our [Database Printing Guide](./database-printing.md).

### Creating Variable Fields

To create fields that can change for each label:

1. Create a text or barcode object
2. Right-click on the object and select **Properties**
3. In the Properties dialog, click on the **Data Source** tab
4. Select **Keyboard Input** as the data source
5. Configure the prompt that will appear when printing

## Saving and Printing

### Saving Your Template

To save your template for future use:

1. Select **File > Save** or **File > Save As**
2. Choose a location and enter a meaningful filename
3. Click **Save**

### Printing Your Template

To print your labels:

1. Select **File > Print** or press **Ctrl+P**
2. Configure your print settings:
   - Number of labels
   - Print order
   - Printer settings
3. Click **Print** to send the job to your printer

## Troubleshooting

### Common Issues and Solutions

**Issue: Labels print with incorrect alignment**
- Solution: Double-check your label dimensions in the template setup
- Solution: Ensure your printer settings match your label stock

**Issue: Barcode doesn't scan**
- Solution: Increase the barcode size or module width
- Solution: Ensure adequate quiet zones around the barcode
- Solution: Adjust print darkness settings

**Issue: Text appears cut off**
- Solution: Reduce text size or font weight
- Solution: Adjust text margins or positioning

## Additional Resources

- [ZebraDesigner Official Documentation](https://www.zebra.com/us/en/support-downloads/software/design/zebradesigner.html)
- [GA International Formatting Appendix](https://cdn.labtag.com/wp-content/uploads/GA-International-Appendix-EN012020-January-28-2020.pdf)
- [Database Printing Guide](./database-printing.md)
- [Printer Settings Guide](./printer-settings.md)

---

[Back to Guides](./index.md) | [Software Guides](./software-guides.md) | [FAQ](../Resources/faq.md) 