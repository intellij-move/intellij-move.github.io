# Code Formatter

Intellij-Move provides automatic code formatter to help making sure your code looks the same across the whole project.

> This section is for plugin's own Move code formatter.
> If you want to use `movefmt` as your code formatter, check out the [movefmt integration](Movefmt.md) section.

## Formatting code from the IDE

You can invoke the formatter both for the whole Move file, and only for the code selection.

<procedure title="Reformat the selection" id="reformat_the_selection">
<step>Select the code fragment you want to reformat.</step>
<step>Press <shortcut key="$ReformatCode"/> or select <b>Code | Reformat Code</b> from the main menu.</step>
<note>
If you call Reformat Code without selecting a fragment, the IDE will reformat the whole file.
</note>
</procedure>

<procedure title="Reformat a file" id="reformat_file">
<step>Open the file you'd like to reformat.</step>
<step>Press <shortcut key="$ReformatFile"/> or select <b>Code | Reformat File...</b> from the main menu.</step>
<step>In the <b>Reformat File</b> dialog, select additional options if necessary. Click <b>Run</b>.
<img src="reformat_file.png" alt="reformat file" height="300" border-effect="line"/>
</step>
</procedure>

<procedure title="Reformat all files in the specific directory, or for the whole project" id="reformat_the_whole_project">
<step>Open Project tool window 
(press <shortcut key="$ProjectView" /> or select <b>View | Tool Windows | Project</b> if it's not already visible).</step>
<step>Select the project root, or any other directory.</step>
<step>Press <shortcut key="$ReformatCode"/> or select <b>Reformat Code</b> from the context menu.</step>
<step>In the <b>Reformat Code</b> dialog, select additional options if necessary. Click <b>Run</b>.
<img src="reformat_directory_code.png" alt="Reformat Directory Code" height="400" border-effect="line"/>
</step>
</procedure>


