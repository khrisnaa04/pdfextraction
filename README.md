# Automated PDF Data Extraction to Excel Using Microsoft AI Builder
This repository documents a Power Automate flow designed to automate the extraction of structured data from PDF files using `Microsoft AI Builder`.
> Note: This repository is for documentation and portfolio purposes only. No actual flow files or sensitive business data are included.

## Use Case
This automation streamlines document processing by allowing users to submit PDF files through a `Microsoft Form`. The flow then extracts relevant data using AI Builder and stores the result into a shared Excel sheet.  

## Requirements
- Microsoft Power Automate
- Microsoft Forms
- Microsoft AI Builder
- Excel Online (Business)
- OneDrive / SharePoint

## Flow Overview
1. **Trigger**: `Microsoft Form` submission.
2. **Retrieve file** from the form response.
3. **Send file to AI Builder** to extract fields.
4. **Write extracted data** into a shared Excel Online (OneDrive/SharePoint) spreadsheet.

## File Structure
```sh
📂 pdfextraction
│─ 📂 assets
  │─ pdf-extraction-flow.png
  │─ pdf-extraction-usecase.png
│─ LICENSE 
│─ README.md
```

## Notes
- No confidential data is included in this repository.
- The AI model used in this project was trained on dummy/sample data only.
- All connections are handled securely within the Microsoft ecosystem.
- Using AI Builder in Power Automate requires a premium license or a Microsoft 365 environment with AI Builder credits. Make sure your organization has the appropriate subscription to access AI capabilities.

## License
This project is shared under the MIT License for educational and showcase purposes.
