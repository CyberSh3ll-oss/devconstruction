Dev Construction – Bill Maker

A simple, offline web app that generates professional construction bills as downloadable JPEG images.

Fill in the bill date and the work items, and the app creates a ready-to-use bill with your company details, customer information, bank details, and signature already filled in.

Features





Live preview – See exactly how the bill will look while you type



Multiple line items – Add up to 8 work descriptions with amounts



Automatic totals – Grand total is calculated for you



One-click download – Saves a high-quality JPEG of the bill



Fixed company branding – Company name, address, GST, customer details, bank info, and signature stay the same on every bill



Works offline – Pure HTML + JavaScript, no server or internet required after opening the file



Print-friendly layout – Clean professional design with proper spacing and typography

How to Use





Open index.html in any modern browser (Chrome, Firefox, Edge, Safari).



Step 1: Choose the bill date.



Step 2: Enter the work done and the amount for each item.
Click + Add another item if you need more lines (maximum 8).



Step 3: Click Download Bill (JPEG picture).
The image is saved to your Downloads folder as Bill_DD-MM-YYYY.jpg.

The preview on the right updates in real time as you type.

Fixed Details (never change from bill to bill)







Field



Value





Company



DEV CONSTRUCTION





Address



MAIN BAZAR, NILESHWAR 671314





Contact / GST



PH: 9847185615, GST – 2GNFPK5825R1ZE





Customer



APPUSSAMI PVT LTD





Customer Address



EK TOWER MARKET JUNCTION, NILESHWAR, PIN 671314





Customer GSTIN



32AAXCA7665H1Z5





Bank



SOUTH INDIAN BANK, NILESHWARAM





Account



0766073000000207 (VIJITH K P)





IFSC



SIBL0000766

Signature is embedded in the bill image.

Technical Notes





Single-file application (index.html)



Canvas-based rendering for the bill preview and export



Uses the EB Garamond web font for a classic look



Amounts are formatted in Indian style (e.g. 1,03,000/-)



No external dependencies except the Google Fonts stylesheet (optional – the app still works offline with system fonts)

Customization

All fixed text is stored in the CONFIG object near the top of the <script> section.
To change company name, address, customer, bank details, or signature, edit the values there and replace the base64 signature image if needed.

const CONFIG = {
  companyName:   "DEV CONSTRUCTION",
  addressLine:   "MAIN BAZAR, NILESHWAR 671314",
  // ... etc
};

Browser Support

Works in all modern browsers that support the HTML5 Canvas API and ES6 JavaScript.



Built for quick, professional billing for Dev Construction.
