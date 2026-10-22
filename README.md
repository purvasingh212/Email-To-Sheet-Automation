# 📧 Email to Sheet Automation

## 📌 Project Overview
Email to Sheet Automation is a workflow automation project built using **n8n, Gmail, and Google Sheets**. It is designed to automate email-related data handling and store the required information in a Google Sheet, reducing manual work.

## 🛠️ Technologies Used
- n8n
- Gmail
- Google Sheets
- OAuth 2.0 Authentication
- Workflow Automation

## ⚙️ How It Works
1. The n8n workflow processes the configured email input or trigger.
2. The required information is extracted or prepared.
3. The data is added to Google Sheets using the Append Row operation.
4. The spreadsheet stores the records for easy access and tracking.

## 🚀 Setup Instructions
1. Download the workflow JSON file from this repository.
2. Open your n8n instance.
3. Import the JSON workflow into n8n.
4. Connect your own Gmail and Google Sheets credentials.
5. Select the appropriate spreadsheet and worksheet.
6. Test the workflow with sample data before activating it.

## 🔐 Security
- Do not share OAuth client secrets, access tokens, or passwords.
- Configure your own credentials in n8n.
- Avoid uploading personal or confidential data.

## 🎯 Project Goal
To demonstrate how workflow automation can connect email services with Google Sheets and reduce repetitive manual data entry.

## 👩‍💻 Author
Purva Bhadoria

