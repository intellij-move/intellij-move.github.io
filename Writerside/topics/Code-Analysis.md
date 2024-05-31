# Code Analysis

With Intellij Move, you have two options for static code analysis: the built-in set of inspections and/or [external linters](#external-linters). 

## Inspections

Inspections detect and help to correct anomalous code before you compile it. 
This includes various problems like potential bugs, spelling problems, or overall code structure issues.

By default, most of the Rust inspections work on-the-fly. Some also provide quick-fixes to be applied right away. 

[//]: # (TODO: unresolved reference gif &#40;with auto-import quickfix&#41;)

[//]: # (TODO: type checking gif)

[//]: # (TODO: unused import gif)

You can also run inspections on demand by calling **Code | Inspect Code** from the main menu. 
In this case, the results are shown in a separate window, from which you can apply quick-fixes 
to a single case or to several cases at a time.

[//]: # (TODO: image for receiver-style function checking)

## External linters

In addition to the built-in set of inspections, Intellij Move helps you run 
[Aptos Compiler](https://aptos.dev/tools/aptos-cli/use-cli/working-with-move-contracts/#1-compiling-move) 
without leaving the IDE.

<procedure title="Call Aptos Compiler" id="call-aptos-compile">
    <step>Go to <b>Settings | Language & Frameworks | Move Language | External Linters</b>.</step>
    <step>Select the external linter (at the time only <b>Aptos Compiler</b> is supported) and provide additional arguments if required:
    <img src="external_linter_settings.png" alt="External Linter Settings" height="400" border-effect="line"/>
    <note>
    Set the <b>Run external linter to analyze code on the fly</b> checkbox if you prefer the chosen linter to work as you type. 
    However, note that this might cause significant performance slowdown.
    </note>
    <p>A widget in the status bar will also show the status of the on-the-fly analysis option. You can click it to quickly open the linters settings.</p>
    <img src="external_linter_widget.png" alt="External Linter Widget" height="100" border-effect="line"/>
    </step>
    <step>If you haven't set <b>Run external linter to analyze code on the fly</b> on the previous step, call the linter by clicking <b>Run external linter</b> in the Aptos tool window (<b>View | Tool Windows | Aptos</b>)
    <img src="external_linter_button.png" alt="External Linter Button" height="200" border-effect="line"/>
    </step>
</procedure>
