# ScheduleSync
Exporter from Orel State University: [Schedule of Classes ](http://oreluniver.ru/schedule) to Google Calendar.

## Tips
Before usage should be generated OAuth client secret file [here](https://console.developers.google.com/apis/credentials). Algorithm of generating OAuth client secret is similar to [this one](https://github.com/burnash/gspread/wiki/How-to-get-OAuth-access-token-in-console%3F). 

There is an issue with permissions for "cacerts.txt" (part of httplib2 library) in OS X. Could be fixed as described [here](http://stackoverflow.com/questions/15696526/ssl-throwing-error-185090050-while-authentication-via-oauth).