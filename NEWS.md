# NCoVUtils 0.4.0

* Added functions to extract regional cases for Spain, Japan, South Korea, the United Kingom, and the United States.
* Improved data extraction from the ECDC.
* Added minimal unit tests.

# NCoVUtils 0.3.0

* Added a function to extract case counts by region for Italy.
* Function to extract ECDC cases. 
* Added a function to extract case counts by region in Germany.
* Fixed cache reset. 
* Added a `NCoVUtils` cache of the public linelist as a fall back option if the source is not available.

# NCoVUtils 0.2.0

* Added `memoise` functionality to automatically cache in the current directory all remote resources.
* Added a non-Hubei linelist function that can extract country and city linelists.
* Added a function to extract the latest WHO case counts.
* Added a function to summarise the current total number of cases.

# NCoVUtils 0.1.0

* Added a `NEWS.md` file to track changes to the package.
* Added `get_linelist` function
* Added functions to reparameterise Weibull and Gamma distributions with mean and standard deviations.
