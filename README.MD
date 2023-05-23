# SubwaySurfersSaveFile
Cleaned and improved port of [janpascal](https://github.com/janpascal)'s SubwayEdit implementation of the Subway Surfers save file to C#

# Usage
```csharp
// playerdata.0 is the file containing the useful stuff
SubwaySurfersSaveFile file = new SubwaySurfersSaveFile() { FileName = "playerdata.0" };
file.ImportFile();
file.ExportFile();
```

# Where is playerdata.x?
You MUST have root to get these files<br>
Use a file manager and browse to /data/data/com.kiloo.subwaysurf/files

# ⚖ License
This project is licensed under the GPLv3 license<br>
You may refer to the "LICENSE" file for more information<br>
NOTE: The original repository had no license