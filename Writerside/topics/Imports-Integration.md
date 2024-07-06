# Imports Integration

Intellij-Move plugin automates working with use statements in the Move language.  

## Unused import inspection

If imports are unused in the file, they are highlighted with the grayed text. 

![Unused imports](unused_imports_2.png) { border-effect="line" width="600"}

## Optimize imports

To get rid of those unused imports, you can use the special function of the Jetbrains IDEs. 

Click on **Code | Optimize Imports** (or <shortcut key="$OptimizeImports"/>), 
and the IDEs will remove all the highlighted use items.

![Optimize Imports](optimize_imports.gif) { border-effect="line" width="600"}

## Auto imports

Searching through the code for the functions and types, and adding use statements for them manually can be a tedious task. 
Intellij-Move provides a way to automatically add the correct statements 
for an accessible item in the project by showing them up in the completion popup:

![Auto Import](auto_import.gif) { border-effect="line" width="600"}

Those completion popups also greatly help with the discovery of the new functions. 

