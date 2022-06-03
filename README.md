# phivolcs-datasets
A repository containing all data from PHIVOLCS earthquake data in CSV and JSON (still planned) formats.

All data is scraped from web, using a script I coded in Python, in [Department of Science and Technology - Philippine Institute of Volcanology and Seismology (DOST-PHIVOLCS) Website](https://earthquake.phivolcs.dost.gov.ph/).

The website is public to anyone who can access the records of the recent and past earthquakes that have happened in the Philippines and this repository also serves as an archive of the earthquake events.


**A note also:**
Around year 2016, there are missing data since the website returns an error 404 not found, who knows what happened to the webpage.

For realtime fetching of data, the script I used updates regularly for every one minute, fetching data 60 times per hour, though there are downtimes in the source website, I will still validate the dataset for missing data, inconsistency or corrupted text which may be written into the CSV file.