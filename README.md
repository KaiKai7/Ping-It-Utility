# Ping-It-Utility-Lite
This is an android app to ping an ip address or site. On demand pings can be run, as well as scheduled pings.
When pings are scheduled they will run at the specified interval, which could be anywhere from 1 minute to 24 hours.
The trigger threshold in milliseconds can also be set. This is what the duration will need to be or greater in order to trigger an alert. This can be changed from 10 milliseconds to 1500 milliseconds (1.5 seconds).
App can run in the background and still run scans as well as send a notifcation.
Log file is a .csv file saved to the device.
Each day is a separate .csv file. If a file does not exist for the date the ping is being run, then there is no log file.
Log files only created if at least one event for that day is triggered.
Before log is written to file, if the file did not already exist then a new .csv file is written with the headers. Then a new line is written to it, this make the data more easily readable if opened in Sheets or similiar.
Run a scan if you feel there is network latency. You can ping the router or individual suspected devices.
Run in the background overnight, and be alerted if there is a network outage when sleeping. This could be a wifi jamming attack or other planned attack.
Monitor your internet connection and save times of unresponsiveness to file.
