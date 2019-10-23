# CRV-MP3
Transcodes MP3 and M4A files to a format suitable for use on the MP3 player on a 2009 Honda CR-V.

To use the software, you'll need to install FFMPEG and LAME. The CRV-MP3 script is designed to work on OSX, so it points to usr folders that contain the FFMPEG and LAME executables. If you're using a Windows machine, you'll have to point to the appropriate folders on your system. 

The software reads in MP3 and M4A files in the Original folder, transcodes them, and writes the transcoded files to a Recoded folder. FFMEG is used to decode M4A files, and LAME is used to encode MP3 files.

Here's an example of how to use the software.
* Install FFMPEG and LAME
