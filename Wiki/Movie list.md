# Movie list

## Simple Movie catalog

![movie–02](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/9379154c-41b0-4e04-b7e8-6263232a85d3)
![movie–03](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/ba18c607-0e57-4f84-8054-5fa020307a84)

```
---
cssclass: movies, align-a, h1-7, fade
tags: 
---
```

my goal was to build a compact Movie list / overview to remember watched movies, or to bookmark movies i would like to watch. I love good entertainment but i do not study movies, so i keep informations pretty basic. This simple movie-catalog should help you skim through your favorites and movies you want to watch in future. To start with, add some basic descriptions (of course you can add much more informations if you wish):

- cover image,
- title and year (ideally a link to iMDB, eg. [Dune (1984)](https://www.imdb.com/title/tt0087182/)) plus a footnote (to display the plot, stars)
- duration,
- genre
- director
- rating

### Usage
1) to add descriptions to your movie table visit the Internet Movie Database: https://www.imdb.com/ 
2) next, add a cssclass to your yaml header, use `cssclass: movies`
3) finally, use this template:

```
|          |                                          |                                          |                                          |                                          |
| -------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| cover    | ![[pict-1.jpg]]                          | ![[pict-2.jpg]]                          | ![[pict-3.jpg]]                          | ![[pict-4.jpg]]                          |
| title    | [Title (Year)](https://movie.url) [^pca] | [Title (Year)](https://movie.url) [^pca] | [Title (Year)](https://movie.url) [^pca] | [Title (Year)](https://movie.url) [^pca] |
| duration | 100 min                                  | 100 min                                  | 100 min                                  | 100 min                                  |
| genre    | #tag1 #tag2 #tag3                        | #tag1 #tag2 #tag3                        | #tag1 #tag2 #tag3                        | #tag1 #tag2 #tag3                        |
| director | Name                                     | Name                                     | Name                                     | Name                                     |
| rating   | ⭐️                                       |  ⭐️                                      |  ⭐️                                      |  ⭐️                                      |
```

- **first column**: As you can see, the very first column is just a guide to tell you what information to enter on the right side. This column won't show up in rendered tables. 
- **cover**: add your locally stored picture with `![[your-picture.jpg]]` followed by a footnote link `[^pic]` TIP: to add unique footnote id's, use the first 3 initials or use the first 3 characters of your movie title. At bottom page then, write:  `[^pic]: pasted story plot` to add your plot.
- since Obsidian does not support popover preview for footnotes, get [obsidian-better-footnotes](https://github.com/jancbeck/obsidian-better-footnotes) by aidenlx this way you can read plots directly from your footnote link (open-book icon), my theme will append automatically an open-book icon before your footnote description in your movie list 
- **title**: add movies name followed by their release year, eg. `[MovieName (Year)]` and after, append a weblink of your choice, eg iMdb, this would look like so: `[MovieName (Year)](https://www.imdb.com/title/id/)`. 

Example: [Dune (1984)](https://www.imdb.com/title/tt0087182/). 

> **Tip**: you can stack movie templates with an empty line above and below templates, if you want to have a 2nd, 3rd or more rows

<br>

### Working with tables

Tables in markdown are, what they are, just get used to it.
However, to simplify your task with tables, i suggest you to:
- toggle on `Source mode`
- get [Advanced-tables-obsidian](https://github.com/tgrosinger/advanced-tables-obsidian) by tgrosinger to work with tables. With this plugin on, you will enjoy working with tables :)
- if you want to add more informations to your movie table, remember to put a short description of your new preset in the very first column of the movie table template above

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
