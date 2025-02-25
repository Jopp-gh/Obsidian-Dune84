## Troubleshooting

### Check your installation
1. Download/update and activate the **Style settings** plugin. *Please don't miss this step*
2. Download/update Dune
3. Download/update Dune's *optional* companion snippets (Dune's mermaid theme, Dune's supported plugins) 


### Dune's preferences - too many steps
Install and activate mgmeyers' `Style Settings` plugin, then open the command palette with `Ctrl+P` (Win, Linux) or `Cmd+P` (Mac) and type `style settings` . You will get a suggestion with `style settings: show style settings view` , just confirm to open Style settings as a note. Next, grab Style Setting's tab and drag this window to the right or left side panel of Obsidian. From now on, you can tweak Dune's interface to your hearts content, Nice!

### Unable to access Obsidian Settings (phone)
to access Obsidian's Settings, open the command palette with a swipe from the top edge of your phone. With the command palette open, type `settings` and confirm the suggestion `Open settings`

### Interface looks odd
A possible cause is an outdated version of Dune.
Yet another cause are incompatible snippets, which try to change the same rules as Dune does. Finally, please check if you need to update Dune's companion snippets, if you use these snippets as well.

Obsidian is growing steadily and Dune needs to adapt to their development progress. Sometimes the changes in Obsidian are minor, sometimes major and due to these circumstances, some features of Dune may not work as expected or break completely. Please report any bugs.

### Slow interface
Please update Dune to the latest version.
To make sure you're always up-to-date, open in Obsidian `Settings>Appearance>`, then click on `Check for updates`

### Dune hides everything
Open `Dune>Show` to reactivate hidden elements in Dune.
The reason why Dune hides interface elements is to help you focus better. Newcomers should familiarize with Obsidians interface, before they hide or deactivate something. Anyway, user interface elements like buttons or icons in Dune don't disappear completely and will re-appear sharply if you move your mouse over them.

### Large margins
if you experience large margins, try to deactivate `Settings>Editor>Readable line lenght` as this option is usually on by default. An "improved" implementation of readable line length is Dune's *Zen view*. Please see `Dune>Show>Zen view`.

### Large/small fonts
Reset font size to defaults in `Dune>Fonts>Typesets` and `1 - Modern` or `2 - Poetry` or `3 - Dashboard` with the slider `Custom Font size` or press the reset button at the line end.

### Emojis turn into black/white blotches (pdf)
this bug is font related and Dune is unable to solve the underlying problem. Check out Obsidian without Dune and you will see the same bug.

### Problems with fonts
Style Settings does a good job but fonts are not always displaying correctly. To remedy and see your favorite fonts, open first `Dune>Fonts` . In there, delete and re-enter some letter in the input fields to refresh fonts. 

### Theme falls back on default black / white
This issue seems related to newer versions of Obsidian starting from Obsian v1.7.x and up. Please try the following steps:
1. open `Dune>Colors>Theme` and switch to another color scheme. 
2. if switching didn't help, deactivate and reactivate **Style Settings**
3. if the problem persists, try to reload Obsidian. 

### Typesetting cssclasses
Typesetting **cssclasses** `ftheme-1`, `ftheme-2`, `ftheme-3` applies only to the current note and to Preview View. Sometimes fonts are pretty artistic and hard to read, therefore fonts are only visible in Preview view. This behaviour gives you two benefits: edit your text in a easy-to-read format and preview and then print your writing in any font you like.
### Callout framed-a
If typesetting alignment is set to justified, the callout `framed-a` won't align to the center.

### Problems with colors
if Dune is unable to display custom colors, go to `Dune>Colors`, click on the problematic color and then press `Save`. Alternatively, click the `Restore default` Button. This should refresh Dune's color palette as well.

### Other Issues
Check your CSS snippets under `Settings>Appearance>CSS snippets` and deactivate them all to see if this solves your issue.
If you're using my companion snippets, try to download them again, just to make sure to have their latest version.

### Bottom toolbar is messed up (phone)
Please check if you have the community plugin **Commander** installed. If so, please change following settings:
Open `Settings>Commander>Mobile Toolbar` and set **Toolbar Row Count** to 4, deactivate **Column Layout**, deactivate **Bottom Offset**, scroll down and under **Advanced Settings** set Button Height as well as Button Width to 30, finally set **Toobar Extra Spacing** to 6. This should give you a nice 3 row x 8 column toolbar layout on conventional phones. 

### Top toolbar buttons (phone)
on phone, the top row is a small and thight space, with title, path bar, the (superfluous) left sidebar button and some more buttons. In addition, you may use some plugins, which add toolbar buttons (example, **Commander plugin** to name a popular one) . These interface elements will clutter and operlap with your notes and make editing much harder at the top page. Additionally, in edit mode Obsidian jumps abruptly to the top, when the keyboard shifts in.
With Dune, the switch between preview mode and edit mode / live preview should be less abrupt and more smooth so you can edit your first line to without worry for buttons or names getting in your way. Also, top toolbar buttons can be semi-opaque to add more space to your notes.

### Note title is always visible (phone)
Just tab on the title field first, then tab somewhere else in your note. This should hide your note title.

### Locked in Canvas view (phone)
to exit from canvas view, click on the bottom-right tab button to exit from canvas view and change to another tab. 

### Dune starts with a white band on top (phone)
This issue is outside of Dune's control and needs a better implementation of Obsidians code itself. A workaround is to re-apply the light or dark theme with the command palette, type `light` / `dark` and choose the right autosuggestion choice.

### Too many open tabs (phone)
if you've a lot of open tabs, you may want to deactivate tab previews to scroll less. Dune offers you a compact tab view, just go to `Dune>Main Window>Slim bars (Phone & Desktop)`

### Exit from zoomed view (phone)
To exit from zoomed images, tab on the left of right edge of your phone screen.

### Dune Silver - Dune Gold
**Dune-Silver** is free and comes already with a lot of features on top of stylistical changes. To make *Dune - a theme for Obsidian* not just **future-proof** but much more important, **sustainable**, I've split the future development of Dune into two branches, one in a free and one in a paid tier. Dune Gold is packed with many more features than the free version.

In the past 3 years I've spent many hundreds of hours of continuous work in research, design, development and implementation of features, debugging and fixing issues in Dune. Also, Dune - a theme for Obsidian works on desktop pc's (Mac/Linux/Windows) and phone (Android) devices, so the effort to maintain this theme isn't trivial.

*Only maintenance guarantees that all of Dune's features work always as expected.* 

<a href="https://www.buymeacoffee.com/jopp.gh" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-violet.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
