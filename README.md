# budget-trackers

# Description
Applying Progressive Web Application, add functionality to budget tracker application to allow for offline access and functionality.  This allows the user to be able to add expenses and deposits to their budget with or without an internet connection.    When entering transactions offline, the total will still populate a total amount when it is brought back online.  

# Developer Creation
1. Created a manifest.webmanifest file, which describes to the browser how to display the app on either a mobile device or desktop monitor.  I linked to this manifest.webmanifest (json) file in the index.html file.
 
2. Created service-worker.js file that enables data to be cached.  The cached files are listed in the const FILES_TO_CACHE array

In Developer tools, need to check Application tab to ensure the Manifest and Service Workers (will appear under Application heading) and IndexedDB (will appear under Storage heading) are enabled.

3. In the IndexedDb.js file, link to 

In the index.html file, link to both the index.js and indexedDb.js file that was added.

In index.js file, link to 

Need to add data online and then test offline.

The offline data will be stored in a table named pending.  



# User Installation
First step is to install npm.


# Usage
Provide instructions and examples for use. Include screenshots as needed.

# Credits
If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

