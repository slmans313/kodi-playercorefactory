# Windows set up

Youtube video

https://www.youtube.com/watch?v=r7Funnh1veY


## 7zip

http://www.7-zip.org/


## ffmpeg

download

http://ffmpeg.zeranoe.com/builds/

unzip the ffmpeg.7zip file

rename the folder to ffmpeg

copy the ffmpeg to C:\

C:\ffmpeg\bin


you can run the ff-prompt script to set up ffmpeg with the windows cmd path

or you can manually add it


add ffmpeg path

system properties

advanced system settings

enviormnental variables

system variables

path

edit

;C:\ffmpeg\bin



## git install

https://git-scm.com/download/win

select 2nd option for path not git bash shell


download the kodi-playercorefactory git repository

create a folder called git in your home 

open the cmd prompt and change into the git repo

	cd git


then clone the kodi-playercorefactory git repository

	git clone https://github.com/NapoleonWils0n/kodi-playercorefactory.git


copy the kodi-playercorefactory\windows\playercorefactory.xml to your kodi userdata folder
see below

open your Windows Start menu and type

	%APPDATA%\kodi\userdata

then press <Enter> to open the folder, 
pin the folder to your file manager sidebar so you find it easily

then copy the kodi-playercorefactory\windows\playercorefactory.xml to your kodi userdata folder


## vlc

https://www.videolan.org/vlc/index.html


### cygwin


https://cygwin.com/install.html

add cygwin path

system properties

advanced system settings

enviormnental variables

system variables

path

edit

;C:\cygwin\bin

