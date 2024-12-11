# PICTURES
## BANNER

```
---
cssclass: banner-a,
---
```
`![[picture.jpg | banner-a]]`

<br>

there are 3 banner types:

- banner-a (**top** banner, height adjustable in **Style Settings**)
- banner-b (**bottom** banner, height adjustable in **Style Settings**)
- banner-m ( **everywhere** on your page, placeholder for decorations, height is fixed)

<br>

to insert a top or bottom -page banner, choose a banner type (eg `cssclasses: banner-a` or `cssclasses: banner-b`) to reserve a top/bottom spot, then add the same tag `banner-a` to your image metadata, eg. `![[picture.jpg | banner-a]]` to transform your image into a banner.
Banner `banner-m` doesn't need a cssclass, just add `![[picture.jpg | banner-m]]` to your picture. 

>Note :
>to get **bottom banners** working, put your image at bottom page, so Obsidian and Dune know where to load your banner. Do not put a footer banner `![[picture.jpg | banner-b]]` at top page, unless your note is very short.

<br>

### Banner height 
to configure your banner height (`cssclass: banner-a` or `cssclass: banner-b`), go to: `Dune>Pictures>Banners>Resize Banner` . Banner `banner-m` has a fixed height.

<br>

### Banner, vertical shift
only for `banner-a`

If your top banner looks truncated, you can use **b**anner **c**oordinates: 
- **locally**: use 15 different placements in your yaml header (10, 20, 30, 40, 50, 60, 70, 80), eg. `cssclass: bc-10` and median values, eg. `cssclass: bc-15`

<br>

## PICTURE LAYOUT

![I-02](https://user-images.githubusercontent.com/48620536/222981873-06037136-9876-45eb-b0a8-468ed5227443.png)

`![[Pict.png | portrait]]`, `![[Pict.png|avatar]]`,  `![[Pict.png|round]]`

**Deutsch**: `![[bild.png|rund]]`


<br>

### IMAGE POSITION

`![[Pict.png | pos-l]]`, `![[Pict.png | pos-r]]`, `![[Pict.png | pos-c]]`

place your images on the **Left**, **Right** or at the **Center** of your note

<br>


## IMAGE FRAMES
### SIMPLE IMAGE FRAMES

![I–04](https://user-images.githubusercontent.com/48620536/222982126-2f17ba6c-9df1-4d13-8bad-9738f3072cc6.png)

**Options**: `![[Pict.png | frame-s1]]`, `![[Pict.png | frame-s2]]`

**Deutsch**: `![[bild.png | rahmen-s1]]`, `![[bild.png | rahmen-s2]]`

Change picture frame colors under **Style Settings>Dune>Pictures>Picture frames**

### SIMPLE IMAGE GRID

![Img-grid](https://github.com/user-attachments/assets/dbef3eb5-1229-46f2-9b8b-3f72c82b3d8d)

**Cssclass**: `grid-10, grid-20, grid-30, grid-40, grid-15, grid-25, grid-35, grid-45`

Perfect to arrange any pictures on your page. Pictures will use all the same height and keep the full aspect ratio.
Just throw in all your images and forget to fiddle around with spacings or new line breaks between images. 

<br>

### BEAUTIFUL IMAGE FRAMES

![I–03 (Kopie)](https://github.com/user-attachments/assets/147f2ddf-47cb-49d3-895d-fc9c2a9fd5a0)


**Options**: `![[Pict.png | frame-a]]`, `![[Pict.png | frame-b]]`

**Deutsch**: `![[bild.png | rahmen-a]]`, `![[bild.png | rahmen-b]]`

To apply beautiful frames, you need to use a online url pointing to a png frame. Unfortunately, Obsidian restricts users from loading local images into **Style Settings** for security issues. 
Sidenote. 

<br>

## BOOK PICTURES
![I–05](https://github.com/user-attachments/assets/c653b175-3fad-43b4-9260-40288641a57b)

```
> [!pict|l] 
>  ![[Pict.png | frame-b | 250]]
>  description
```
**Options**: `> [!pict|l]`, `> [!pict|r]`

**Deutsch**: `> [!bild|l]`, `> [!bild|r]`

place your images, add a picture frame and description. 


<br>

## SIMPLE IMAGE DESCRIPTION

![Img-capt](https://github.com/user-attachments/assets/35a656e9-9d15-4687-b377-4762db269f72)

`![[Pict.png#cap|capture]]`

you can adjust the max width of "simple descriptions" by adding following cssclass: `capt-10`, `capt-15`, `capt-20`, `capt-25`, `capt-30`, `capt-35`, `capt-40`. 
`capt-10` means max string width is 100px. 

<br>

## VIDEO SIZE

![I-08](https://user-images.githubusercontent.com/48620536/222982358-5d0eefcd-435a-4871-b73f-dcb46f973c96.png)

`![[video.mp4|vid-20]] `

**Options**: 
<br>
- smaller `vid-20`, `vid-30`, `vid-40`, `vid-50`
- bigger `vid-120`, `vid-150`, `vid-200`


---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
