# bmmvtu3.py

This is a python3 translation of g0t mi1k's bmmvtu.py Batch/Mass/Multiple VirusTotal.com Uploader.

https://blog.g0tmi1k.com/2011/10/bmmvtupy-batchmassmultiple/

Full credit goes to him. I had need for a mass uploader and found this. While it still works, it was written some time ago. Rather than install python2, I got it working in python3 (I'm lazy like that).

### Changes
Ran it through a python2 -> python3 converter
Wrapped "open file" on line 54 in str() to prevent "expected str instance, bytes found"
Changed line 128 and 129 to str() instead of encode ASCII to prevent "cannot concatenate str to byte" error.
