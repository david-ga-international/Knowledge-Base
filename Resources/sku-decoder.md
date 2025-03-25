# LabTag SKU Decoder

[🏠 Home](../index.md) > [Resources](./index.md) > SKU Decoder

This tool helps you understand and decode LabTag product SKUs to identify the exact specifications of any product.

## SKU Structure

LabTag SKUs follow this structured format:
```
CLASS-MODEL[VARIANT]C[PRINT_METHOD]-[SIZE][COLOR]
```

## Component Breakdown

| Component | Description | Examples |
|-----------|-------------|----------|
| CLASS | Product family/class | JTTA, FJT, AWA, FTT, CIJ |
| MODEL | Specific design/size | 7, 28, 56, 115 |
| VARIANT | Special features (optional) | NP (No Perforation), SB (Special Backing), NOT (Notched) |
| PRINT_METHOD | Print format | C1 (Single across), C3 (Three across) |
| SIZE | Dimension parameter | 1, 2, 0.5 (inches or other unit) |
| COLOR | Color code | WH (White), BL (Blue), GA (Green), YE (Yellow) |

## Product Class Reference Guide

| Class Code | Product Description | Temperature Range | Primary Use |
|------------|---------------------|------------------|-------------|
| JTTA | Cryo Barcode Labels for Liquid Nitrogen Storage | -196°C to +110°C | Cryogenic vials, freezer storage |
| FJT | Deep-Freeze Labels for Thermal-Transfer Printers | -80°C to +120°C | Ultra-low freezers, general freezer |
| L2FS | Cryogenic Thermal-Transfer Labels for Frozen Surfaces | -196°C to +100°C | Already frozen samples |
| AWA | Metal Rack Labels for Barcode and Thermal Printers | -196°C to +100°C | Metal freezer racks, equipment |
| FTT | Extended Exposure Xylene & Chemical-Resistant Labels | -80°C to +120°C | Histology, solvent exposure |
| AUB | Solvent-Resistant Color Labels for Containers | -80°C to +120°C | Chemical containers, general |
| AUBR | Solvent-Resistant Color Labels for Containers | -80°C to +100°C | Chemical containers, temporary |
| AUAR | Removable Solvent-Resistant Color Labels | -80°C to +100°C | Reusable containers, temporary |
| AUTT | Autoclave-Resistant Thermal-Transfer Labels | -60°C to +150°C | Sterilization, autoclaving |
| SLPA | Permanent Labels for Autoclave & High Temperatures | -60°C to +150°C | Critical sterilization, self-laminating |
| SAUP | Steam Sterilization Indicator Thermal-Transfer Labels | -60°C to +150°C | Sterilization verification |
| SPAUTT | Autoclave-Resistant Labels with SimPEEL Technology | -60°C to +150°C | Easy application, autoclave |
| LT | Cryogenic Color Dots for Microtube Tops | -196°C to +110°C | Color coding, small containers |
| BOC | Deep-Freeze Cover-Up Labels | -80°C to +120°C | Re-labeling, error correction |
| CIJ | Cryo-JetTAG™ Inkjet Printable Cryogenic Labels | -196°C to +121°C | Color printing, Inkjet compatible |

## Special Variant Codes

| Variant | Description | Benefit |
|---------|-------------|---------|
| NP | No Perforation | Continuous label strips for special applications |
| SB | Special Backing | Enhanced adhesion for difficult surfaces |
| NOT | Notched | Easy removal from backing with tabs |
| PET | Polyester | More rigid and durable material |
| CD | Chemical Durable | Enhanced resistance to harsh chemicals |
| TE | Tamper Evident | Security feature that shows tampering |
| SL | Self-Laminating | Built-in protective layer over print |
| BO | BlackOut | Opaque material to cover existing labels |

## Print Method Codes

| Code | Description | Details |
|------|-------------|---------|
| C1 | Single Across | One label across the width of the roll |
| C2 | Double Across | Two labels across the width of the roll |
| C3 | Triple Across | Three labels across the width of the roll |
| C4 | Quad Across | Four labels across the width of the roll |
| C5 | Five Across | Five labels across the width of the roll |
| C6 | Six Across | Six labels across the width of the roll |
| C8 | Eight Across | Eight labels across the width of the roll |

## Color Codes

| Code | Color | Visual |
|------|-------|--------|
| WH | White | ⬜ |
| BL | Blue | 🟦 |
| GA | Green | 🟩 |
| YE | Yellow | 🟨 |
| PI | Pink | 🟪 (lighter) |
| RE | Red | 🟥 |
| OR | Orange | 🟧 |
| VI | Violet | 🟪 |
| MT | Metallic | ⬜ (shiny) |
| GS | Gray/Silver | ⬛ (lighter) |
| LA | Lavender | 🟪 (lighter) |
| BE | Beige | 🟫 (lighter) |
| BR | Brown | 🟫 |
| BK | Black | ⬛ |
| CL | Clear | Transparent |

## Examples Decoded

### Example 1: JTTA-7C1-1WH

| Component | Value | Meaning |
|-----------|-------|---------|
| CLASS | JTTA | Cryo Barcode Labels for Liquid Nitrogen Storage |
| MODEL | 7 | Standard rectangular cryo label |
| VARIANT | (none) | Standard version |
| PRINT_METHOD | C1 | Single label across |
| SIZE | 1 | 1 inch width |
| COLOR | WH | White |

### Example 2: JTTA-28NPC3-05BL

| Component | Value | Meaning |
|-----------|-------|---------|
| CLASS | JTTA | Cryo Barcode Labels for Liquid Nitrogen Storage |
| MODEL | 28 | Small format rectangular label |
| VARIANT | NP | No Perforation |
| PRINT_METHOD | C3 | Three labels across |
| SIZE | 05 | 0.5 inch width |
| COLOR | BL | Blue |

### Example 3: FTT-98SBC1-1YE

| Component | Value | Meaning |
|-----------|-------|---------|
| CLASS | FTT | Extended Exposure Xylene & Chemical-Resistant Labels |
| MODEL | 98 | Specific chemical-resistant design |
| VARIANT | SB | Special Backing |
| PRINT_METHOD | C1 | Single label across |
| SIZE | 1 | 1 inch width |
| COLOR | YE | Yellow |

### Example 4: CIJSA-12WH

| Component | Value | Meaning |
|-----------|-------|---------|
| CLASS | CIJSA | Cryo-JetTAG™ Inkjet Printable Cryogenic Labels |
| MODEL | 12 | Standard sheet format |
| VARIANT | (none) | Standard version |
| PRINT_METHOD | (implied) | Sheet format for inkjet printers |
| SIZE | (implied) | Approximately 0.94" × 0.5" labels on sheet |
| COLOR | WH | White (base for color printing) |

## Related Resources

- [Product Selection Guide](./product-selection-guide.md)
- [Product Comparison Charts](./product-comparison-charts.md)
- [Order Form Reference Guide](./order-form-guide.md)

---

[Back to Resources](./index.md) | [Products](../Products/index.md) | [Home](../index.md) 