# RunnerTracker
A Windows application that tracks bib numbers of runners in an Ultra-style race or run.

This application is written in Visual Studio C#.  There are two modes of operation: as an Aid Station or as the Central Database.

The Aid Station enters the bib numbers of the runners as they come in and leave (if two Log Points are being used).  This information is transferred to the Central Database via Ethernet (MESH), Packet or APRS.  Bib numbers are entered by keyboard or RFID.

The Central Database maintains the information on all the runners and aid stations.
