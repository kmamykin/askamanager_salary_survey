# askamanager Salary Survey

Cleaned up dataset of self-reported salaries


## Getting the raw original data

Download in CSV https://docs.google.com/spreadsheets/d/1rGCKXIKt-7l5gX06NAwO3pjqEHh-oPXtB8ihkp0vGWo/export?format=csv

Download OpenRefine https://github.com/OpenRefine/OpenRefine


## Assumptions and calculations

Hourly rate to annual base salary conversion: assumes 1650 billable hours per year.
https://www.trinityp3.com/calculators/

Google API Key: AIzaSyCmmdNgylHYkAa4hlB3B-cIV0Q_rFd__gU
AIzaSyCqd-BAzUsp6a2ICBETWebYYwoA3d3EeWk

Industry codes: https://developer.linkedin.com/docs/reference/industry-codes#
https://www.webspidermount.com/features/generic-job-taxonomy/
https://en.wikipedia.org/wiki/Global_Industry_Classification_Standard
https://en.wikipedia.org/wiki/Industry_Classification_Benchmark


"https://maps.googleapis.com/maps/api/place/findplacefromtext/json?input=" + escape(value.strip(), "url") + "&inputtype=textquery&fields=formatted_address,name&type=locality&key=AIzaSyCqd-BAzUsp6a2ICBETWebYYwoA3d3EeWk"
