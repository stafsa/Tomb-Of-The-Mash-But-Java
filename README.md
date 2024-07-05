# Tomb-Of-The-Mask-But-Java
Basically a copy of Tomb Of The Mask.But it made with java.Honestly, I didn't make this completely.I just added map editor, some new maps, Customizaton, better map configuration.That's all.Thank you for reading.And in case anyone want it's source code, I will publish it tomorrow or, next week.
Here's the original source code: https://github.com/Aom92/smolToTMclone
I will tell you how can you change source and how can you compile it.
# What Should I do, My Terminal Isn't Unix?
if you use another OS, for example windows(I will explain for just windows.The files are shell[.sh] file btw)You should use that files:

**Run.bat:**
```bat
@ECHO OFF

call cd bin 
start java src/main/Game
```
**MapEditor.bat**
```bat
cd bin/src/mapeditor
java MapEditor
cmd kill
```
