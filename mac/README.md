**Simple double click on "shift-planner.app" will open the app and create the file in the current dir"**

When you download an app from the internet (like GitHub, Google Drive, or email) that wasn't created on your own specific computer, macOS tags it with a hidden "Quarantine" flag. 

Open your Terminal. 
```
$ sudo xattr -cr /Users/XXXX/Downloads/shift-planner.app
```

**For new build on MAC**

```
$ cd /XXX/XXXX/python.py
$ python3 -m venv build_env
$ source build_env/bin/activate
$ pip install pyinstaller
$ pyinstaller --noconsole --onedir --windowed shift-planner.py
$ deactivate
Go to your dist folder. You can now double-click shift-planner.app and it will open correctly.
You can even move it to your desktop and remove the rest of files
```
