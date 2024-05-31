# Code Formatter

Intellij-Move provides automatic code formatter to help making sure your code looks the same across the whole project.

[//]: # (TODO: gif to showcase the formatting experience)

## Formatting code from the IDE

You can invoke the formatter both for the whole Move file, and only for the code selection.

<procedure title="Reformat the selection" id="reformat_the_selection">
<step>Select the code fragment you want to reformat.</step>
<step>Press <shortcut key="$ReformatCode"/> or select <b>Code | Reformat Code</b> from the main menu.</step>
<note>
If you call Reformat Code without selecting a fragment, the IDE will reformat the whole file.
</note>
</procedure>

<procedure title="Reformat a file" id="reformat_a_file">
<step>Open the file you'd like to reformat.</step>
<step>Press <shortcut key="$ReformatFile"/> or select <b>Code | Reformat File...</b> from the main menu.</step>
<step>In the <b>Reformat File</b> dialog, select additional options if necessary. Click <b>Run</b>.
<img src="reformat_file.png" alt="reformat file" height="300" border-effect="line"/>
</step>
</procedure>

<procedure title="Reformat all files in the the specific directory, or for the whole project" id="reformat_the_whole_project">
<step>Open Project tool window 
(press <shortcut key="$ProjectView" /> or select <b>View | Tool Windows | Project</b> if it's not already visible).</step>
<step>Select the project root, or any other directory.</step>
<step>Press <shortcut key="$ReformatCode"/> or select <b>Reformat Code</b> from the context menu.</step>
<step>In the <b>Reformat Code</b> dialog, select additional options if necessary. Click <b>Run</b>.
<img src="reformat_directory_code.png" alt="Reformat Directory Code" height="400" border-effect="line"/>
</step>
</procedure>

[//]: # (## Add formatting check to CI)

[//]: # (### Qodana)

[//]: # ()
[//]: # (The easiest way to add formatting check to your CI pipeline is )

[//]: # (using Jetbrains [Qodana Cloud service]&#40;https://qodana.cloud/&#41;. It's free )

[//]: # (for open-source projects.)

[//]: # (### Manual)

[//]: # (If your project is not public, and you don't want to buy Qodana license, you'd need to setup your CI formatter check manually. )




