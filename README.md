# activity-dashboard-reports

## Setup
- Add the agiliteActivityDashboardReports.json application to your Connections organisation
- Ensure the include-files property pulls the correct path referencing the following files:

* agiliteCore.js
* chart.js
* xml2json.js
* agiliteActivityDashboardReports.js

- In the Community Homepage of the Community you wish to have these reports active for, edit the Rich Content widget, select HTML Source in the WYSIWYG editor, and paste the following HTML into the editor:

```javascript
<div id="agilite_activity_dashboard_reports">Loading Activity Dashboard Reports...</div>
```
- Save and close the Rich Content widget

## Description
The purpose of this Customizer application is to generate a doughnut chart for the logged in user's Active and Completed To Do items per Activity for a specified Community. This application is self managed and only requires that you provide a small piece of HTML code into the Rich Content widget of the relevant Community (Read the "setup" instructions above)

To test this functionality, simply open the Homepage of the Community that has been setup according to the "setup" instructions above. In the Rich Content widget, 2 doughnut charts will be created: 1 for your active Activities and 1 for your completed Activities.

## Screenshots

![Screenshot 1](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-activity-dashboard-reports-1.jpg)

![Screenshot 2](http://bleedingcode.com/wp-content/uploads/2017/10/agilite-activity-dashboard-reports-2.jpg)