# Callouts
## Callouts colors
Tint any callout in: red, green, blue, gray

![B0](https://github.com/user-attachments/assets/c5dfd9c9-2f03-401b-9dd1-07e9c3dccf36)

```
> [!note|red]
> note
```

**Options:** `> [!note|red]`, `> [!note|green]`, `> [!note|blue]`, `> [!note|gray]`

**Deutsch:** `> [!note|rot]`, `> [!note|grün]`, `> [!note|blau]`, `> [!note|grau]`

<br>

## Aside notes (hidden)
Hidden box with a visual reference to open your side note. 
To display your box, hover over its thin, button on your right/left note border

![B1](https://github.com/user-attachments/assets/75bb1f17-9e9f-4f3b-985d-ad261b4744ba)

```
> [!aside|rh]
```

**Options:**  `> [!aside|rh]` or  `> [!aside|lh]`

**Deutsch**: `> [!seite|rv]` or  `> [!seite|lv]`

>Hover in `source mode`/`live preview` is deactivated, to prevent visual glitches.

<br>

## Aside-in (visible)
Box on your right or left side. 

![B2](https://github.com/user-attachments/assets/fe3006fc-3b1f-4c95-9bb9-e64e50e6dbda)

```
> [!aside-r]
```

**Options:**  `> [!aside|r]` or  `> [!aside|l]`

**Deutsch**: `> [!seite|r]` or  `> [!seite|l]`

<br>

## COLUMN HIGHLIGHT
Tint column blocks with a rgbm highlight.

![empph-parag](https://github.com/user-attachments/assets/4c756e7e-8bbb-4bb7-a4b2-d68ccf4696c6)

**Options:**  `> [!column|hl]` ,  `> [!column|hlr]`,  `> [!column|hlg]`,  `> [!column|hlb]`,  `> [!column|hlm]`

**Deutsch**: `> [!spalte|w]` or  `> [!spalte|wr]`, `> [!spalte|wg]`, `> [!spalte|wb]`, `> [!spalte|wm]`

<br>

## Multi-column
A multi-purpose callout column box to organize nested callouts, pictures, embeds. 

![B3](https://github.com/user-attachments/assets/a4478499-5ef3-403d-8388-d0bfbe26b124)
```
> [!multi-column]
>
>> [!check]+ Title 1
>> 
>> - words words words  
>> - words words words  
>
>> [!info]+ Title 2
>> - words words **words**
```

**Common Callouts**

```
> [!multi-column]
>
>> [!blank-container]
>>
>> - words words words  
>> - words words words  
>
>> [!blank-container]
>> - words words **words**
```

**Options:** Use either callout metadata tags or `> [!blank-container]` if you want to insert a blank callout 

**Deutsch**: 

 ```
> [!mehrspaltig]
>
>> [!leerraum]
>>
>> - words words words  
>> - words words words  
>
>> [!leerraum]
>> - words words **words**
```

>Note: use > [predefined Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) or generate custom callouts (use > [**Admonition**](https://github.com/valentine195/obsidian-admonition) by valentine195)


<br>

## Sidebox
Sidebox to summarize most important details of a topic. Accepted formats: pictures, text and links. 

![B4](https://user-images.githubusercontent.com/48620536/222980230-ca87423e-20fb-4680-8997-0b1a74e3c4a3.png)

```
> [!infobox|r]
> ## Title
> ![> [Pict.png]]
> ## Info
> A|  B |
> ---|---|
> Text| (> [Links](https://en.wikipedia.org/wiki/Frank_Herbert)) |
```

**Options:** `> [!infobox|l]`, `> [!infobox|r]`


<br>

## Citation
embed citations in boxes and place them on the left or right side of your note.

![citeblock](https://github.com/user-attachments/assets/bae4f744-fe83-40c7-a326-4b5d0d53b890)


```
> [!citation] 
>  description
```

**Options:** `> [!citation|l]`, `> [!citation|r]`

**Deutsch:** `> [!zitat|l]`, `> [!zitat|r]`

 <br>

## Read more…
Callout to shorten longer documents. 

```
> [!read-more]- 
> Lorem ipsum etc
```

**Options** `> [!read-more]-`

**Deutsch** `> [!weiterlesen]-`

>do not forget to add the minus after the callout, othewise this callout won't fold as expected

<br>

## Callouts alignment
Callout floats left

`> [!note|l]`

Callout floats right

`> [!note|r]`

Callout columns, left, right, axis (centered)
```
> [!column|l]
> [!column|r]
> [!column|a]
```

**Deutsch**

Ausruffeld Spalte links, rechts, Axis (Mitte)
```
> [!spalte|l]
> [!spalte|r]
> [!spalte|a]
```

<br>

## Text blocks - Small & Large
`l` in `font-l]`  equals to large and `s` in `font-s]`   equals to small


![new-features–02](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/a6fc8aa0-42bf-4859-b5a0-b4596fb5417f)

```
> [!font-l]
> Words Words Words Words
> Words Words Words Words
```

**Options** `> [font-l]`

**Deutsch**: `> [schrift-g]`


![new-features–03](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/32ad5dea-1489-421a-b529-81725fc66b17)

```
> [!font-s]
> Words Words Words Words
> Words Words Words Words
```

**Options** `> [font-s]`

**Deutsch**: `> [schrift-k]`

<br>


## Line breaks
### Simple line breaks (global)
to change line breaks globally, go to `Dune>Fonts>Text layout>Linebreak - blank` and toggle linebreaks on, to ignore empty lines and merge lines/paragraphs



<br>

### Multiple Line breaks (local)
for smaller line breaks, you don't need to add any line breaks inside this code block. For bigger breaks,
add as many line breaks as you need to this code fence.

````
```br


```
````


<br>

## Memo
to add more color variations, use: red, green, blue, gray.

 **Options**: `memo-r`, `memo-g`, `memo-b`, `memo-m`,

![Memo-b](https://github.com/user-attachments/assets/1b0f1486-6fd9-438d-8211-a69be9dc9625)

````
```memo-b
abc
```
````

---
> [go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
