# CRV-MP3
The Honda CR-V media player circa 2009 is very picky about the MP3 formats it can play, and it can't play M4A files at all. This software transcodes MP3 and M4A files to a format suitable for use on the MP3 player on a 2009 Honda CR-V. 

To use the software, you'll need to install FFMPEG and LAME on your system. FFMEG is used to decode M4A files, and LAME is used to encode MP3 files.

The CRV-MP3 script is designed to work on OSX, so it points to usr folders that contain the FFMPEG and LAME executables. If you're using a Windows machine, you'll have to point to the appropriate folders on your system. 

The software reads in MP3 and M4A files in the Original folder, transcodes them, and writes the transcoded files to a Recoded folder. M4A files are coded to MP3 and MP3 files are recoded to an MP3 format the CR-V media player can handle.

Here's an example of how to use the software.
* Install FFMPEG and LAME (you may need to install the LAME MP3 engine).
* Check the crv-mp3 file and make sure the constants FFMPEG2 and LAME point to the correct folder on your system (they are correctly set up for OSX).
* Create an Original folder in the same folder as the crv-mp3 folder.
* Copy your MP3 and M4A files to the Original folder, so it might look something like this:

* Now, execute the script:

* At the end of the process, you should see:
