# DocuFlow Pro — Executive Accounting Document Generator

DocuFlow Pro is a revolutionary, high-fidelity client-side web application designed to help businesses manage their contacts and generate tax-compliant billing documents (Invoices, Quotations, Purchase Orders, Proformas, and Credit Notes) with ease.

Built using **HTML5**, **Vanilla CSS**, and **pure ES6 Javascript**, DocuFlow Pro features a premium, interactive dark-theme dashboard with real-time computations and styling templates.

---

## Key Features

1. **Business Profile Onboarding**: Setup your company name, registered address, VAT registration numbers, phone, email, and currency defaults.
2. **Custom Logo Uploads**: Upload corporate logos which are saved locally as Base64 strings.
3. **Interactive Document Editor**: Build document structures, add line items with adjustable tax rates (15% VAT or Exempt), and view real-time calculations.
4. **Printable A4 Mockups**: View pixel-perfect paper page previews using one of four visual themes:
   - *Minimalist Charcoal*
   - *Speco Gold Classic*
   - *Modern Indigo*
   - *Emerald Clean*
5. **Native PDF Exporting**: Use the `@media print` formatting to print or save the document as a clean PDF directly from your browser.
6. **CRM & Supplier Directories**: Keep logs of corporate contacts and track their total billed value and overdue balances.
7. **AI Accounting Assistant**: Copywrite descriptions and draft payment notices.
8. **Data Persistence**: All assets, contacts, and logs are persisted inside your browser's local sandbox (`localStorage`).

---

## Getting Started

### Local Setup
Since DocuFlow Pro is a serverless application, you can run it directly:

1. **Open File**: Double-click `docuflow-pro-dashboard.html` in any modern web browser.
2. **Serve Locally**: Start a quick server inside the root directory to support all asset features:
   ```bash
   python3 -m http.server 8000
   ```
   Then open [http://localhost:8000/docuflow-pro-dashboard.html](http://localhost:8000/docuflow-pro-dashboard.html) in your browser.
