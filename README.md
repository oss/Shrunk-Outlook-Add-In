# Steps to Test Add-in
1. Run `npm install` inside root directory. Once that's done, run `npm start`
2. Navigate to https://outlook.office.com/mail/
3. Open any email
4. Under the subject, there will be a few icons. Click square with four circles in it (Apps)
5. Find the extension and click show Task pane

More help to side-load:
https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/sideload-outlook-add-ins-for-testing?tabs=web#modern-outlook-on-the-web-and-new-outlook-on-windows-preview


To do:
 - Add extra parameter to tracking pixel fetching "/<alias>.png?countVisits=false" that does not increment the visits in the metadata for that link
 - Make it look pretty