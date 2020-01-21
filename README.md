# intelliJ
IntelliJ Cheatsheet (Windows Default and Mac OS X 10.5+)
https://www.youtube.com/watch?v=eq3KiAH4IBI
https://www.youtube.com/watch?v=Cv-84klCL7Q

## God Shortcuts
* Double shift : Search Everywhere (Enter / to see commands)
* Ctrl + Shift + A (Cmd + Shift + A) : Find action
* Ctrl + E (Cmd+E) : Recent Files [use Tab Placement as None to show only one file](https://www.jetbrains.com/help/idea/settings-editor-tabs.html)
* Shift + Ctrl/Cmd + E : Recent Location
* Ctrl + Shift + C : Recent changes

## Project and Windows
* Project : Alt/Cmd + 1 
* Version Control : Alt/Cmd + 9
* Terminal : Alt + F12
* Hide all Windows : Shift + Ctrl + F12 (Shift + Cmd + F12)
* Quick Switch mode: Ctrl + `` ` `` => Distraction Free Mode
* Settings : Ctrl + Alt + S (Cmd + ,)
* Project Structure : Shift + Ctrl + Alt + S (Cmd + ;)
* New File : Alt + Insert (Cmd + N)
* Ctrl (two times) - Run anything
* Alt + Home (Cmd + Up) - Navigation bar

## Navigation
* double shift
* Ctrl + N (Cmd + O ) => Navigate to class
* Ctrl + _*Shift*_ + N (Cmd + _*Shift*_ + O ) => Navigate to file
* Ctrl + _*Shift*_ + _*Alt*_ + N (Cmd + _*Alt*_ + O ) => Navigate to Symbol
  - j.u.c.c.DEFAULT_CAPACITY => Search DEFAULT_CAPACITY in java.util.concurrent.ConcurrentHashMap
* Ctrl + Alt + Right / Left (Cmd + ] / \[) => Forward / Backward
* Cmd / ctrl + F12 => list all methods in a class

## Class Hierarchy
* Ctrl + B (Cmd + B) =>  Declaration (of a method, variable )
* Alt + Ctrl + B (Alt + Cmd + B) =>  Implementation
* Alt + F7 => Usage
* Ctrl + Shift + B (Cmd + Shift + B) => Type Declaration
* Ctrl + U (Cmd + U) => Super Method
* Shift + Cmd + T => Test Subject for Tests or on Class to see tests for that class


## Search 
* Find in File: Ctrl + F (Cmd + F ) 
* Find occurences in Path: Ctrl + Shift + F (Cmd + Shift + F)
* Replace : replace F with R

## Project Window Resize
* shift + ctrl + Right / Left

## Editing
* Extend Selection : Ctrl + W (Option + Up)
* Deselect : Shift + Ctrl + W (Option + down)
* Move selection Up / Down: Shift + Ctrl + Up /down(Shift + Option + Up/Down)
* Duplicate a line : Ctrl + D (Cmd + D)
* Delete a line : Ctrl + Y (Cmd + Backspace)
* Clip board history : Shift + Ctrl + V (Shift + Cmd + V)
* Word Selection : Alt + J (Ctrl + G)
* Unselect: Shift + Alt + J (Shift + Ctrl + G)
* Move to next occurence : F3 (Cmd + G)
* Multiple cursors : Alt + Shift + button1 click
* Auto indent: Ctrl + Alt + I 
* Reformat : Ctrl + Alt + L
* Select a method (Alt + J or Ctrl + G) > Ctrl + Enter > Change code style if u wish
* Alt + Enter => Lang inject (Json, regex, html etc)

## Completion
* Basic Completion: Ctrl + Space 
* Smart Completion: Shift + Ctrl + Space (e.g. BufferedReader bf = new <Use Smart not Basic>)
* Complete Current Statement : Shift + Ctrl + Enter (Shift + Cmd + Enter) 
* Parameters : Ctrl + P (Cmd + P)
* Hippie-Completion (cylic completion) : Alt + / (say I have variable test1 to test10. If I type test and press Alt + /, it will loop thru all the values)
* Intention action: alt + enter (like static import )
* Cmd + , => select auto import.
  (https://www.jetbrains.com/help/idea/auto-completing-code.html)

## Extract
* Ctrl/Cmd + Alt + V/P/M
  
 ## Live Templates
 * Ctrl + J (Cmd + J)
 * Surround Template: Alt + Ctrl + T (Alt + Cmd + T)
 * Try this. 
 ```Java
 Person p = new Person()
 // p.[in suggestion you can see that you have null and notnull which evaluates to expression]
 ```
 
