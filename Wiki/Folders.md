# Folders

## Folder colors
![fold-col_400Px](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/968f3fff-18a3-4128-8602-e1f27b907039)

to add or change folder colors, choose a number from 0-9 (see figure 1 above) 
Just rename your folder with a `color-id` and add a `space` followed by a `name of your choice.`

<br>

### Example
- add a *single-digit number* in front of your folder name, eg. add "4"in front of `Archive` (please see picture below) separated by a `space`
- After you renamed a folder with a `color-id`, this id will be hidden until you rename it again

![Folder colors-2](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/460ec1dd-484e-4787-89f2-9e4bb3f6b09b)

now lets combine both `colorID` and `keywords`:

`1 Project`, `2 Area`, `3 Resources`, `4 Archive`

**Tip**
- Just make sure to add a valid number 
- the first character must be single digit
- add an `empty space` or `hyphen`to divide your `color-id` from the "real name" of your folder, eg. `Color-id Foldername`

<br>

## Folders Icons

![Folder colors](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/b3474617-369d-4f66-82c5-e37aa12a9c0b)

to use **folder icons**, *add special keywords* to folder names, eg. `Project`, `Area`, `Resources`, `Archive`

### Usage
1. To get started, download [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) first.
2. Then [install that snippet](https://help.obsidian.md/Extending+Obsidian/CSS+snippets), 
3. pick a random keyword from the list below (notice, keywords which share the same icon are separated with a slash "/"): 

- Workbench
- Journal / Training / Education
- Design / Draft
- Read
- Project
- Responsibility / Area
- Resources
- Archive
- Portfolio
- Photo
- Software / Linux / Mac / Win
- Entertainment / Movie
- Study / Research
- Contact
- Society / Social
- Health
- Network
- Travel
- Sport
- Language
- Code / Shell
- Game

<br>

### In practice
to add *colors* AND *icons* to your folders, use following *name convention* : 
<br>
a) `colorID keyword`  eg. "1 Project"
<br>
b) `colorID JohnnyDecimalNumber folderName keyword`  eg. "1 30 Test Project" 


>**Tip**
>- if you add multiple words to a folder name, your *keyword* **must be last**
>- **Folders Icons** is an extension of Dune, because this way you can display the icons you like with the keywords you need. 
>- Keywords are case sensitive, this means, if you add eg. "project" instead of "Project", then keywords won't work.

<br>

### Expand your Iconset
Check the [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) snippet and make changes as you see fit. 
You can add or remove keywords, change keywords to lowercase and change or remove icons. Find a list of available icons in [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) or add new icons by yourself, check out icon websites like: https://lucide.dev

<br>

### Change Icons and Folder names
to display icons you need to modify my snippet. All you need to know is:
- your folder names 
- assign an icon to this folder names

<br>

1. First of all, open `folder-icons-v2.css` in a text editor of your choice. consider this snippet is organized in 2 parts: the top section stores all available icons and afterwards follows the ruleset section.
2. now search for "Journal" down below in the rulesets and replace that name . You've to replace this name twice, because of the "light" and "dark" theme. Replace "Journal" with a name of one (1) of your folders
3. open the command palette `cmd+p` on Mac, should be `ctrl+p` on Win/Linux and type "reload" for "reload app without saving" . On restart, you folder should have an icon now.

> Note, you can assign Multiple Names to an icon. See again the example rule for "--openbook-icon". This is one ruleset -block:

#### Let's look at an example
the following ruleset contains: "Journal", "Education" and "Training".
```
/* Journal, Education, Training */
body:not(.is-mobile).theme-dark .tree-item-self.is-clickable.nav-folder-title:is([data-path$="Journal"], [data-path$="Education"], [data-path$="Training"]):hover>.tree-item-inner.nav-folder-title-content::after {
    filter: inherit;
}

.nav-folder-title:is([data-path$="Journal"], [data-path$="Education"], [data-path$="Training"]) .nav-folder-title-content::after {
    content: var(--openbook-icon);
}
```

For simplicity, I renamed my folders to A, B and C:
```
body:not(.is-mobile).theme-dark .tree-item-self.is-clickable.nav-folder-title:is([data-path$="A"], [data-path$="B"], [data-path$="C"]):hover>.tree-item-inner.nav-folder-title-content::after {
    filter: inherit;
}

.nav-folder-title:is([data-path$="A"], [data-path$="B"], [data-path$="C"]) .nav-folder-title-content::after {
    content: var(--openbook-icon);
}
```
Now if you don't like the icon given to A, B and C, search the head part of my snippet for another icon-name (example --bookmark-icon) and replace the content of: `var(--openbook-icon);` declaration with: `content: var(--bookmark-icon);`

<br>

## Interacting with folders

if you enabled a banner or squared profile picture, [drag n drop](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/Wiki/Profile.md#drag-n-drop-area) folders and files over your Profile and a blue drop area will appear

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
