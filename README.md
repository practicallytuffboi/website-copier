# website-copier

[![platform](https://img.shields.io/badge/platform-windows%2010%20%7C%2011-0078d6?style=flat-square&logo=windows)](https://github.com)
[![dependencies](https://img.shields.io/badge/dependencies-none%20(zero%20install)-brightgreen?style=flat-square)](https://github.com)
[![runtime](https://img.shields.io/badge/.net%20framework-4.0%2B%20native-blueviolet?style=flat-square)](https://github.com)
[![version](https://img.shields.io/badge/release-v1.0-orange?style=flat-square)](https://github.com)

before we get into this read below.

<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<

`webcopier` is optimized for:
- documentation sites & wikis
- blogs & portfolios.
- anything else that does not connect to a <ins>live service.</ins>

so, you might be here to clone/copy websites which is what this tool is pretty much for as you can see in the title. 

you do `NOT` need any dependencies for this since there is a `.net` runtime that is already installed on ur `windows 10/11` computer.

### how do i use this?

open <ins>webcopy.bat</ins>

paste in ur website url (https://www.example.com)

you can paste a file directory if you want to but you can just click enter. this is how a custom file directory would look like if copied, lets say you have a folder in ur downloads you would paste in 
<ins>C:\Users\USER\Downloads\FOLDERNAME/</ins>

the bundle feature is really bugged and i dont plan on fixing it for quite a bit unless needed.

you can also choose to open the website you downloaded in browser once it is fully downloaded.

quick tip, to answer these questions do Y/N (Y stands for (yes) N stands for (no)

now, it will do its thing that it's supposed to.... i mean hopefully

you should see a downloaded_sites folder if you didnt bother to change the file directory but it if you did, go to that folder directory and it should be there.

# answering questions that i made up

"what is the webcopier.exe for if it's just a .bat file?"

it's just to hide the code as if you edit the webcopier.bat, it should say this. @"%~dp0webcopy.exe" %*

basically what that does, is that if you click the webcopier.bat it redirects to ur .exe if you decide to not click the .exe and the .bat instead it wont redirect to anything. i dont know why i decided to do this and im probably going to change this in the future.
