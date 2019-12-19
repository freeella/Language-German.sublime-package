# Language-German.sublime-package
An already UTF8 converted and packaged OpenOffice / LibreOffice based dictionary based on the recommendations of http://www.sublimetext.com/docs/2/spell_checking.html

## Install Sublime package

* Download [Language - German.sublime-package](https://github.com/freeella/Language-German.sublime-package/raw/master/Language%20-%20German.sublime-package)

* Place it inside the 'Installed Packages' directory.

````
[Linux]$ cp "Language - German.sublime-package" ~/.config/sublime-text-3/Installed\ Packages/
or
[Linux]$ cp "Language - German.sublime-package" /opt/sublime_text/Packages/


[OS X]$ cp "Language - German.sublime-package" ~/Library/Application\ Support/Sublime\ Text\ 3/Installed\ Packages/
or
[OS X]$ cp "Language - German.sublime-package" /Applications/Sublime\ Text.app/Contents/MacOS/Packages/


[WINDOWS]C:\> copy "Language - German.sublime-package" "%APPDATA%\Sublime Text 3\Installed Packages"
or
[WINDOWS]C:\> copy "Language - German.sublime-package" "%ProgramW6432%\Sublime Text 3\Packages"
````

* Restart Sublime

### Limitations

* If the package is deleted from "*/Installed Packages" by Package Control, deactivate "remove_orphaned" under 
"Package Settings"->"Package Control"->"Settings - User" or delete package-metadata.json.

```javascript
{
	"remove_orphaned": false
}
```

* When installing the package directly to the program directory, no packages are auto removed by Package Control but they might be removed when Sublime Text is updated.
