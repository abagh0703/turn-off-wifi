# Description
A simple Python script that turns off the wifi on a Windows 10 computer and then turns it back on after a configurable
number of seconds. 

# Running
You can run this with `python turn-off-wifi.py`. Change `SECONDS_WITH_WIFI_DISABLED` to alter how long the wifi 
remains disabled.
Be sure to run it with admin rights. If you don't, you'll see "return value 5" in the command prompt and the disabling
of wifi won't function properly.

# Use Case
I've used this with [Windows Task Scheduler](https://sumtips.com/how-to/run-program-windows-wakes-up-sleep-hibernate/) 
to turn off my wifi for a couple minutes whenever my computer awakens from sleep or hibernation. This causes me to stop 
and be more mindful about the tasks that I work on when getting to my computer, helping me focus on only the highest
priority tasks instead of easier lower priority tasks.