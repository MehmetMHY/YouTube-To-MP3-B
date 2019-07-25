Program: YouTube To Mp3 - B
Date:    7-18-2019
By:      Mehmet Yilmaz + youtube-dl

# Description:
A simple terminal console program that allows you to create,
a list of youtube URL links. Then, convert those URL links
to mp3 files. As this is a YouTube to mp3 converting program.
This is all possible thanks to youtube-dl, I simply gave it
the option of adding lists of URL links well at the same time
create an OK-ish UI though the terminal.

# Important:
1) This code only really works on MacOS.
2) This code is a Terminal Console program.
3) This code can work with Ubuntu/Linux, but some
   changes need to be made.
4) All MP3 Files are stored in MP3_Files dir.

# Requirements:
  -MacOS
  -Python3
  -Brew
  -youtube-dl  :  https://github.com/ytdl-org/youtube-dl

# How to Install:
1) Read the README
2) Run the install-yam.sh bash script in the terminal
3) Follow the steps stated after executing install-yam.sh
4) Click on ytm.command to run

# How to Use:
(1) ADD:          Takes you a loop where you can add as many YoTube URLs as you want.
(2) CONVERT:      Uses youtube-dl on all the links you added in ADD.
(3) EXIT:         Closes over all program.
(4) REFRESH:      Cleans programs directory, use it before closing program. Also clears links.txt file.
(5) VIEW LIST:    Prints out all the URLs you entered.
(6) README:       Prints out README.
(7) VIEW EXPORTS: Prints out all the MP3 files in the MP3_Files folder.

# Other Notes:
  -Please only use and move around ONE ytm.command for this program!

# What Each Part Does: (as of 7-19-2019)
YTMB-OTHER      = Folder of old stuff I made and just kept. Not part of code!
install-ytm.sh  = Used to install over all code.
links.txt       = Used to store YouTube URL Links.
main_run.sh     = Main Bash Script for the code as a whole.
MP3_Files       = Where the MP3 Files are stored after downloading.
music_run.py    = Python script used as part of downloading process.
print.py        = Python script to print non-UI for the code.
README.txt      = README Text File.
ytm.command	 = Used to execute overall program anywhere.

# Useful Links:
1) https://github.com/ytdl-org/youtube-dl
2) https://stackoverflow.com/questions/8409946/how-do-i-make-this-file-sh-executable-via-double-click
3) https://apple.stackexchange.com/questions/20104/how-do-i-execute-command-line-scripts