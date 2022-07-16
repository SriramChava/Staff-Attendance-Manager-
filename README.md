# Staff-Attendance-Manager-
Web App for managing and storing staff attendance of an organisation.

# WEBAPP URL : 
https://script.google.com/macros/s/AKfycbwHJZhZBBrqXdkm7rjzjShnQ2873nInUBK79_xGMf0aeNBgpsgP1MpkHaLRhyTrrvUB/exec


# Staff Management

Google Apps Script Documentation : https://developers.google.com/apps-script/guides/sheets/functions

The Staff Management system is a webapp, where staff of the organization can mark their daily attendance. The webapp includes a login dashboard which is protected by a passcode so that only staff can open the webpage.

ADD ENTRY : Staff will type his/her name and click on the ADD ENTRY button to record their entry time.

ADD EXIT : Staff can enter their name again and an exit time is automatically added in the excel. It is necessary for the user to already have an entry time otherwise an exit time will not be added.

ADD OFF/LEAVE : This button adds OFF and Leave against a persons name in case they are not present.

DELETE ALL:  This button deletes all the added entries in the sheet incase of an error.

SAVE EXCEL IN DRIVE AND GENERATE PDFS : This button should be activated monthly for best performance. Pressing this button deletes all entries of the previous month and genrates PDFS and mails the previous months attendance reports to all the recipients. Drive folder links have to be provied for storing previous months excels and also to store all the generated reports.  



