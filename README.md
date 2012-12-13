FluksoViz
=========

FluksoViz is a visualization of Flukso data to Android. Flukso is a energy meter, visit flukso.net

How to use this project (using Eclipse + ADT)
=============================================

First of all you need a working environment running Eclipse with ADT plug-in. I strongly suggest to
download the "ADT bundle SDK". Since this bundle comes with Eclipse pre-configured to run ADT and 
Android SDK already downloaded to latest version, this package is all you need. If you already
have Eclipse and want to install ADT on it, follow instructions at http://developers.android.com.

-> Go to http://developer.android.com, develop area and download ADT bundle SDK
-> Unpack it in you home directory (Linux users) or wherever you want to

Now, lets´s download the FluksoViz code from github (if you are reading this maybe you already did it)

-> Go to a directory of your choice (i.e. cd $HOME). Do not use Eclipse workspace directory!
-> Clone the project with git (i.e. git clone git://github.com/jrbenito/FluksoViz.git)
   This will create a directory named FluksoViz and download the project into it.

The final phase is to import the project into Eclipse (ADT will help with the trick)

-> Open Eclipse from the bundle you downloaded. (i.e. $HOME/adt-bundle-linux/eclipse/eclipse)
-> Click menu "File" then click "Import"
-> "Import" window shall open, select "Existing Android Code Into Workspace" under "Android" folder
-> Click "Next" button
-> At "Import Projects" window, click "Browse" button
-> Navigate through the filesystem selecting the folder where you cloned the project 
  (i.e. $HOME/FluksoViz)
-> Click "OK" button
-> Optionally you can check "Copy Projects into Workspace", this will copy the source folder to
   Eclipse workspace directory (i.e. $HOME/workspace). This is personal choice matter.
-> Click "Finish" button

After those steps Eclipse shall have imported the source code, and created some support files
to handle the code as a Eclipse/Android project.

Happy codding!
