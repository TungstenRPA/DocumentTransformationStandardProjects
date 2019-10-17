# Document Transformation Standard Projects 10.7.0
Enhancements to the Standard Projects delivered with Kofax RPA Document Transformation

## Addresses
Uses the Address Locator to detect US addresses on a document. 
* It returns up to 20 Addresses in a table field with the columns Name, Address, City, State, Zip, Confidence.
## Barcodes
Uses the Barcode Locator to find one on a document.
* It searches for any kind of 1D or 2D barcode, and returns the first found.
## Invoices_SalesTax
Reads standard invoice data and table line items from a US invoice.
## Invoices_VAT
Reads standard invoice data and table line items from a UK, German, French or Spanish invoice.
## OCR
Performs OCR in English on a document
## Sentiment
Returns the sentiment score of a document. -1.0 for very negative,  0.0 for neutral and 1.0 for very positive.
## Languages
Determines the language of a document
* supports 30 languages, including Arabic, Greek and Slavic languages.
* The OCR engine is only configured for English - you need to add other alphabets as required.
