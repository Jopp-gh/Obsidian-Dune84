```
---
cssclass: banner-a,
---
```

`![[Pict.jpeg|banner-a]]`

**Options**: banner-a, banner-b

To add a neat banner, you must define both `cssclass` AND `alt name`. 

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

`![[Pict.png|frame-m]]` `![[Pict.png|frame-s]]`
Change picture frame colors under **Style Settings>Dune>Colors>Extra colors>** 

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

**Options**: Configure height and width under `Style Settings>Pictures>Zoom Pictures`

the more pictures you put in a picture wall, the more you will get a seamless board. To remove empty spaces and get a neat-looking picture wall, see (see **Style Settings>Dune>Pictures>Image Wall**) and adjust sliders accordingly. Keep an empty line between each line of pictures. 

<br>

### Simple Movie catalog

![movie-str](https://user-images.githubusercontent.com/48620536/225897413-b0a210aa-4d0e-4443-a7bc-2c391887ab5e.png)

my goal was to build a compact movie list / movie overview to remember watched movies, or to bookmark movies i would like to watch. I love good entertainment but i do not study movies, so i keep informations pretty basic. This simple movie-catalog should help you skim through your favorites and movies you want to watch in future. To start with, add some basic descriptions (of course you can add much more informations if you wish so):

- cover image,
- title and year (ideally a link to iMDB, eg. [Dune (1984)](https://www.imdb.com/title/tt0087182/)),
- duration,
- director
- rating

#### Usage
1) To add descriptions to your movie table visit https://www.imdb.com/ 
2) First, you need to add a cssclass in your yaml header, use `cssclass: mov-strip`
3) secondly, use this template:

```
|          |                                   |                                   |                                   |                                   |
| -------- | --------------------------------- | --------------------------------- | --------------------------------- | --------------------------------- |
| cover    | ![[pict-1.jpg]][^pca]             | ![[pict-2.jpg]][^pcb]             | ![[pict-3.jpg]][^pcc]             | ![[pict-4.jpg]][^pcd]             |
| title    | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) | [Title (Year)](https://movie.url) |
| duration | 100 min                           | 100 min                           | 100 min                           | 100 min                           |
| type     | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 | #tag1 #tag2 #tag3                 |
| director | Name                              | Name                              | Name                              | Name                              |
| rating   | ⭐️                                |  ⭐️                               |  ⭐️                              |  ⭐️                               |
```

- As you can see, the first column of this template is just a guide to tell you what information to enter. This column will be present as long as you edit your table, but 
a rendered table won't show table header nor the first column. 
- **cover**: add your picture wiki link with `![[your-picture.jpg]]` followed by a footnote link `[^pic]` TIP: use the first 3 initials of your movie title or its first 3 characters to give your footnote link a name. At bottom page, write:  `[^pic]: your story plot` to add your plot.
- **title**: add a descriptive name followed by its release year, eg. `[MovieName (Year)]` and append after a link to your movie on iMdb, eg. `(https://www.imdb.com/title/id/)`. 

Finally, your Title row will look like this: `[Dune (1984)](https://www.imdb.com/title/tt0087182/)[^dun]`. My theme will add automatically the open-book icon before the footnote link to indicate the link to your movie plot

#### working with tables

Tables in markdown are, what they are, just get used to it.
However, to simplify your task with tables, i suggest you to:
- toggle on `Source mode`
- also, get [Advanced-tables-obsidian](https://github.com/tgrosinger/advanced-tables-obsidian) by tgrosinger to work with tables. With this plugin, you will enjoy working with tables :)
- add a short description to your movie table's very first column to remember your new preferences.

<br>

### Video resized 

`![[video.mp4|vid-20]] `

**Options**: 
- smaller - 20, 30, 40, 50
- bigger -120, 150, 200

![I-08](https://user-images.githubusercontent.com/48620536/222982358-5d0eefcd-435a-4871-b73f-dcb46f973c96.png)
