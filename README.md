# QR-generating-by-excel
# QR Code Generator for Business Cards
This repository contains a Jupyter Notebook that can quickly generate thousands of QR codes for business cards by reading data from an Excel file. This tool is ideal for companies, events, or individuals looking to efficiently produce customized QR codes for large-scale business card distribution.
## Features
   Generates thousands of QR codes in just a few minutes.
   Reads data from Excel files, allowing for easy bulk processing.
   Customizable QR code parameters (size, color, etc.).
   Ideal for business card QR codes with details like name, contact information, company, and more.

## Prerequisites
Before using the QR code generator, you will need to install the following Python libraries:
    Pandas: For reading and managing Excel data.
    qrcode: To generate QR codes.
    openpyxl: To read and write Excel files.
![image](https://github.com/user-attachments/assets/9bf4cb44-279a-4b73-9553-aba591aa29b5)

## How to Use
# Step 1: Prepare Your Data
  Prepare an Excel file containing the data for the business cards. Each row in the Excel sheet should correspond to a unique entry for a QR code. The columns     should represent different fields such as name, contact information, email, etc.

# Step 2: Run the Program
   Open the Jupyter Notebook file.
   Adjust the path to your Excel file in the code.
   Run the notebook, and it will automatically generate QR codes for each entry in your Excel file.
Each QR code will be saved as an image file (e.g., JohnDoe_QR.png), and you can further customize the filename format in the notebook.

# Step 3: Customization
   Output Directory: By default, the QR codes are saved in the current working directory. You can modify the output directory within the notebook.
   QR Code Customization: You can customize the size, colors, and error correction levels of the QR codes. Explore the qrcode library documentation for          advanced features.





