# Exercise 2: Scrape SENS announcements from the JSE

### About



You will need to write a console application that is able to scrape SENS announcement data from the [JSE's website](https://clientportal.jse.co.za/communication/sens-announcements) or an alternative data source.
The output of your application needs to be a styled Microsoft excel file (.xlsx) where the background of the column headers need to be coloured in green.
And the text in a bold. 


### Useful links:
* JSE SENS Page: https://clientportal.jse.co.za/communication/sens-announcements
* Moneyweb SENS Page (alternate data source): https://www.moneyweb.co.za/tools-and-data/moneyweb-sens/
* Sharenet (alternate data source): https://www.sharenet.co.za/v3/sens.php


### Constraints:
* Your final console application needs to be a self contained executable and able to run on a Windows 10 machine


### Example inputs
As an input, your console application should take in an optional argument called `output_filename` eg:

```
..> .\YourConsoleApp.exe -o sens_announcements_latest.xlsx
```
WHERE
* `.\YourConsoleApp.exe`: is the windows executable version of your application
* `sens_announcements_latest.xlsx`: is the name of the expected output file

### Example outputs
As an output your console app should spit out a Microsoft excel file containing the necessary data in a presentable format. Also, the column headers need to have a green background. See below image for example output file
![alt text](https://drive.google.com/uc?export=download&id=1QCP2yQOCr9KmuRVYXBKez4RS_phgaKiH)