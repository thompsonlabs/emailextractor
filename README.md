# emailextractor
Provided with a URL this bash utility will retrieve the contents of the referenced page and seek to extract all email addresses therein.

### usage
1.  Give the script executable permissions on your system, as necessary, by navigating to the root directory of the project and typing: `chmod +x ./eextractor`

2.  Run the script by typing `./eextractor [A_WEBSITE_URL]`

3.  On successful run of the utility, a file will be generated titled as follows: __[WEBSITE_DOMAIN].txt__  and stored to a sub directory titled extracted-emails; the contents of which, will be all email addresses successfully extracted from the page at the provided URL. 
