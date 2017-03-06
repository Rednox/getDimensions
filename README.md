# Description

This is FreeCAD macro that gets chipboards dimensions to cut (or any other wood parts but has been designed for chipboards 18 mm thickness). This macro creates spreadsheet named "toCut" with all needed things to cut chipboards for your woodworking project.

# Install

1. Create new macro in FreeCAD named e.g. "getDimesions".
2. Copy exact language version of macro (e.g. getDimesionsEN.py) and paste it to your new empty macro.

# Usage

* Create chipboards:
 * Go to FreeCAD -> Part -> Create a cube solid -> Cube data (tab):
 * Set "Length" to e.g. 500
 * Set "Width" to e.g. 500
 * Set "Height" to e.g. 18
 
**NOTE**: Now you should have chipboard 500 mm x 500 mm x 18 mm. You can create whatever you like using such chipboards. Even group them in folders.

* Run macro.

**NOTE**: Now you should have spreadsheet named "toCut" with all needed dimensions.

Maybe someone will make any YouTube video tutorial about it?

# Printing

FreeCAD not support direct printing for spreadsheets. So you have to:

1. Export your spreadsheet to csv.
2. Copy the csv data to LibreOffice.
3. Convert text with tabulators in LibreOffice to the table.
4. (optional) Make some corrections (add mm and adjust table columns).
5. Print it.
6. Go and cut your chipboards to market or any other woodworking service that provide wood cutting :-)

# Make a note

* Special characters (Polish) for chipboards (object cube names) not supported.

# Available versions

* Polish version (originally designed): [getDimesions.py](https://raw.githubusercontent.com/dprojects/getDimensions/master/getDimensions.py)
* English version (ported): [getDimesionsEN.py](https://raw.githubusercontent.com/dprojects/getDimensions/master/getDimensionsEN.py)

# License

MIT
