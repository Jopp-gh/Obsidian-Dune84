# Folders

## Folders Icons

to use **folder icons**, *add special keywords* to folder names, eg. `Project`, `Area`, `Resources`, `Archive`

### Usage
1. To get started, download [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) first.
2. Then [install it](https://help.obsidian.md/Extending+Obsidian/CSS+snippets), 
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
use following *name convention* : 
) `folderName keyword`  eg. "Test Project" 


>**Tip**
>- if you add multiple words for a folder name, put your *keyword* **last**
>- **Folders Icons** is an extension of Dune, so you can display the icons you like with the keywords you want. 
>- Keywords are case sensitive, eg. "project" is not the same as "Project"

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

1. First of all, open `folder-icons-v2.css` in a text editor of your choice. consider this snippet is organized in 2 parts: the top section holds all icons , followed by the ruleset section.
2. now search for "Journal" in the rulesets and replace that name with a  name of one (1) of your folders
3. open the command palette `cmd+p` on Mac, should be `ctrl+p` on Win/Linux and type "reload" for "reload app without saving" . 

> Note, you can assign Multiple Names to an icon. See again the example rule for "--openbook-icon". This is one ruleset -block:

#### Let's look at an example
the following ruleset contains: "Journal", "Education" and "Training".
```
/* Journal, Education, Training */
.nav-folder-title:is([data-path$="Journal"], [data-path$="Education"], [data-path$="Training"]) .nav-folder-title-content::after {
    content: var(--openbook-icon);
}
```

For simplicity, I renamed my folders to A, B and C:
```
.nav-folder-title:is([data-path$="A"], [data-path$="B"], [data-path$="C"]) .nav-folder-title-content::after {
    content: var(--openbook-icon);
}
```

Now if you don't like the icon given to A, B and C, search the top part of my snippet for another icon-name (example --bookmark-icon) and replace the content of: `var(--openbook-icon);` with: `content: var(--bookmark-icon);`


---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
