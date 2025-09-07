         GT2DataSplitter v0.8.0
=================================================================
	 by pez2k
=================================================================

A tool to convert the carparam files in Gran Turismo 2 to and
from CSV. These files contain all of the physics, parts and
event data.

Please note that, as more columns in the carparam data are
researched and mapped to CSV each version, no guarantee is given
for backwards or forwards compatibility of CSV files between
versions of this tool.

=================================================================

How to use:

Place the following GT2 files in the same directory as the exe,
for a given language (eng / fra / ger / ita / spa / jpn / usa):
<language>_gtmode_data.dat.gz
<language>_gtmode_race.dat.gz
<language>_unistrdb.dat.gz

Drag any one of the above files onto the exe to convert to CSV.

Run the tool with no arguments to convert the CSV files back to
gzipped DAT files.

Please note that tens of thousands of CSV files will be created,
which may be very slow, especially on a a mechanical hard disk.

=================================================================

Requirements:

.NET 6.0

=================================================================

Credits:

Code: pez2k, adeyblue (GT2DataExploder structs)
Research: pez2k, adeyblue (GT2DataExploder), Xenn, Submaniac

=================================================================

THE END