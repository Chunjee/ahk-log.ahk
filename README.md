# log.ahk

A powerful, no-nonsense logging library for AHK

## Installation

In a terminal or command line navigated to your project folder:
```bash
npm install log.ahk
npm install json.ahk
```

In your code only export.ahk needs to be included:
```autohotkey
#Include %A_ScriptDir%\node_modules
#Include log.ahk\export.ahk
#Include json.ahk\export.ahk ; log.ahk depends on json.ahk

logger := new log()
logger.add("application starting...")
```
You may also review or copy the library from [./export.ahk on GitHub](https://raw.githubusercontent.com/Chunjee/log.ahk/master/export.ahk); #Incude as you would normally when manually downloading.
