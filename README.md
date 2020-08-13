# budget-trackers

# Description
Applying Progressive Web Application, add functionality to budget tracker application to allow for offline access and functionality.  This allows the user to be able to add expenses and deposits to their budget with or without an internet connection. When entering transactions offline, the total will still populate a total amount when it is brought back online.  

# Developer Creation
1. Created a manifest.webmanifest file, which describes to the browser how to display the app on either a mobile device or desktop monitor.  I linked to this manifest.webmanifest (json) file in the index.html file.
 
2. Created service-worker.js file that enables data to be cached.  The cached files are listed in the const FILES_TO_CACHE array

In Developer tools, need to check Application tab to ensure the Manifest and Service Workers (will appear under Application heading) and IndexedDB (will appear under Storage heading) are enabled.

3. In the index.html file, link to both the index.js and indexedDb.js file that was created.


# User Installation
First step is to install npm.
Run node server

Need to add data online first and then add data offline.

The offline data will be stored in a table named pending (an object store), as can be seen here:
![budgettrackerpendingoffline](https://user-images.githubusercontent.com/57371259/90090743-0bfbea80-dce2-11ea-9baf-1b65727180c1.jpg)  


# Usage
User will be able to add expenses and deposits to their budget with or without an internet connection.  When entering transactions offline, the total will still populate a total amount when it is brought back online.  

