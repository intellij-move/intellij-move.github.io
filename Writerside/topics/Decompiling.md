# Decompiling

IntelliJ-Move provides integration with the `aptos move decompile` command.  

<procedure title="Decompile a single bytecode file" id="decompile_a_single_bytecode_file">
<step>Open the Aptos Bytecode file (with the <code>.mv</code> extension). By default, the IDE will show the binary contents of the file. 
<img src="mv_file_contents.png" alt="Bytecode File contents" />
If Aptos CLI is configured correctly, notification will be shown at the top of the file, allowing to decompile it and show the source code. 
Underneath, <code>aptos move decompile</code> will be called.  
</step>
<step>Click on <b>Decompile into source code</b> to see the original <code>.move</code> file. It will be created near the bytecode file with the name <code>BYTECODE_FILENAME.move</code></step>
</procedure>

<procedure title="Decompile a package from the blockchain" id="decompile_a_package_from_the_blockchain">
<step></step>
</procedure>



