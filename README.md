# 📇 A4 ID Card Grid

A beautiful, modern web application for creating printable ID card grids on A4 paper. Upload your ID card images, edit them with precision, and generate print-ready PDFs.

![ID Card Grid](https://img.shields.io/badge/Format-A4-maroon?style=for-the-badge) ![Card Size](https://img.shields.io/badge/Card-CR80%20Standard-gold?style=for-the-badge)

---

## ✨ Features

### 🎨 **Professional Design**
- Modern maroon & gold theme with glassmorphism effects
- Responsive layout that works on desktop and mobile
- Smooth animations and hover effects

### 🖼️ **Smart Image Editor**
- **Crop Mode**: Maintain perfect ID card aspect ratio (1.58:1)
- **Warp Mode**: Adjust corners independently for perspective correction
- Real-time magnifier for precise adjustments
- Drag to reposition, arrow keys for fine-tuning

### 📄 **Flexible Grid Layout**
- 4×2 grid (8 cards per A4 sheet)
- Front and back card support
- Individual card editing by clicking
- Bulk upload for all fronts or backs

### 🖨️ **Print & Export**
- High-quality PDF generation
- Browser print preview
- Cutting guides for easy separation
- Black & white conversion option

---

## 🚀 Getting Started

### **Quick Start**
1. Open `index.html` in any modern web browser
2. No installation or server required!

### **Usage**

#### **Method 1: Bulk Upload**
1. Click **"Front Side"** to upload an image for all front cards
2. Click **"Back Side"** to upload an image for all back cards
3. Use the image editor to crop or warp your image
4. Click **"Apply Changes"**

#### **Method 2: Individual Cards**
1. Click on any card placeholder in the grid
2. Upload an image for that specific card
3. Edit and apply

#### **Editing Tools**
- **Crop Mode** (Default): Maintains ID card proportions
  - Drag corners to resize
  - Drag the center to reposition
  - Use arrow keys for pixel-perfect adjustments
  
- **Warp Mode**: For perspective correction
  - Move each corner independently
  - Perfect for photographed cards

#### **Export Options**
- **Download PDF**: Generate a high-quality PDF file
- **Print Preview**: Use browser's print dialog
- **Reset Grid**: Clear all cards and start over

---

## 🎯 Use Cases

- **Schools & Universities**: Student ID cards
- **Events**: Conference badges and passes
- **Businesses**: Employee ID cards
- **Organizations**: Membership cards
- **Personal**: Custom cards for any purpose

---

## 🛠️ Technical Details

### **Built With**
- Pure HTML5, CSS3, and JavaScript
- No frameworks or build tools required
- External libraries:
  - [html2canvas](https://html2canvas.hertzen.com/) - For PDF generation
  - [jsPDF](https://github.com/parallax/jsPDF) - PDF creation
  - [Font Awesome](https://fontawesome.com/) - Icons
  - [Google Fonts (Inter)](https://fonts.google.com/) - Typography

### **Browser Support**
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

### **Smart Card Specifications**
- **Standard**: CR80 / ID-1 (ISO/IEC 7810)
- **Dimensions**: 85.6mm × 53.98mm (3.375" × 2.125")
- **Aspect Ratio**: 1.586:1
- **Thickness**: Standard 0.76mm (30 mil)
- **Corner Radius**: 3.18mm (1/8")
- **Grid Layout**: 2 columns × 4 rows = 8 cards per A4 sheet
- **Paper Format**: A4 (210mm × 297mm)
- **Output Resolution**: 1011×638px per card (high quality)

**Common Card Types Using CR80 Standard:**
- Credit/Debit Cards
- Driver's Licenses
- National ID Cards
- Employee ID Badges
- Student ID Cards
- Access Control Cards
- Membership Cards
- Library Cards

---

## 📱 Features Breakdown

| Feature | Description |
|---------|-------------|
| **Responsive Design** | Works on desktop, tablet, and mobile |
| **Black & White Mode** | Toggle grayscale filter for printing |
| **High Resolution** | 1011×638px output per card |
| **Cutting Guides** | Dashed lines for easy card separation |
| **Toast Notifications** | User-friendly feedback messages |
| **Keyboard Shortcuts** | Arrow keys for precise positioning |

---

## 💡 Tips for Best Results

1. **Image Quality**: Use high-resolution images (at least 1000px wide)
2. **Lighting**: Ensure even lighting on photographed cards
3. **Alignment**: Use the warp tool to correct perspective distortion
4. **Preview**: Always check print preview before printing
5. **Paper**: Use thick cardstock (200-300gsm) for durability

---

## 🎨 Customization

The application uses CSS custom properties for easy theming. Edit the `:root` section in the `<style>` tag:

```css
:root {
    --primary: #800000;       /* Maroon */
    --accent: #d97706;        /* Gold */
    --success: #059669;       /* Emerald */
    /* ... more variables */
}
```

---

## ‍💻 Developer

**Developed with 𖹭 by Arslan**

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

## 📞 Support

If you encounter any issues or have questions:
1. Check that you're using a modern browser
2. Ensure JavaScript is enabled
3. Try clearing your browser cache
4. Verify image file formats (JPG, PNG, WebP supported)

---

## 🔄 Version History

- **v1.0** - Initial release with crop and warp editing modes

---

**Happy Printing! 🎉**
