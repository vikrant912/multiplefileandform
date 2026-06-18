#multiple file and forms 
Step 1: Prepare Your Word Template

Create a Word document called template.docx.

Put placeholders where values should change:

Employee Name: {{NAME}} Serial Number: {{SERIAL}}

Save it as:

template.docx Step 2: Create Excel File

Create data.xlsx:

NAME SERIAL Vikrant ABC123 Amar XYZ789 John DEF456 Step 3: Install Python Libraries pip install pandas openpyxl python-docx Step 5: Run It python generate_docs.py
