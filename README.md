# Making Android Studio pretty
Today, during a glorious transition from 1.5 rc1 to 1.5 Android Studio decided to keep all of my settings completely intact, with the honorable exception of GUI and syntax themes and LogCat colors, which were just gone. Being me, I had not the slightest recollection on how the previous combo have gotten into my editor and I had to search for everything again. Not particularly enjoying the process of rediscovery, I decided to keep it stashed somewhere, both for the future me and maybe for some curious souls that happen to bump onto my blog.


## Final appearance

| Shot 1    |
| :-------------: |
| ![Shot](./screen%20shots/prettyAS-1.png) |

| Shot  2   |
| :-------------: |
| ![Main](./screen%20shots/prettyAS-2.png) |

| Shot   3  |
| :-------------: |
| ![Shot](./screen%20shots/prettyAS-3.png) |

| Shot   4  |
| :-------------: |
| ![Shot](./screen%20shots/prettyAS-4.png) |

=======================================================================================
### GUI Theme manual from here
Open the Settings/Preferences dialog (OSX/Unix: ⌘+,, Windows: Ctrl+Alt+S)
In the left-hand pane, select Plugins.
Click Browse repositories… and search for Material Theme UI
Click Install plugin and confirm your intention to download and install the plugin.
Click OK in the Settings dialog and restart for the changes to take effect.
``` explain
 tl;dr: ⌘⇧a → "Plugins" → ↩ → ⌃⌥b → <search> → "Material Theme UI" → [Install plugin] → ⌃⌥c → ⎋ → <restart>
```

NOTE: No need to set schema as we’ll be using a different one.

### Editor Schema manual from here
Find plugin
Open IDE and locate File >> Settings >> Plugins and click Browse Repositories…
Search for and click ChroMATERIAL and click Install plugin
Use Color Scheme
```
Locate File >> Settings >> Editor >> Colors & Fonts >> Scheme
```
Choose ChroMATERIAL and click Apply/OK.
 tl;dr: ⌘⇧a → "Plugins" → ↩ → ⌃⌥b → <search> → "ChroMATERIAL" → [Install plugin] → ⌃⌥c → ⎋ → <restart> → ⌘⇧a → "Color Scheme" → [3. ChroMATERIAL] → ↩

### HOLO Logcat
Type	Color
verbose:	#BBB
debug:	#33B5E5
info:	#9C0
assert:	#A6C
error:	#F44
warning:	#FB3
Go to Preferences → Editor → Colors & Fonts → Android Logcat,
Make sure that ChroMATERIAL is selected in dropdown, and click Save as…,
Choose a name ex. ChroMATERIAL + HOLO and confirm with OK,
Click on each item from the list in the center and change their Foreground color to the one from table above,
Click Apply/OK.
```
 tl;dr: ⌘⇧a → "Android Logcat" → [Save as...] → "ChroMATERIAL + HOLO"¹ → ↩ → <set foreground colors as in the table ↑> → ⎋
```


and as always thanks for reading
