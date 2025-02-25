# Folders

## Folders Icons

>[!important]
>This companion plugin is obsolete by now. I wrote **Folders Icons** years ago, to add icons to folders in absence of suitable plugins. You can still use **Folders Icons** if you want, but I recommend you to download and use the community plugin **Iconic** by Holo

to use **folder icons**, *add special keywords* to folder names, eg. `Project`, `Area`, `Resources`, `Archive`

### Usage
1. To get started, download [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) first.
2. Then [install snippets](https://help.obsidian.md/Extending+Obsidian/CSS+snippets), 
3. pick a random keyword from the list below (notice, keywords which share the same icon are separated with a slash "/"): 

<br>

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
use following *name convention* : `folderName keyword`  eg. "Test Project" 


>**Tip**
>- if you add multiple words to a folder name, put your *keyword* **last**
>- **Folders Icons** is an extension of Dune, so you can display the icons you like with the keywords you want. 
>- Keywords are case sensitive, eg. "project" is not the same as "Project"

<br>

### Expand your Iconset
Check [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) and make changes as you see fit. 
You can add or remove keywords, change keywords to lowercase and change or remove icons. Find a list of available icons on top of [folder-icons-v2.css](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/snippets/folder-icons-v2.css) or add new icons by yourself, check out icon websites like: https://lucide.dev

<br>

### Change Icons and Folder names
to display icons you need to modify my snippet. All you need to know is:
- the folder you want to use 
- the icon you want to use

<br>

1. First of all, open `folder-icons-v2.css` in a text editor of your choice. Consider, `folder-icons-v2.css` is organized in 2 parts: the top section holds all icons , the bottom section holds the rule.
2. now search for "Journal" in the rules and replace that name with a name of one (1) of your folders
3. open the command palette `cmd+p` on Mac, should be `ctrl+p` on Win/Linux and type "reload" for "reload app without saving" . 

<br>

> Note, you can assign Multiple Names to an icon, but not to a folder. 

<br>

## Example
the following rule contains: "Journal", "Education" and "Training".
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

if you don't like the icon given to A, B and C (--openbook-icon), find in the top part of my snippet another icon-name (example --bookmark-icon) and replace the content of: `var(--openbook-icon);` with: `content: var(--bookmark-icon);`


---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
