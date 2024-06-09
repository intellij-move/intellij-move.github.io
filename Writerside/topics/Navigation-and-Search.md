# Navigation and Search

You can quickly navigate through your Move code, as well as through the IDE elements, using various actions and popups.

## Go-to-Definition

To get to the definition of the item, select it in the editor and press <shortcut key="$DeclUsages"/>. 

## Find usages

The **Find Usages** action helps you search for the references of a code element across the codebase. 

<procedure title="Find usages in file" id="search_for_item_usages">
<step>In the editor, place the caret at a symbol you want to find.
<p>By default, the IDE automatically highlights all found usages in the file:
<img src="highlight_all.png" alt="Usages Highlighted" width="500" border-effect="line" />
</p></step>
<step>
<p>
By pressing <shortcut key="$DeclUsages"/> on the item definition, usages popup is invoked with the list of usages:
<img src="find_usages.gif" alt="List of Usages" width="500" border-effect="line" />
</p>
</step>
</procedure>

<procedure title="Search for item usages in a project" id="search_for_usages_in_a_project">
<step>Select a symbol, then right-click it and choose <b>Find Usages</b> from the context menu, 
or press <shortcut key="$FindUsages"/>.</step>
</procedure>

## File structure

You can explore the structure of the currently opened file in the **Structure** tool window or in a popup.

* To open the **Structure** tool window, select **View | Tool Windows | Structure** from the main menu 
   or press <shortcut key="$ShowFileStructure" />.

* To view the file structure in a popup, select **Navigate | File Structure** from the main menu 
   or press <shortcut key="$NavigateFileStructure"/>.

![File Structure](file_structure.png)