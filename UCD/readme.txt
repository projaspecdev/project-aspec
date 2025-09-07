         GT2UsedCarEditor v1.0
=================================================================
	 by pez2k
=================================================================

A tool to edit the available stock in the Used Car Dealerships in
Gran Turismo 2.

=================================================================

How to use:

Extracting:
Drag any one of the .usedcar files onto the tool to extract the
used car lists into a folder. The lists are categorised into
folders based on the day they become available (Day 0 through Day
590), then by manufacturer. Each CSV file contains a list of each
car ID followed by the price and the ID of the car colour shown.

Rebuilding:
Drag the output folder onto the tool to rebuild into the original
game file. This will overwrite the original file with no prompt.

Notes on editing:
MS Excel will often mangle CSV files, it's recommended to just
use Notepad to edit them.
The maximum value for the price is 16,777,215 credits.
The colour ID can be found in the header of the CDP file for the
car, and is exactly one hexadecimal byte. An invalid value will
be interpreted by the game as the first colour for that car.

=================================================================

Requirements:

.NET Framework 4.7

=================================================================

Credits:

Code: pez2k
Research: adeyblue
CsvHelper: Josh Close

=================================================================

THE END