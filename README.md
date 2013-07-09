SecurityScopeBookmarkTest
=========================

First launch the app, create a new document, and quit.


Test Case 1.

1. Launch the app.
2. Open a previous saved document.
3. In Finder, move that document to another location.
4. In the recent files window in the app, select the document from the list and click "Refresh Selected". Notice that the URL updates to the new location.
5. Make an edit to the file and save. Note that the file successfully saves.
6. Refressh the URL in the recent files window. Note that the URL fails to refresh with a file not found error.
 

Test Case 2.
1. Launch the app.
2. Open a previous saved document.
3. Make an edit and save.
4. In Finder, move that document to a different location.
5. In the recent files window in the app, select the document from the list and click "Refresh Selected". Note that the URL fails to refresh with a file not found error.
