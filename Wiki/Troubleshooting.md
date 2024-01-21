## Troubleshooting
### Dune hides everything
Make sure to _install_ and _activate_ the **Style Settings** plugin to access all features of Dune. Otherwise, Dune won't work correctly.

### Left toolbar / ribbon is gone
Open the command palette with `Ctrl+P` (Win) or `cmd+P` (Mac) and type `setting`, then pick the command `Open Settings`. In Settings, scroll down on the left column from `Options`, to `Core plugins` and finally to `Community plugins`, where you will find all loaded plugins. Look for `Style Settings` - if Style Settings is not available in your plugin list, scroll up and go to `Options>Community plugins>Search installed plugins`, then type `Style Settings`. Activate Style Settings and go to `Community plugins>Style Settings>Dune>Show UI Elements`. Search for `Sidebar, left` in `Main window` (older versions of Dune) or `Extra toggles`(newer versions of Dune). Finally, use the toggle nearby to reveal the left sidebar / ribbon.

### Quick configuration
Have `Style Settings` installed, then open the command palette and type `style settings` to reveal `style settings: show style settings view` and confirm. Now, Style settings will open in your main window. Pick its tab and drag this window to your right / left side dock. From now on, you can explore and tweak Dune's interface to your heart's content !

### Something is missing in Dune's interface
Open `Settings>Style Settings>Dune>Show ui elements`to reveal elements in Obsidians interface hidden by default in Dune. Dune hides elements to help you focus. Beginners need to familiarize with Obsidian first, therefore feel free to restore anything or all you are missing in Dune's interface.

### Slow interface
Please use the latest version of **Obsidian**, **Style Settings** and **Dune**. Otherwise you will experience strange glitches or slowdowns.

### How to change the accent color 
if you use the default flat light / flat dark theme of Dune, navigate to `Settings>Appearance>Accent color` and change the accent color as you would do normally. 

### Problems with margins
is there a big margin on the left side of your note? try to deactivate `Settings>Editor>Readable line lenght` as it is on by default.

### Problems with fonts
open `Settings>Style Settings>Dune>Fonts` and then look for font settings (**Typesets / Extra Fonts / Special Header Fonts**) . In there, delete and re-enter some Character in the input fields to refresh fonts. Alternatively, click the `Restore default` Button at the end of the input field.

### Problems with colors
if Dune is unable to display some color, try to find the missing one under `Settings>Style Settings>Dune>Colors`, click on it and press `Save`. Alternatively, click the `Restore default` Button.

### Stuck in Dune's anonymized interface?
Open Obsidians Settings and pay attention, there is a colum on the left with a larger area on the right. Now click in the column on some lines. You will see that Dune reveals the name of Options if you click on them. Check the first letter of "some extension" to understand where in the alphabet you are. **Style Settings** begins with **S** and must be somewhere at the bottom of your extension list. Just click through the Extensions till you find **Style Settings**. In there, expand the last section (second last section in newer versions of Dune) to find **Hide App UI** . Deactivate the toggle nearby.

### Interface issues on tablets
Send me some screenshots and a clear description of your issue and I'll try to fix your issue. Since I don't have a tablet myself, be precise and patient.

### Something else
open a bug report and I will see if I can fix your issue. Please explain in easy-to-follow step-by-step examples how to reproduce your bug. You can add screenshots as well.

### Known issues
**left sidebar toggle broken**
The left sidebar button in Obsidian's main window is inactive in fullscreen-mode when the left ribbon `Sidebar, left` is hidden. . If time permits, I will fix it in future.

A workaround is to assign a keyboard shortcut and go to `Settings>Shortcuts`, search for `toggle left sidebar` and assign a shortcut easy to remember, for example: `shift+ctrl+arrow left`.
