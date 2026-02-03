**Simple double click on "shift-planner.app" will open the app and create the file in the current dir"

When you download an app from the internet (like GitHub, Google Drive, or email) that wasn't created on your own specific computer, macOS tags it with a hidden "Quarantine" flag. 

Open your Terminal. 
```
$ sudo xattr -cr /Users/XXXX/Downloads/shift-planner.app
```
