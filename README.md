# iOS-Battery-Checker

This code allows you to upload a log-aggregated ips file that contains information about battery usage. The code will read the file and then split it into lines. If a line contains certain strings of text like: com.apple.ioreport.BatteryCycleCount, com.apple.power.battery.MaximumFCC, com.apple.power.battery.NominalChargeCapacity, the code will display the values from that line in the top left hand corner.

## How to

1. Open Settings
2. Privacy & Security
3. Analytics & Improvements
4. Analytics Data
5. Search: "log-aggregated"-YYYY-MM-DD-XXXXXX.ips (Pick the latest)
6. Click Top right "Share" > "Save to Files" e.g. "Downloads"

7. Go to https://ios-battery-checker.netlify.app/
8. Click on Button then Choose your file
9. If done correctly you should see three Categories each displaying a value.



## Explaination
> BatteryCycleCount = How many Times your Battery has been charged.
> MaximumFCC = Max. Designed Capacity of your Battery when it was new.
> NominalChargeCapacity = Capacity of your Battery now.



## Troubleshoot

"I don't have a log-aggregated file on my iOS Device"
> Make sure under Analytics & Improvements the "Share iPhone & Watch Analytics" is turned on. If it wasn't turned on, turn it on and wait a few hours or days until you find a file named "log-aggregated". After you have your file, it is recommended to turn off Analytics.
