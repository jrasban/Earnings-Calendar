# Earnings-Calendar
This Python script will pull all earnings announcement dates from Yahoo. The code is designed to start on the current day and go through the end of the year. With this information, we can build an ics calendar with these events. Below is the example calendar that this python code builds.

![](images/calendar.PNG)

## Recommendations and Additional Comments
It takes a long time to pull even 3 months worth of data from yahoo using this script. We recommend running the first part of the code once and placing the data into a CSV that can be referrenced mutliple times during calendar building. We have attached a csv in this repository as an example. The time frame is always set to the end of the current year. It may be wise to alter this so that the script does not run for a very long time. 












