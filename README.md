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
Currently, the path to the csv file is hard coded in the script. The csv file needs to be in the same folder as the script.
This will be fixed.
