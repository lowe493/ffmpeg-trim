# ffmpeg-trim
FFMPEG PS Script that will trim .MKV files

# Trim Videos
1. Place MKV videos into the Videos folder
2. Right Click on the Trim.PS1 file and select 'Run with powershell'
3. Videos will be trimmed into the output folder

You can change the trim ammount by editing -ss hh:mm:ss to the desired time e.g
``.\resources\bin\ffmpeg.exe -i .\videos\$file -vcodec copy -acodec copy -ss 00:00:20 ".\output\trimmed-$file"``
