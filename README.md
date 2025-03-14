# File Converter Web App

This web application converts PDF and Excel files to Word documents (DOCX) while preserving the original layout, including tables, images, and graphs. The converted files are then emailed to the user.

## Requirements

- Flask
- pdf2docx
- openpyxl
- pandas
- smtplib

## How to Run

1. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python app.py
   ```

3. Use a tool like Postman to send a POST request to `/convert` with the file to be converted.
