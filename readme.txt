A tool for extracting/modifying the files of the Elite Penguin Force DS games.


Current features:

Opening and editing ARC files (Both EPF and HR)
Opening and editing RDT files (EPF. HR is viewing/exporting only, and lacks filenames)
Opening and editing TSB/MPB files. (Both EPF and HR)
Exporting and reimporting LUA scripts.
Editing save files. (Both EPF and HR)
Dumping audio clips to wav
Exporting and replacing music tracks in .XM format (you will then need to convert these to midi with OpenMPT or similar to actually listen to them, as the XM files have no sample data.)

The music replacing also currently has issues with some tracks (e.g. Dojo and Gadget Room, among others)

With thanks to
Fireboyd78 for creating a C# port of unluac (originally by tehtmi)
No$GBA for its invaluable debugging tools
DSDecmp and Ekona for their LZ10/11 compression features