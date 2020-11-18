# ffmpeg-trim
FFMPEG PS Script that will trim .MKV files

# Trim Start of Videos
1. Unzip Trim.Zip
2. Place MKV videos into the Videos folder
3. Right Click on the TrimStart.PS1 file and select 'Run with powershell'
4. Videos will be trimmed into the output folder

You can change the trim ammount by editing -ss hh:mm:ss to the desired time e.g
``.\resources\bin\ffmpeg.exe -i .\videos\$file -vcodec copy -acodec copy -ss 00:00:20 ".\output\trimmed-$file"``


# Trim End of Videos
1. Unzip Trim.Zip
2. Place MKV videos into the Videos folder
3. Right Click on the TrimEnd.PS1 file and select 'Run with powershell'
4. Videos will be trimmed into the output folder

You can change the trim amount by editing the $trim variable desired time in minutes
