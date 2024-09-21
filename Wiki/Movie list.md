# Movie list

## Simple Movie catalog
![movie–02a](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/a2d84e6f-e6a9-44f7-ab82-8a94a5f0b767)

```
---
cssclass: movies
tags: 
---
```
>legend: 
>- movies = loads this **movies** layout
>- fade = adds some horizontal lines to relax multiple tables in a nicer layout on the same page

my goal was to build a compact Movie list / overview to remember watched movies, or to bookmark movies i would like to watch. I love good entertainment but keep informations pretty basic. This simple movie-catalog should help you skim through your favorites and movies you want to watch in future. To start with, add some basic descriptions (of course you can add much more informations if you wish):

### Table layout

- cover image (recommended)
- title and year (Dune (1984) or just the title plus a footnote reference (to display the plot, actors, etc)  (recommended)
- duration 
- genre
- director
- rating  (recommended)

### Usage
1) to add details to your movie table, visit the Internet Movie Database: https://www.imdb.com/ 
2) next, add a **cssclass**, eg `cssclass: movies, h1-7` to your yaml header
3) optinally, set a special font for your movie title, go to: `Dune>Fonts>Extra Fonts>Special Header Font>Header - Movies`
4) finally, use this template:

```
|          |                      |                      |                      |                      |
| -------- | -------------------- | -------------------- | -------------------- | -------------------- |
| cover    | ![[pict-1.jpg]]      | ![[pict-2.jpg]]      | ![[pict-3.jpg]]      | ![[pict-4.jpg]]      |
| title    | Title (Year) [^1]  | Title (Year) [^2]  | Title (Year) [^3]  | Title (Year) [^pca]  |
| duration | 100 min              | 100 min              | 100 min              | 100 min              |
| genre    | #tag1 #tag2 #tag3    | #tag1 #tag2 #tag3    | #tag1 #tag2 #tag3    | #tag1 #tag2 #tag3    |
| director | Name                 | Name                 | Name                 | Name                 |
| rating   | ⭐️                   | ⭐️                   | ⭐️                   | ⭐️                   |
```

**first column**: 
As you can see, the very first column is special and just a guide to tell you what information to enter on the right hand side. The first column won't show up in rendered tables (only visible in `source mode`).

<br>

1. **cover**: add a local cover picture, eg `![[your-picture.jpg]]` 
2. **title**: add a movie name, ideally followed by the release year and a footnote to read plots eg. `MovieName (Year) [^1]` 
3. **duration, genre, director and rating** are optional values. You can remove some or all of these rows altogether or replace them with values you prefer 
4. **expand** your movie table with more rows for more keywords,  or add another movie table below (keep at least an empty line between tables). Just remember to put a short description in the very first column in your movie table template

> **TIP**: add as many columns as you like, for a clean overview i suggest 4 in a row for phone and 6 to 8 movies in a row for desktop pcs.

<br>

### Zoomed view 

![movie–03](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/ba18c607-0e57-4f84-8054-5fa020307a84)

zoomed view (press and keep left mouse button)



---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
