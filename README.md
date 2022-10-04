# iOS-Battery-Checker

With this simple Code you can upload a log-aggregated ips file. When a file is uploaded, it reads the file as text, and then splits the text into lines. It then loops through the lines, and if a line contains a certain string like: com.apple.ioreport.BatteryCycleCount, com.apple.power.battery.MaximumFCC, com.apple.power.battery.NominalChargeCapacity, it'll get the values below that line, and displays these values in the top left hand corner.


## How to

1. Open Settings
2. Privacy & Security
3. Analytics & Improvements
4. Analytics Data
5. Search: log-aggregated-YYYY-MM-DD-XXXXXX (Pick the latest)
6. Click Top right "Share" > Save to Files e.g. "Downloads"

7. Go to https://ios-battery-checker.netlify.app/ (or your own website)
8. Click on Button then Choose your file
9. If done correctly you should see three Categories each displaying a value.

## Troubleshoot

"I don't have a log-aggregated file on my iOS Device"
> Make sure the Analytics & Improvements "Share iPhone & Watch Analytics" is turned on. If it wasn't turned on, turn it on and wait a few hours or days until you find a file named "log-aggregated" 
