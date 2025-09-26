## goto-obsidian

goto-obsidian uses [URI scheme of Obsidian](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI) to jump to the note in Obsidian with the same name as the current directory. If the note does not yet exist, it will be created. 

This helper is very specific to my needs and must be adapted to your use case. 1) It only makes sense if your folder is embedded in a naming system with a unique ID, as in my case [Johnny Decimal](https://johnnydecimal.com/). 2) You have to enter your vault name and the note directory in the line starting with `set obsidianURI`

