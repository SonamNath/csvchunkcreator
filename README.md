# **CSV-CHUNK-CREATOR**
The CSV Data Chunking and Cleaning project focuses on efficiently handling and organizing data from CSV files. The main objective of this project is to import a CSV file, clean the data, and divide it into manageable chunks, which are then stored in multiple CSV files.

# **Project Goals**

    A. Data Import: The project begins by importing a CSV file, which typically contains information such as first names, last names, email addresses, and phone numbers.

    B. Data Segmentation:

        1. The imported data is divided into two separate dataframes: one for emails and another for phone numbers.
  
        2. The Email DataFrame includes first names, last names, and email addresses. It is processed to remove blank values and duplicates, ensuring that the email data remains clean and concise.

        3. The PhoneNumber DataFrame includes first names, last names, and phone numbers. This dataset is carefully processed to:
  
              3.1. Remove blank values.
    
              3.2. Standardize phone numbers to ensure that they have 10 digits.
    
              3.3. Eliminate any 12-digit numbers by removing the '91' prefix.
    
              3.4. Ensure that the dataset contains only numeric, 10-digit phone numbers without any alphabets or special characters.
    
    C. Data Chunking: After the data cleaning process, both the Email and PhoneNumber DataFrames are divided into smaller, more manageable chunks. Each chunk typically contains a specified number of records (e.g.,300 records per chunk).
    
    D. File Distribution: These smaller data chunks are then distributed across multiple CSV files. For instance, each chunk of email data and phone number data is saved in separate CSV files. This ensures that the data is organized into easily accessible and structured files.

### **Key Benefits**

* Improved Data Quality: The project enhances data quality by removing duplicates, blank values, and inconsistent phone number formats.
* Data Segmentation: Data is efficiently separated into relevant categories (emails and phone numbers).
* Scalability: The project can handle large datasets by breaking them into smaller, more manageable chunks.
* Data Organization: The segmented data is stored in multiple CSV files, making it easy to work with and analyze.

### **Use Cases**

* E-commerce: Organizing customer contact data for marketing campaigns.
* Logistics: Managing contact information for shipments and deliveries.
* Analytics: Preprocessing data for further analysis and reporting.
  
In summary, the CSV Data Chunking and Cleaning project is a versatile tool that streamlines the process of importing, cleaning, segmenting, and storing data from CSV files. It is designed to improve data quality and ease the analysis of large datasets, making it valuable for a range of industries and applications.
