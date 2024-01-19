Student ID: 5582852
Module code: IB96D0
Module title: Programming Solutions for Enterprise 

# Project title:
IB96D0 Assignment. 

# Project overview:
This Python program is designed to analyse multiple PDF files, searching for user-specified keywords and counting their occurrences. 
It extracts text from each provided PDF file, counts the frequency of each keyword, and compiles the results. 
Additionally, the program offers the functionality to email these results to a specified recipient.


# Installation
Before running the program, ensure you have Python installed on your machine. Then, install the necessary package:

`pip install PyPDF2`



# Usage Instructions

## Run the Program
Execute the script in your Python environment.

## Enter Keywords
When prompted, input the keywords you want to search for in the PDF files. Type 'stop' to finish entering keywords.

## Provide PDF File Paths
Enter the paths to the PDF files you wish to analyse. Type 'stop' to finish entering file paths.

## Review Results
The program will process each file and display the count of each keyword on the console.

## Send Email (Optional)
Choose whether or not to send these results via email. If yes, input the receiver's email address.



# Considerations

## File format
Ensure the file paths provided end with '.pdf', as the program is designed specifically for PDF files.

## Email credentials
The script uses a hardcoded sender email and password. For security, consider implementing a more secure way to handle credentials, like environment variables.

## SSL context
The program uses SSL for secure email sending. Ensure the network and email provider support SSL connections.

## Error handling 
The program includes basic error handling, particularly for file reading and email sending processes.



# Additional Notes

## Performance
The script's performance may vary based on the size and complexity of the PDF files.

## Dependencies
The program relies on the PyPDF2 library for PDF processing and the Python Standard Library for other functionalities.
