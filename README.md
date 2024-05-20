# File Format Converter
File Format Converter is a Python project with extended Python library support Pandas.

## Tools and Technologies used in this project
- Python
- Pandas
- JSON
- PostgreSQL Database (For Files and Databases Extraction)
- VS-Code
## How to install and run this application
- Fork this Repository into your account or download a zip file for source code
- Data/ Folder contains files and database information which we will convert into **JSON** File Format.

# Steps To Follow
**Step 1.** Create a Python Virtual Environment for your project and use that environment to run this application later.

- Open the terminal and use "python -m venv <virtual-env-name>"

**Step 2.** Folder Structure before running the project

**NOTE** - retail_db is the database folder name and it contains our source files in CSV format 
![ss1](https://github.com/harshitsachdeva06/File-Format-Converter/assets/65173697/5c1d293e-73f9-445f-9d8f-f12b13eed234)

**Step 3.** Set the environment Variable in your directory for setting the path for the source directory location and target directory location where we will generate the file 
using below commands.
![image](https://github.com/harshitsachdeva06/File-Format-Converter/assets/65173697/2b57b2f2-4988-4424-bd5b-9254ecd0d8ca)

**Step 4.** Use **python app.py "parameters-optional"** to run your application
- It will create a folder "retail_db_json" which contains JSON files for all the database files that we wanted to create.
![image](https://github.com/harshitsachdeva06/File-Format-Converter/assets/65173697/ce2188c5-8b0b-4af6-8161-a35a613b1ab2)
