### Banner

```
---
cssclass: banner-a,
---
```
`![[Pict.jpeg|banner-a]]`

**Options**: banner-a, banner-b

to add a neat banner, you must define both `cssclass` AND `alt name`. 

**Vertical placement**

To adjust your **b**anner **c**oordinates vertically 
- locally: use 6 different sizes (10, 20, 30, 40, 50, 60), eg. `cssclass: bc-10` 
- globally: see **Style Settings>Dune>Pictures>Zoom Pictures>Banner vertical placement** 

<br>

### Portrait, Avatar, Round

`![[Pict.png|portrait]]`, `![[Pict.png|avatar]]`,  `![[Pict.png|round]]`


![I-02](https://user-images.githubusercontent.com/48620536/222981873-06037136-9876-45eb-b0a8-468ed5227443.png)

<br>

### Left, Right and Center side

`![[Pict.png|pos-l]]`, `![[Pict.png|pos-r]]`, `![[Pict.png|pos-c]]`

place your images on the Left, Right or at the Center of your note

<br>

### Picture Frames

`![[Pict.png|frame-a]]` 

Options: a-d

Frame your pictures. Download some frames like [this png template](https://pngimg.com/image/91008). Customize your frames under **Style Settings>Dune>Pictures>Picture frames**

![I–03](https://user-images.githubusercontent.com/48620536/222982094-4943ac34-34be-4587-8365-78408b671aff.png)

<br>

### Simple Frames

`![[Pict.png|frame-s]]`
 
Change picture frame colors under **Style Settings>Dune>Colors>Extra colors>** and adjust frame thickness in **Style Settings>Dune>Pictures>Frame (simple)**

![I–04](https://user-images.githubusercontent.com/48620536/222982126-2f17ba6c-9df1-4d13-8bad-9738f3072cc6.png)

<br>

### Book pictures

```
> [!framed-l] 
>  ![[Pict.png|frame-b | 250]]
>  description
```
**Options**: framed-r, framed-l

position your images, add a picture frame and description 

![I–05](https://user-images.githubusercontent.com/48620536/222982159-2f481d4c-634e-491f-9ac6-8b73ecbda539.png)

<br>

### Simple description

`![[Pict.png#cap|capture]]`

![I–06](https://user-images.githubusercontent.com/48620536/222982200-63caf748-6a65-42e3-a927-f262103943e6.png)

<br>

### Moodboard

```
> [!moodboard]
> ![[pic1.jpeg]] ![[Pict2.jpeg]]![[Pict3.jpeg]]
> 
> ![[Pict4.jpeg]] ![[Pict5.jpeg]] ![[Pict6.jpeg]] 
> 
> ![[Pict7.jpeg]] ![[Pict8.jpeg]] ![[Pict9.jpeg]] 
```
![I-10](https://user-images.githubusercontent.com/48620536/223212661-17a473b1-8151-4aac-b558-42c7fafe59a1.jpg)

**Options**: Configure height and width, see **Style Settings>Pictures>Image Wall**

the more pictures you put in a picture wall, the more your picture wall will look seamless. To remove empty spaces and get a neat-looking picture wall, (see **Style Settings>Dune>Pictures>Image Wall**) and adjust H/W sliders accordingly. Remember to keep an empty line between each line of pictures. 

<br>

### Simple Movie catalog

![Mov-coll-2](https://user-images.githubusercontent.com/48620536/225926038-afdc2964-60b9-4afd-9472-0f1057d99a49.png)

my goal was to build a compact Movie list / overview to remember watched movies, or to bookmark movies i would like to watch. I love good entertainment but i do not study movies, so i keep informations pretty basic. This simple movie-catalog should help you skim through your favorites and movies you want to watch in future. To start with, add some basic descriptions (of course you can add much more informations if you wish):

- cover image,
- title and year (ideally a link to iMDB, eg. [Dune (1984)](https://www.imdb.com/title/tt0087182/)),
- duration,
- director
- rating

#### Usage
1) to add descriptions to your movie table visit the Internet Movie Database: https://www.imdb.com/ 
2) next, add a cssclass to your yaml header, use `cssclass: mov-strip`
3) finally, use this template:

```
|          |                                   |                                   |                                   |                                   |
| -------- | --------------------------------- | --------------------------------- | --------------------------------- | --------------------------------- |
| cover    | ![[pict-1.jpg]][^pca]             | ![[pict-2.jpg]][^pcb]             | ![[pict-3.jpg]][^pcc]             | ![[pict-4.jpg]][^pcd]             |
| title    | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) |
| duration | 100 min                           | 100 min                           | 100 min                           | 100 min                           |
| genre    | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 |
| director | Name                              | Name                              | Name                              | Name                              |
| rating   | ⭐️                                |  ⭐️                               |  ⭐️                              |  ⭐️                               |
```

- **first column**: As you can see, the very first column is just a guide to tell you what information to enter on the right side. This column won't show up in rendered tables. 
- **cover**: add your locally stored picture with `![[your-picture.jpg]]` followed by a footnote link `[^pic]` TIP: to add unique footnote id's, use the first 3 initials or use the first 3 characters of your movie title. At bottom page then, write:  `[^pic]: pasted story plot` to add your plot.
- since Obsidian does not support popover preview for footnotes, get [obsidian-better-footnotes](https://github.com/jancbeck/obsidian-better-footnotes) by aidenlx this way you can read plots directly from your footnote link (open-book icon), my theme will append automatically an open-book icon before your footnote description in your movie list 
- **title**: add movies name followed by their release year, eg. `[MovieName (Year)]` and after, append a weblink of your choice, eg iMdb, this would look like so: `[MovieName (Year)](https://www.imdb.com/title/id/)`. 

Example: [Dune (1984)](https://www.imdb.com/title/tt0087182/). 

<br>

#### Working with tables

Tables in markdown are, what they are, just get used to it.
However, to simplify your task with tables, i suggest you to:
- toggle on `Source mode`
- get [Advanced-tables-obsidian](https://github.com/tgrosinger/advanced-tables-obsidian) by tgrosinger to work with tables. With this plugin on, you will enjoy working with tables :)
- if you want to add more informations to your movie table, remember to put a short description of your new preset in the very first column of the movie table template above

<br>

### Zoom Svg diagrams

Options: (phone) `cssclass: svg-50` ,  `cssclass: svg-100` 

Options: (desktop) svg-50, svg-100, svg-150, svg-200. eg. `cssclass: svg-50` 

to zoom in **mermaid diagrams**, adjust your zoom size, see options above. Embedded diagrams and phone diagrams may require smaller sizes, (eg. svg-50) meanwhile notes with diagrams only require bigger sizes, (eg. svg-150 or svg-200). 

Activate automatic-zoom in **Preferences>Style Settings>Dune>Pictures>Zoom Pictures>Zoom on hover**
Otherwise click and hold over an image

### Zoom Pictures

just hover and click, hold click. Otherwise, activate automatic zoom in **Preferences>Style Settings>Dune>Pictures>Zoom Pictures>Zoom on hover**

<br>

### Video resized 

`![[video.mp4|vid-20]] `

**Options**: 
- smaller - 20, 30, 40, 50
- bigger -120, 150, 200

![I-08](https://user-images.githubusercontent.com/48620536/222982358-5d0eefcd-435a-4871-b73f-dcb46f973c96.png)
