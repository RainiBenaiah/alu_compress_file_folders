
README

File Name: compress_folder.py

Purpose:

Compresses a specified folder into a zip, tar, or tgz archive.
Allows the user to choose the compression format.
Includes error handling for potential issues.
Installation:

Ensure you have Python 3 installed.
No external libraries are required.
Usage:

Run the script from the command line: python compress_folder.py
Enter the path to the folder you want to compress.
Select the desired compression type from the options provided.
The script will create a compressed archive with the following format:
folder_name_YYYY_MM_DD.extension (e.g., my_folder_2024_02_14.zip)
Functions:

compress_folder(folder_path, compress_type):

Compresses the specified folder using the given compression type.
Handles potential errors and provides informative messages.
main():

Prompts the user for folder path and compression type.
Calls the compress_folder function with user-provided inputs.
Compression Types:

zip: Creates a standard zip archive.
tar: Creates a tar archive (uncompressed).
tgz: Creates a compressed tar archive using gzip.
