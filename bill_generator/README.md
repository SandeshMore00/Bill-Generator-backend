# 🕉️ Jai Bhavani Bill Generator

A modern, web-based bill/invoice generator application that allows you to create professional invoices quickly and easily.

## Features

- 🔐 **Secure Login**: Protected access with user authentication
- 🕉️ **Om Sign**: Beautiful orange background Om sign with pulse animation
- ✨ **Modern UI**: Beautiful, responsive design with gradient colors
- 📝 **Complete Bill Details**: Add company and customer information
- 🛒 **Multiple Items**: Add unlimited line items with quantity and pricing
- 💰 **Automatic Calculations**: Real-time automatic calculations for:
  - Item totals (quantity × price)
  - Subtotal (sum of all items)
  - Tax calculation (percentage-based)
  - Discount application
  - Final total (subtotal + tax - discount)
- 📄 **Bill Preview**: Real-time preview of your generated bill
- 🖨️ **Print Ready**: Print-friendly layout for professional invoices
- 📱 **Fully Responsive**: Optimized for desktop, tablet, and mobile devices

## How to Run the Project

### Method 1: Using npm run dev (Recommended)

1. **Install Node.js** (if not already installed)
   - Download from [nodejs.org](https://nodejs.org/)
   - Install the LTS version

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   - The terminal will show a local URL (usually `http://localhost:5173`)
   - Open that URL in your browser
   - The page will auto-reload when you make changes

### Method 2: Direct Browser Opening

1. **Navigate to the project folder**
   - Open File Explorer
   - Go to `C:\bill_generator`

2. **Open the HTML file**
   - Double-click on `index.html`
   - OR right-click → Open with → Choose your browser

3. **That's it!** The application will open in your browser

### Method 3: Using Command Line

1. **Open Command Prompt or PowerShell**
   - Press `Win + R`, type `cmd` or `powershell`, press Enter

2. **Navigate to the project folder**
   ```bash
   cd C:\bill_generator
   ```

3. **Open in default browser**
   ```bash
   start index.html
   ```
   OR for PowerShell:
   ```powershell
   Invoke-Item index.html
   ```

## Login Credentials

To access the bill generator, use these credentials:

- **User ID**: `9224381321`
- **Password**: `9224381321`

⚠️ **Note**: If you enter wrong credentials, you'll see an error message "Wrong credentials. Please try again."

## How to Use

1. **Login**
   - Enter User ID: `9224381321`
   - Enter Password: `9224381321`
   - Click "Login" button

2. **Fill in Bill Details**
   - Enter bill number and dates
   - Add your company information (From)
   - Add customer information (To)

3. **Add Items**
   - Click "+ Add Item" to add line items
   - Enter description, quantity, and unit price
   - Items are automatically calculated

4. **Set Tax and Discount**
   - Enter tax rate as a percentage
   - Enter discount amount in dollars

5. **Generate Bill**
   - Click "Generate Bill" to create a preview
   - Review the bill in the preview section
   - Click "Print Bill" to print or save as PDF

6. **Reset**
   - Click "Reset" to clear all fields and start over

## File Structure

```
bill_generator/
├── index.html      # Main HTML file
├── styles.css      # Styling and layout (with responsive design)
├── script.js       # JavaScript functionality (with calculations)
├── package.json    # npm configuration
├── .gitignore      # Git ignore file
└── README.md       # This file
```

## Calculations

The bill generator automatically calculates:

- **Item Total** = Quantity × Unit Price
- **Subtotal** = Sum of all item totals
- **Tax Amount** = Subtotal × (Tax Rate / 100)
- **Final Total** = Subtotal + Tax Amount - Discount

All calculations update in real-time as you type!

## Browser Compatibility

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Print Functionality

The bill is optimized for printing:
- Professional layout
- Print-friendly colors
- Automatic page breaks
- Can be saved as PDF from print dialog

## Customization

You can easily customize:
- Colors in `styles.css` (look for gradient colors)
- Default values in `script.js`
- Form fields in `index.html`

## License

Free to use for personal and commercial purposes.

---

**Enjoy creating professional bills! 📄✨**

