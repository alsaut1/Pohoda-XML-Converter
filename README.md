# Pohoda-XML-Converter
CSV to XML converter for Pohoda accounting software. Client-side only, no data upload.
Pohoda XML Converter
CSV/TXT to XML converter for importing EET Pokladna (electronic cash register) data into Pohoda accounting software (Czech Republic).
What it does

Reads CSV files exported from EET Pokladna applications
Converts to Pohoda XML format (issued invoices)
Automatically calculates VAT 21% (DPH)
Groups line items by document numbers
Filters out cancellations and invalid records

Perfect for
Ideal for businesses using EET Pokladna applications (electronic cash registers) who need to import sales data into Pohoda accounting:

Campings & Hotels - accommodation and additional services
Restaurants & Cafes - daily sales from POS systems
Retail Shops - bulk import of cash register data
Service Businesses - any EET-compliant cash register exports

How to use

Open the HTML file in any web browser
Select your CSV/TXT file with sales data
Click "Convert to XML" button
Download the generated XML file
Import the XML into Pohoda software

Data format expected
The converter expects CSV files exported from EET Pokladna applications with these columns:
datetime, number, sum, name, price, amount, vat, sumLine, stornoNumber, isEet
Example from EET Pokladna export:
25.05.2024 17:53:16,560,750,chatka 2 os.,750,1,21,750,,1
11.06.2024 18:06:14,561,200,parcela,100,1,21,100,,1
Security & Privacy

Client-side only - runs entirely in your browser
No data upload - files are NOT sent to any server
Local processing - all data stays on your computer
Works offline - no internet required after loading
No tracking - completely private

Technical details

Language: Vanilla JavaScript (ES6+)
Dependencies: None
Browser support: All modern browsers (Chrome, Firefox, Safari, Edge)
File formats: CSV, TXT with comma delimiters
Output: Pohoda XML schema version 2.0

Installation
No installation required! Just download and open the HTML file.
Option 1: Download

Download pohoda_converter.html
Open in any web browser
Start converting

Option 2: Use online
Visit the hosted version: [Add your URL here]
Features

Camping-optimized - handles accommodation services perfectly
VAT calculation - automatic 21% VAT computation
Bulk processing - converts hundreds of records at once
Data validation - filters invalid and cancelled transactions
Responsive design - works on desktop and mobile
Czech compliance - follows Pohoda XML standards

Example use cases

EET Pokladna → Pohoda: Convert electronic cash register exports to accounting format

Contributing
Contributions are welcome! Please feel free to submit issues and pull requests.
License
MIT License - see LICENSE file for details.
Support
For issues and questions, please use the GitHub issues page.
