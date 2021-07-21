# bme280_google_excel
This code to push all bme's data to cloud using google driver API also the google sheet API
# How to use:
  * Creat the cloud with key and name will be sent on google_spreadsheet.py and the google-auth.json 
  * Send all the data with Frequency data sending and the sheet's name corectly
  * lib: gspread and oauth2client
# Syntax: python3 google_spreadsheet.py 
 
# Note:
 * You have to share the user @:   "client_email": "pi-107@optical-torch-320306.iam.gserviceaccount.com",(for example in google-auth.json file) to googlesheet which you wanna send all data into. 
 * You have to check the name of your datasheet correctly on google_spreadsheet.py @: GDOCS_SPREADSHEET_NAME = 'raspi-temp'(for example)
 * You have to consider the name of the Sheet inside the datasheet as **Sheet 1** for example 
