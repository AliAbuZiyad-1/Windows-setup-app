# Windows Setup App

This is my **first application** from a terrible programmer, the app is probably isnt good, as it doesnt even work somtimes and i didnt even tested it thats how lazy im.
You can run it anywhere in Windows PE or a live Windows environment that has some sort of recovery apps. (It only supports Windows and i don’t think it works under Linux/Wine beacuse of the abomination i made on it)

## What it does
- **Fix My PC**: literally just runs command prompt. Doesn’t work if your os doesnt have cmd.exe at system directory
- **Select Image File & Edition**: choose a Windows image to install kinda basic
- **Partitioning**: pick a volume to install on, Only works if the volume has a drive letter (Because im lazy), You cant format, create, or resize partitions  (Advanced users can use the “Fix My PC” button and DiskPart if needed because i dont care about the app anymore)  
- **Installing Phase**: installs Windows Logs exist for debugging, probably useless

## Notes
- This is my first ever app, built with absolutely no knowledge of C#
- It might be slow, glitchy, or litterly never works
- Feedback is appreciated, but don’t expect me to fully fix it because i completely forgot to save my source code

## ⚠️ Disclaimer
This application is provided **"as-is"** for educational/testing purposes only
I am **not responsible** for any damage, data loss, or corruption that happens when using this app
Use it at your **own risk**
