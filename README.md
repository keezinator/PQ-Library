# PQ-Library
A method to create a library of powerquery functions that are automatically loaded into any Excel workbook connected to the library

## Install
* Copy the content of this repo into any location on you harddrive
* run the ".....ps1" power**script** file to initialize you power**query** library in the default location (your XLSTART folder)

## Using the library
* Place any PowerQuery scripts in the XLSTART/PQ Libraray folder as files with a .pq extension
* Copy the script "M" from the XLSTART/PQ Library Manager.xlsx into any workbook
* Refresh the #"M" query: This returns a record with the result of all the queries as fields, with the field name equal to the file name of the script without extension
* Refer to any of the library queries with the syntax M[Your Query Name Here]
* So calling a function goes like: M[Your Function Name Here](paremeter1, parameter2)
* Remember! M is case sensitive: use the exact name (without extension) of the .pq file.

## Planned for future releases
* Provide the library manager as a plugin to automate linking the PQ Library to you workbook
* Additional .pq files for your use
* Support for A direct link to this github repo, so you can always have the latest release.
