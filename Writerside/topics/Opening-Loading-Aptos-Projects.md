# Working with Aptos projects

<procedure title="Open an existing Aptos project" id="open_existing_aptos_project">
<step>Go to <b>File | Open</b> and select the directory containing the root <b>Move.toml</b> file 
(or select <b>Move.toml</b> itself)
</step>
<step>Check the Aptos tool window (<b>View | Tool windows | Aptos</b>) to make sure your project has been imported successfully:
<img src="opened_project.png" alt="Aptos Tool Window with imported project" border-effect="line" width="600">
</step>
</procedure>

<procedure title="Create new Aptos project" id="create_new_aptos_project">
<step></step>
</procedure>

## Project loading

When you open or update an existing Aptos project, the plugin takes project information from the **Move.toml** files 
and opens the **Build** tool window (the **Sync** tab) to show the progress and result of project loading. 
Click ![inspections-eye](inspectionsEye.svg) to view all the steps:

![Build Tool Window image](build_sync.png) { border-effect="line" width="450"}

### Automatic reloading

By default, Intellij Move reloads the project whenever you update **Move.toml** outside the IDE or through VCS. 
You can change that behaviour in **Settings | Build, Execution, Deployment | Build Tools**.

![Reload Behaviour](reload_behaviour.png) { border-effect="line" width="350" }

### Manual reloading

If automatic reloading is partly/fully disabled, the IDE will still let you know whenever the model needs an update 
- the editor will display a button that you can use to quickly reload the model.

![Load Changes](load_changes.gif)

Alternatively, you can reload projects through the Cargo tool window (**View | Tool Windows | Cargo**) 
by clicking the ![Reload Icon](refresh.svg) in the toolbar.

