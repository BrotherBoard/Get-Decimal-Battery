# Decimal-Battery
get your battery capacity up to one decimal number.

do `bash DecimalBattery` in some terminal

How it works:

copies the file from
/sys/class/power_supply/battery/charge_counter
to
/storage/emulated/0

chooses directory
/storage/emulated/0

shows a text of
your battery percentage is

by naming a variable with the text inside the file we copied
value of the variable "board" is based on the text inside file

divide the variable by 30,000
now the variable should be ready for displaying

shows the percentage under the "your battery percentage" line
XX.X (ex. 68.9)

Tested on the Galaxy A10 running Android 13 Arm64
