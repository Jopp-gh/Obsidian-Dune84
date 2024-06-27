# Callouts
## Callouts colors

![callout-col](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/48e2d47b-873a-483c-ac83-e5c19eed47db)

```
> [!red callout|red]
> note
```
Tint any callout in: red, green, blue, gray

**Options:**`> [!note|red]`, `> [!note|green]`, `> [!note|blue]`, `> [!note|gray]`

<br>

## Aside notes (hidden)

![B1](https://user-images.githubusercontent.com/48620536/222979880-64b7d178-7804-4d3b-b089-2375df712e94.png)

```
> [!aside-rh]
```
Hidden box with a visual reference to open your side note. 
To display your box, hover over its thin, button on your right/left note border

**Options:**  `[!aside-rh]` or  `[!aside-lh]`

>Hover in `edit mode` is deactivated, to prevent visual glitches.

<br>

## Aside-in (visible)

![B2](https://user-images.githubusercontent.com/48620536/222979913-e8e15146-725f-47d4-8126-b7c4055d261e.png)

```
> [!aside-r]
```
Box on your right or left side. 
**Options:**  `[!aside-r]` or  `[!aside-l]`

<br>

## Multi-column

![B3](https://user-images.githubusercontent.com/48620536/222980074-7f5294b8-d4ad-4cf5-8436-97f909303e86.png)

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
**Horizontal Lists**

A multi-purpose callout column box to organize nested callouts, pictures, embeds. 
 **Options:** Use either callout box tags or `[!blank-container]` if you want a blank callout (without colors, title). 

>Use [predefined Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) or generate custom callouts (use [**Admonition**](https://github.com/valentine195/obsidian-admonition) by valentine195)


<br>

## Sidebox

![B4](https://user-images.githubusercontent.com/48620536/222980230-ca87423e-20fb-4680-8997-0b1a74e3c4a3.png)

```
> [!infobox-r]
> ## Title
> ![[Pict.png]]
> ## Info
> A|  B |
> ---|---|
> Text| ([Links](https://en.wikipedia.org/wiki/Frank_Herbert)) |
```
Sidebox to summarize most important details of a topic. Accepted formats: pictures, text and links. 

**Options:** `infobox-l`, `infobox-r`

<br>

## Columns in Gutter 

![columns–02](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/4f441c9a-55d5-4b56-b372-29556ec4e0e9)

```
>[!framed-lg]
Lorem…
```

![columns–01](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/53d5ba80-c273-4fbf-a579-cd3004887986)

```
>[!framed-rg]
Lorem…
```

The `rg` in `>[!framed-rg]` refers to the *right gutter* on the far right of your page, `lg` moves text blocks to the *left gutter*.

**Options:** `framed-lg`, `framed-rg`

>You must enable `Readable line length` under `preferences>editor>display` for this feature to work, otherwise your layout will overlap.
Basically, with this callout you can add notes to your left or right -side gutter.

<br>

## Callout Boxes

![framed-cite](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/2be78884-c3a0-4e84-8a72-6c3419e5d67b)

```
> [!framed-r | cite] 
>  description
```
 
embed citations in boxes and place them on the left or right side of your note.
By default, this callout has no background, but you can add a background if you add following meta-tags:

**Options:**
- add a soft background: `>[[!framed-l | bg]]`,`>[[!framed-r | bg]]`
- add a soft background and a citation Symbol:  `>[[!framed-l | cite]]`,`>[[!framed-r | cite]]`

 <br>

## Read more…

```
> [!read-more]- 
> Lorem ipsum etc
```
Callout to shorten longer documents. 

**Options** `>[!read-more]-`, `> [!weiterlesen]-`

>do not forget to add the minus after the callout, othewise this callout won't fold as expected

<br>

## Callouts alignment

`> [!note|left]`
Callout floats left

`> [!note|right]`
Callout floats right

<br>

## Text blocks - Small & Large

![new-features–02](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/a6fc8aa0-42bf-4859-b5a0-b4596fb5417f)

```
>[!font-l]
> Words Words Words Words
> Words Words Words Words
```
`l` in `font-l]`  stands for large

**Options** `>[font-l]`, `>[schrift-g]`



![new-features–03](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/32ad5dea-1489-421a-b529-81725fc66b17)

```
>[!font-s]
> Words Words Words Words
> Words Words Words Words
```
`s` in `font-s]`  stands for small

**Options** `>[font-s]`, `>[schrift-k]`

<br>

## Continuous text flow (around boxes, images)

### global
to change line breaks globally, go to `Preferences>Style Settings>Dune>Fonts>Spacing>Linebreak - blank` and toggle linebreaks on, to ignore empty lines and merge lines/paragraphs

<br>
## Multiple Line breaks

````
```br


```
````
add as many linebreaks as you want to control empty lines (the example above breaks two lines).

<br>

## Memo
![note-yell](https://user-images.githubusercontent.com/48620536/230743665-6075fa26-ad47-4d4a-b3e0-f2d9dbcb0a0d.png)

````
```memo
words words words words 
```
````
to add more color variations, use: red, green, blue. **Options**: `memo-r`, `memo-g`, `memo-b`,

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
