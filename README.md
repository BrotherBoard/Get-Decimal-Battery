this no longer gets updates since i made a cleaner one, DBC
Included in BombScripts "Kit"

# Get-Decimal-Battery
Show a shell notification of your decimal battery level.

**Tested on the Galaxy A10 running Android 13 Arm64**

To start
do `bash DecimalBattery` in some terminal to proceed

The script might do some optional commands, it will prompt you with them.

this is not a scam, I made this for fun but it's useful for me
because I do like to see my charging level increases 10 times
more precise, as an example, if you want to test your charger
speed, then if you need to watch it for 100 seconds, you can
watch it for only 10 seconds with this script, lol.

**Version history**

v6.0
abandoned current repo, the new DecimalBatteryClean works like a charm, with no packages required.

v6.0 beginning of the clean code
for now it stopped making that "helper" file, insyead now it
echos to the var directly, i will start working on using
the bashrc file of termux instead of making files such as
.locator in internal
and the directory DecimalBatteryFiles in internal
and its files, next version 6.1 will not touch your internal, but
thats some work ok

v5.9 visual improvements
now drops an error explaining it failed to find file, if no root
and/or not not permissive (on some devices permissive is required
to access system), besides imrpoving something else also i forgot
lmao.

v5.8 new features
now shows time every time you request in textonly,
besides that I added a drop calculator to know
how much did you battery drop and in how much seconds.

v5.7 Added enforcing toggle
since script will enable permissive so it can access system,
in settings there is a switch which can edit the state of enforcing.

v5.6 Fixed bugs
Added also some option to revert script like first launch,
alongside with fixing some annoying errors.

v5.5 quick fix
now first setup does install requirements to avoid errors,
if already then delete the file "noob" in your settings directory,
or go settings -> delete settings directory.

v5.0 release, getting even better
now settings menus use a while statement which can do go back in menus
now quick start uses a file stored on your device to define value
yes it's no longer reset upon exiting.
added settings and ability to choose directory of script settings
or change it, also removed some unnecessary code

v4.0 release, getting better
now logs are in colors optionally
quick start with root and text only methods
text only now supports instant refresh by clicking enter
some more I forgot

v3.0 release, nais one here
a menu now appears, asking what to show.
you get to sleect between root and no root notification,
or just text from terminal.

v2.0 release, literally 3 days after.
now it's a notification instead of terminal output.
warning, needs root from now on. use pre release instead.

v1.0 release, main release, simple and shows output in terminal
