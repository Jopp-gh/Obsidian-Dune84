# Pictures
## Banner

```
---
cssclass: banner-a,
---
```
`![[picture.jpg | banner-a]]`

<br>

choose between 2 banners types:

- banner-a (top banner, height adjustable in **Style Settings**)
- banner-b (bottom banner, height adjustable in **Style Settings**)

<br>

to insert a banner, choose a banner type (eg `cssclasses: banner-a`) to reserve a top/bottom space, then add the same value `banner-a` to your image metadata, eg. `![[picture.jpg | banner-a]]` to transform your image into a banner.

>Note :
>to get bottom banners working, put your image at bottom page, so Obsidian and Dune know where to load your banner. Do not put a `![[picture.jpg | banner-b]]`-type at top page, unless your note is very short.

<br>

### Banner height 
to configure your banner height (`cssclass: banner-a` or `cssclass: banner-b`), go to: `Preferences>Style Settings>Dune>Pictures>Arrange Pictures>Banners>Resize Banner`  

<br>

### Banner, vertical placement
only for `banner-a`

If your top banner looks cut, you can use **b**anner **c**oordinates: 
- **locally**: use 8 different placements in your yaml header (10, 20, 30, 40, 50, 60, 70, 80), eg. `cssclass: bc-10` 

<br>

## Portrait, Avatar, Round

![I-02](https://user-images.githubusercontent.com/48620536/222981873-06037136-9876-45eb-b0a8-468ed5227443.png)

`![[Pict.png | portrait]]`, `![[Pict.png|avatar]]`,  `![[Pict.png|round]]`

<br>

### Left, Right and Center side

`![[Pict.png | pos-l]]`, `![[Pict.png | pos-r]]`, `![[Pict.png | pos-c]]`

place your images on the **Left**, **Right** or at the **Center** of your note

<br>


### Simple Frames

![I–04](https://user-images.githubusercontent.com/48620536/222982126-2f17ba6c-9df1-4d13-8bad-9738f3072cc6.png)

`![[Pict.png | frame-s]]`
 
Change picture frame colors under **Style Settings>Dune>Colors>Extra colors>** and adjust frame thickness in **Style Settings>Dune>Colors>Extra colors>Frame color**


<br>

## Book pictures

```
> [!framed-l] 
>  ![[Pict.png | frame-b | 250]]
>  description
```
**Options**: `framed-r`, `framed-l`

place your images, add a picture frame and description. 
If you want a soft background too (ideally for text blocks), add bg as metadata after the pipe symbol, eg `>[[!framed | bg]]`  

<br>

## Simple description

![Img-capt](https://github.com/user-attachments/assets/35a656e9-9d15-4687-b377-4762db269f72)

`![[Pict.png#cap|capture]]`


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
