# kicad-jlcpcb-tools-qty-extractor

Intended for use with https://github.com/Bouni/kicad-jlcpcb-tools.
Unfortunately the tool does not include a quantity column in it's BOM .csv output files.
Thus it is not possible to order the BOM items from LCSC.
This small script reads the BOM file, processes it by adding a quantity column and saves the new file.

# Dependencies
Recent version of Python 3
## Python packages
pandas
### How to install:
pip install pandas

# Usage
I run the script in VS code.
When runing the script, an open file dialog opens.
Pick your BOM .csv file that kicad-jlcpcb-tools generated.
Now the script processed the file and saves the processed file in the original file's directory.
You can now upload this file via LSCS' BOM tool. :)
