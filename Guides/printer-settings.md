# Printer Speed and Darkness Settings

[🏠 Home](../index.md) > [Guides](./index.md) > Printer Settings

## Importance of Proper Print Settings

Speed and darkness settings are critical for achieving optimal print quality and durability on your labels. Proper configuration ensures:

- Crisp, readable text and barcodes
- Complete ink transfer from ribbon to label (for thermal transfer)
- Proper activation of direct thermal materials
- Maximum durability in challenging environments (chemical exposure, extreme temperatures)
- Extended printhead life

This guide explains how to adjust these settings in popular label printing software applications.

## General Recommendations

### For Standard Labels
- **Darkness/Temperature:** Default or 10-15% higher
- **Speed:** Default or manufacturer recommendation

### For Cryogenic Labels
- **Darkness/Temperature:** 20-30% higher than default
- **Speed:** 25-50% slower than default
- **Ribbon:** Resin (RR-class) recommended

### For Chemical-Resistant Labels
- **Darkness/Temperature:** 15-25% higher than default
- **Speed:** 25% slower than default
- **Ribbon:** Resin (RR-class) recommended

## Adjusting Settings in BarTender

1. After designing your label, press the **Print** button
2. Select **Document Properties** underneath your printer's name
3. Select the **Options** tab in the printer properties window
4. For darkness adjustment:
   - Uncheck **Use current printer settings** in the **Darkness** field
   - With **Relative** selected, move the bar to the right to increase darkness
   - For cryogenic labels, set to approximately 20-30 (depending on your printer model)
5. For speed adjustment:
   - Uncheck **Use current printer settings** in the **Speed Settings** field
   - Reduce the printing speed (for cryogenic labels, try 2.00-3.00 in/sec)
6. Click **OK** to save these settings
7. Proceed with printing

<div class="settings-image">
<img src="../Resources/images/bartender-settings.png" alt="BarTender darkness and speed settings dialog">
</div>

## Adjusting Settings in Zebra Designer

1. Select **File**, then **Printer Settings**
2. Navigate to the **Options** tab
3. Locate the darkness slider (typically 0-30)
   - For standard applications, set to 10-15
   - For cryogenic or chemical-resistant applications, set to 20-30
4. Locate the speed settings (typically 2-6 inches/second)
   - For standard applications, use 4-6 ips
   - For cryogenic applications, use 2-3 ips
5. Click **OK** to save settings
6. Proceed with printing

<div class="settings-image">
<img src="../Resources/images/zebradesigner-settings.png" alt="ZebraDesigner darkness and speed settings dialog">
</div>

## Adjusting Settings in Cab Label Software

1. Select the print option for your label template
2. Highlight the CAB printer in the list of available printers
3. Double-click the small icon on the far right-hand side, labeled **Configure the currently selected device**
   - Alternatively, right-click on the printer and select **Configure the currently selected device**
4. In the properties dialog box, select the **Options** tab
5. Locate the Speed and Darkness settings
6. For optimal printing of cryogenic labels:
   - Decrease the speed (the lowest setting is typically 50.8 mm/s)
   - Increase the darkness (the highest setting is typically 19)
7. Click **OK** to save the settings
8. Proceed with printing

## Adjusting Settings in Cablabel S3 Light/Pro

1. Click the **File** menu, then select **Printer Settings**
2. Navigate to the **Options** tab in the printer settings dialog
3. Locate the **Print Parameter** section
4. Adjust the **Heat** or **Energy** setting:
   - For standard labels: 8-12
   - For cryogenic or chemical-resistant labels: 14-18
5. Adjust the **Speed** setting:
   - For standard labels: 100-150 mm/s
   - For cryogenic or chemical-resistant labels: 50-75 mm/s
6. Click **OK** to save settings
7. Proceed with printing

## Testing and Fine-Tuning

After adjusting your settings, we recommend:

1. **Print a test label** with text and barcodes
2. **Visually inspect** the print quality:
   - Text should be clear with sharp edges
   - Barcodes should have clean, straight lines with no voids
   - Solid areas should be uniformly dark
3. **Test label durability** by rubbing with your finger - ink should not smudge
4. **Scan barcodes** to verify readability
5. **Make incremental adjustments** if needed:
   - If print is too light: Increase darkness by 5-10%, decrease speed by 10%
   - If print is too dark or bleeding: Decrease darkness by 5-10%, increase speed slightly

## Troubleshooting Common Issues

### Print Too Light/Faint
- Increase darkness/temperature setting
- Decrease print speed
- Verify correct ribbon type (for thermal transfer)
- Check printhead pressure
- Clean printhead

### Print Too Dark/Bleeding
- Decrease darkness/temperature setting
- Increase print speed slightly
- Check label and ribbon compatibility
- Verify correct media type in printer settings

### Inconsistent Print Quality
- Clean printhead thoroughly
- Check for even printhead pressure
- Ensure ribbon is tracking properly (for thermal transfer)
- Calibrate printer

## Additional Resources

- [Printer Calibration Guide](./printer-calibration.md)
- [Printer Technology Guide](../Resources/printer-guide.md)
- [Ribbon Selection Guide](../Products/ribbons.md)
- [Troubleshooting Common Printing Issues](../Resources/printing-troubleshooting.md)

---

[Back to Guides](./index.md) | [Printer Technology Guide](../Resources/printer-guide.md) 