# Advanced Pro Bodice Drafter & 3D Mannequin

A web-based professional bodice pattern drafting tool that generates a customized **2D sewing pattern** and **3D mannequin representation** from body measurements.

The application is designed to make custom bodice drafting easier, faster, and more accurate while providing both digital visualization and printable pattern layouts.

## ✨ Features

### 📏 Body Measurements

Enter body measurements in centimeters, including:

- Upper Bust
- Full Bust
- Under Bust
- Waist
- Hip
- Nape to Waist
- Armhole Depth
- Waist to Hip
- Additional proportional measurements

Each measurement includes a short description to help users enter the correct value.

### 📐 2D Pattern Generation

The application generates a customized bodice pattern based on the entered measurements.

The pattern can include:

- Bust shaping
- Waist shaping
- Darts
- Armhole construction
- Neckline
- Shoulder slope
- Bust level
- Waist level
- Construction guides
- Measurement annotations

### 👗 3D Mannequin Visualization

A 3D representation allows users to visually inspect the generated proportions, including:

- Bust volume
- Waist shape
- Body proportions
- Garment shaping
- Front and side contours

### 🖨️ Printable Pattern

The application provides a print layout for creating a physical sewing pattern.

Supported workflow:

- Preview the print layout
- Select the intended paper format
- Print the generated pages
- Assemble the pages into the complete pattern

### 🌎 English / Spanish

The interface supports bilingual use:

- 🇺🇸 English
- 🇲🇽 Spanish

## 🖥️ Interface

The application provides three main views:

1. **View 2D Pattern** — displays the drafted bodice pattern.
2. **View 3D Mannequin** — displays the corresponding 3D body/mannequin representation.
3. **View Print Layout** — prepares the pattern for printing.

The measurement panel contains the user's body measurements and drafting parameters.

## 🎯 Project Goal

The goal of this project is to transform body measurements into a customized bodice drafting system.

Traditional pattern drafting requires manual calculations and construction. This application aims to simplify that process by calculating proportions automatically and presenting the result as both a 2D pattern and a 3D visualization.

### Workflow

```text
Body Measurements
       ↓
Measurement Calculations
       ↓
Pattern Drafting
       ↓
2D Bodice Pattern
       ↓
3D Mannequin
       ↓
Printable Pattern
```

## 🧮 Pattern Generation

The entered measurements are used to calculate the geometry of the bodice.

Depending on the implementation, measurements can determine:

- Pattern width
- Bust placement
- Waist position
- Armhole depth
- Dart positioning
- Shoulder dimensions
- Neckline dimensions
- Body curvature
- Bust projection
- Overall proportions

The resulting geometry is rendered in the application's visualization system.

## 📝 How to Use

1. Open the application.
2. Enter the required body measurements.
3. Make sure measurements use centimeters.
4. Review the generated 2D pattern.
5. Open **3D Mannequin** to inspect the shape and proportions.
6. Open **Print Layout** to prepare the pattern.
7. Print the generated pattern.
8. Assemble the printed pages if required.

## 📊 Example Measurements

```text
Upper Bust:       88 cm
Full Bust:        92 cm
Under Bust:       76 cm
Waist:            70 cm
Hip:              96 cm
Nape to Waist:    41 cm
Armhole Depth:    21 cm
```

These values are examples only and can be replaced with measurements for an individual user.

## 🔮 Future Improvements

- [ ] More advanced body measurements
- [ ] Back bodice generation
- [ ] Sleeve pattern generation
- [ ] Skirt pattern generation
- [ ] Pants pattern generation
- [ ] Adjustable bust projection
- [ ] Automatic dart manipulation
- [ ] Seam allowance options
- [ ] A0/A1/A2/A3/A4 printing support
- [ ] PDF export
- [ ] SVG export
- [ ] DXF export for CAD systems
- [ ] Saved customer profiles
- [ ] Measurement history
- [ ] Multiple body types
- [ ] Automatic pattern grading
- [ ] Fabric consumption calculations
- [ ] Improved 3D fitting simulation

## ⚠️ Accuracy Disclaimer

This application is intended as a digital pattern drafting and visualization tool.

Generated patterns should be checked against the user's actual measurements and, when necessary, tested using a muslin/toile before producing the final garment.

Body shape, posture, bust projection, ease, fabric characteristics, and drafting methodology can affect the final fit.

## 🛠️ Technologies

Potential technologies used by the project include:

- HTML5
- CSS3
- JavaScript
- SVG
- Canvas
- WebGL
- Three.js
- PDF generation libraries


**Advanced Pro Bodice Drafter & 3D Mannequin**

A digital approach to custom pattern drafting, visualization, and printable sewing patterns.
