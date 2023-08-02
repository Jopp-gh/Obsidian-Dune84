# Pictures
## Banner

```
---
cssclass: banner-a,
---
```
`![[Pict.jpeg|banner-a]]`

<br>

**Options**: 
- (big banner) `banner-a`
- (small banner) `banner-b`

**Note**
<br>
to add a neat banner, you must define `banner-a` or `banner-b` twice, for both `cssclass` AND `alt name` 

<br>

### Banner, vertical placement

To move your Banner vertically, change your **b**anner **c**oordinates accordingly: 
- **locally**: use 8 different placements in your yaml header (10, 20, 30, 40, 50, 60, 70, 80), eg. `cssclass: bc-10` 
- **globally**: see **Style Settings>Dune>Pictures>Zoom Pictures>Banner vertical placement** 

<br>

## Portrait, Avatar, Round

![I-02](https://user-images.githubusercontent.com/48620536/222981873-06037136-9876-45eb-b0a8-468ed5227443.png)

`![[Pict.png|portrait]]`, `![[Pict.png|avatar]]`,  `![[Pict.png|round]]`

<br>

### Left, Right and Center side

`![[Pict.png|pos-l]]`, `![[Pict.png|pos-r]]`, `![[Pict.png|pos-c]]`

place your images on the Left, Right or at the Center of your note

<br>

## Picture Frames

![I–03](https://user-images.githubusercontent.com/48620536/222982094-4943ac34-34be-4587-8365-78408b671aff.png)

`![[Pict.png|frame-a]]` 

**Options**: `frame-a`, `frame-b`, `frame-c`,`frame-d`

Frame your pictures. Download some frames like [this png template](https://pngimg.com/image/91008). Customize your frames under **Style Settings>Dune>Pictures>Picture frames**

<br>

### Simple Frames

![I–04](https://user-images.githubusercontent.com/48620536/222982126-2f17ba6c-9df1-4d13-8bad-9738f3072cc6.png)

`![[Pict.png|frame-s]]`
 
Change picture frame colors under **Style Settings>Dune>Colors>Extra colors>** and adjust frame thickness in **Style Settings>Dune>Pictures>Frame (simple)**

<br>

## Book pictures

![I–05](https://user-images.githubusercontent.com/48620536/222982159-2f481d4c-634e-491f-9ac6-8b73ecbda539.png)

```
> [!framed-l] 
>  ![[Pict.png|frame-b | 250]]
>  description
```
**Options**: `framed-r`, `framed-l`

position your images, add a picture frame and description. 
If you want a soft background for text and images inside **Book Pictures**, add bg as metadata, after the pipe symbol, eg `>[[!framed | bg]]`  

<br>

## Simple description

![I–06](https://user-images.githubusercontent.com/48620536/222982200-63caf748-6a65-42e3-a927-f262103943e6.png)

`![[Pict.png#cap|capture]]`

<br>

## Moodboard

![I-10](https://user-images.githubusercontent.com/48620536/223212661-17a473b1-8151-4aac-b558-42c7fafe59a1.jpg)

```
> [!moodboard]
> ![[pic1.jpeg]] ![[Pict2.jpeg]]![[Pict3.jpeg]]
> 
> ![[Pict4.jpeg]] ![[Pict5.jpeg]] ![[Pict6.jpeg]] 
> 
> ![[Pict7.jpeg]] ![[Pict8.jpeg]] ![[Pict9.jpeg]] 
```

**Options**: Configure height and width, see **Style Settings>Pictures>Image Wall**

the more pictures you put in a picture wall, the more your picture wall will look seamless. To remove empty spaces and get a neat-looking picture wall, (see **Style Settings>Dune>Pictures>Image Wall**) and adjust H/W sliders accordingly. Remember to keep an empty line between each line of pictures. 

<br>

## Zoom Pictures
### Zoom Svg diagrams


**Options**: svg-20, svg-30, svg-40, svg-50, svg-60, svg-70, svg-80. eg. `cssclass: svg-50` 

to zoom in **mermaid diagrams**, adjust your zoom size, see options above. Embedded diagrams and phone diagrams may require smaller sizes, (eg. svg-50) 

Activate automatic-zoom in **Preferences>Style Settings>Dune>Pictures>Zoom Pictures>Zoom on hover**
Otherwise click and hold over an image


<br>

### Video size 

![I-08](https://user-images.githubusercontent.com/48620536/222982358-5d0eefcd-435a-4871-b73f-dcb46f973c96.png)

`![[video.mp4|vid-20]] `

**Options**: 
<br>
- smaller `vid-20`, `vid-30`, `vid-40`, `vid-50`
- bigger `vid-120`, `vid-150`, `vid-200`


---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
