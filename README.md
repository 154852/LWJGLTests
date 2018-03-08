# LWJGLTests

So LWJGL works which is pretty cool, but you need to be able to run it sooo...

## Step 1 - Have Java
Go to https://java.com/en/download/ and download java __1.8__ for your computer - make sure you get the right one for your operating system (Linux, Windows, Macos etc). To check it worked open an application called something along the lines of Terminal or Command Prompt and type:

`java -version` and press enter.

It should print the following:
  java version "1.8.0_131"
  Java(TM) etc...

## Step 2 - Get the jar
Download the relevant file from this repository for your operating system, put it where you can find it.

## Step 3 - find it
Open your command prompt / terminal again and type pwd and press enter. It will now print out the current location that you are reading, eg `/Users/Me`. Go to the folder in which your jar is stored by using `cd ` and the folder name you want to go to, using `cd ..` to go up one folder and `ls` to list the contents of the folder, eg:

    pwd
      Users/Me
    cd Desktop
    pwd
      Users/Me/Desktop
    cd MyFolder
    ls
      MyFile.txt
      macos.jar
      Game.app

## Step 4 - Run it
Finally type the following code:

    java -jar -XstartOnFirstThread <Your Operating System>.jar
  
Eg:
  
    java -jar -XstartOnFirstThread macosx.jar
    
## How it works
You can use your mouse to drag the corners of the rectangle.
To reset it press R.


**Also, I understand that this is a long a complicated way to lanuch something simple but I couldn't be bothered to make a launcher so... Maybe another day. :)**

**Finally, I just wanted to say that this is just a demonastration of how smooth the whole thing is, I can now easily adapt it for other purposes**
