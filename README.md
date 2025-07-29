 Invoice Validation Bot (UiPath)

This UiPath project automates the process of reading invoice PDFs, extracting GSTIN numbers and other details, validating them via a GST API, and saving consolidated results into an Excel file.
It is designed to improve efficiency, reduce manual effort, and ensure data accuracy in invoice processing.

---

 Features

 Reads and extracts data from multiple invoice PDFs
 Validates GSTIN numbers using a public/private API
 Writes validated data to a consolidated Excel report
 Sends email or message notification on successful completion
 Handles exceptions with clear logging and error reporting

---

 Project Structure
 
 Input

- PDF files containing invoice data placed in a designated folder  
- Each invoice must contain a valid GSTIN to be processed  

---

 Output

- **Excel File**: A consolidated report with extracted and validated GSTIN data  
- **Email/Log**: Process completion message or error details  

---

 Prerequisites

- UiPath Studio (2022.10 or above recommended)  
- Tesseract OCR or Document Understanding (if PDFs are scanned)  
- Internet connection for GST API validation  
- Excel installed on the system  

---


.


