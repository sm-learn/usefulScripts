Useful Scripts
=============

Useful general purpose scripts written in Bash or Python

ang\_pol 
-------------
Script which connects to internet dictionary and translate word from English to
Polish

<b>Usage:</b>
   ```ang_pol <englishWord>```
* <i>englishWord</i> - word in English to translate

<b>Example:</b>
   ```ang_pol go ```
  
<b>Output of example:</b> <br>
    >> isc; pojsc; chodzic <br>
    >> (o srodkach lokomocji) jechac <br>
    >> (o nagrodzie) byc przyznanym <br>
    >> chodzic; poruszac sie; dzialac (np. o urzadzeniu) <br>
    >> odchodzic; mijac; ustepowac (np. o dolegliwosci) <br>
    >> sadzic (kat.: potoczny) <br>
    >> poloznictwo i ginekologia (kat.: medycyna) <br>

appendText
-------------
<b>Description</b>
Script gets selected number of lines from one file and append those lines to other file.

<b>Usage: </b>
  ```appendText <inputFile> <outputFile> <numberOfLines>```
* <i>inputFile</i> - files where lines should be get from
* <i>outputFile</i> - files where lines should be appended to
* <i>outputFile</i> - number of lines from inputFile which should be appended
  to outputFile
<b>Example: </b>
  ```appendText input.txt output.txt 2```
* This will copy first 2 lines from input file and will append them to output.txt

application\_controller
-------------
<b>Description</b>
Script which can assure that some application is still working. If application
crashes, this script restart it.

<b>Configuration: </b>
There are few configuration variables withing application_controller file which
should be set up:
* <i>CHECKINGPERIOD</i> - interval (in seconds) where controller check whether
  application is working 
* <i>MYEMAIL</i> - email where notification about application crash and
  restarting should be send (you have to have configured mail app to receive
  mail notifications)

<b>Usage: </b>
  ```application_controller <APPLICATION_NAME>```
* <i>APPLICATION_NAME</i> - name of application which should be checked by
  controller. 

<b>Example: </b>
  ```application_controller asterisk```

If we select asterisk APPLICATION_NAME then our script will
check if asterisk is still working. If asterisk crashes, this controller
restarts asterisk.

bkp
-------------
<b>Description</b>
Doing backup of selected file copying it and appending .bkp to the name. It
simplifying working with copies of file when we would like to override it temporary.

<b>Usage: </b>
```bkp <fileName>```
* <i>fileName</i> - name of file which should be backed up
<b>Example: </b>
```bkp input.txt```
This will copy input.txt file to input.txt.bkp, so we can test something with
input.txt file having it backed up.

change\_dependencies\_in\_debs
-------------
<b>Description</b>
Appliation allows change dependencies and version of dependencies in .deb file

<b>Usage: </b>
```change_dependencies_in_debs <debFile.deb>```
* <i>debFile.deb</i> - deb file where we would like to change dependencies

<b>Example: </b>
```change_dependencies_in_debs skype.deb```
After invoking above command application will extract skype.deb and will open
control file (file where dependencies are saved) in vim editor. You can change
those dependencies and save control file. After that, script will create
skype.deb.modified.deb containing modified dependencies.

change\_text\_in\_files
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

change\_text\_recursively
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

changeExtension
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

connectSSHFSRemoteResource
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

convertDotToPNG
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

convertHTML5Video
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

createDebKernelPackeges
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

createSVNRepository
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

disable\_enable\_touchpad
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

do\_action\_on\_files
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

do\_selected\_action\_on\_files
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

embedLogoIntoImage
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

ensureIPAddress
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

grepSelectedEnvironment
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

improveImages
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

installOpenCV
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

mailing
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

pdftojpg
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

pol\_ang
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

popup
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

prependText
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

radio
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

remove\_git\_dirs
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

remove\_svn\_dirs
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

remove\_temporary\_files
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

rst
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

sendUDPPacketToHostPort
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

telnetAndRunCommand
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

UbuCleaner
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

youtubeSearch
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

youtubeToMp3
-------------
<b>Description</b>
TODO

<b>Usage: </b>

<b>Example: </b>

<b>Output of example: </b>

