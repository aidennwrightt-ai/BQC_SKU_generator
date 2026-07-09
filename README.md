# BQC SKU Generator

A browser-based tool for generating Shopify-compatible SKUs, preserving barcodes, and filling Google Merchant Center fields for beauty and cosmetics products.

## Features

- **SKU Generation** — Generates SKUs in `BRAND-PRODUCT-SIZE-COLOUR` format from Shopify product exports
- **Barcode Handling** — Preserves existing EAN/UPC barcodes, attempts online lookup for missing ones
- **Google Merchant Center** — Fills GTIN, MPN, Brand, Condition, Google Product Category, Age Group, Gender, Material
- **Sub-Collection Mapping** — Map each sub-collection to a Google Product Category via dropdown
- **Shopify Reimport** — Outputs a CSV ready to reimport into Shopify (Products → Import → Overwrite)

## Usage

1. Open `index.html` in your browser (or visit the GitHub Pages URL)
2. Enter the Brand Name
3. Add Sub-Collections and assign Google Product Categories
4. Upload your Shopify product export CSV
5. Review the generated SKUs and Merchant fields
6. Download the Shopify reimport CSV

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the repository
3. Go to Settings → Pages → Source → Deploy from branch → main → root
4. Your tool will be available at `https://yourusername.github.io/repo-name/`

## No Server Required

Everything runs in the browser. No data leaves your computer — the CSV is processed locally using JavaScript.
