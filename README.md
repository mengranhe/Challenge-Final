**matching.R**
matching function: take signatures of snippets, a threshold w, and the number of matches to be returned

**signature.R**
convert audio file into signal and calculate window signatures (only .wav format)

**tasks.R**
contains functions of three tasks: add song information and its signatures into database, list song information, and identify audio file

**testing.R**
unit testing for important functions

**shazam_add.R**
command line driver for task adding song information and its signatures into database

**shazam_list.R**
command line driver for task listing song information

**shazam_identify.R**
command line driver for tasking identifying audio file (.mp3 and .wav format)

`source(psqlConnet.R)` is to load library(RpostgreSQL), log into server and define variable song_data containing all the songs' signatures. 
