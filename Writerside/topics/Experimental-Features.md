# Experimental Features

There's a number of experimental features that are disabled by default, but can be turned on with the registry options. 
To enable those, press <shortcut key="$SearchActions">, type "Registry" and select it to open Registry Editor window.

You can also set those by clicking **Help | Edit Custom Properties...** and specify explicit boolean values 
for those properties.  

* `org.move.aptos.fetch.deps` 

    Enables calling `aptos move compile` on every build sync to be able to fetch 
    Aptos git dependencies without the need to call it yourself every time you change `Move.toml` file. 

* `org.move.debug.enabled` 

    Enables "Debug Mode" which turns some silent errors into explicit ones and allows better error reporting. 

