# Callouts
## Callouts colors

![callout-col](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/48e2d47b-873a-483c-ac83-e5c19eed47db)

```
> [!red callout|red]
> note
```
### Options:
`> [!note|red]`, `> [!note|green]`, `> [!note|blue]`, `> [!note|yellow]`, `> [!note|gray]`, `> [!note|col]`

red tint, green tint, blue tint, yellow tint, gray and favorite tint
to add your own tint, set your color in `Preferences>Style Settings>Dune>Colors>Custom Theme>Secondary Colors>Callout color - custom`. Back to your note, add "col" after the pipe symbol, eg `> [!note|col]` 

<br>

## Aside notes (hidden)

![B1](https://user-images.githubusercontent.com/48620536/222979880-64b7d178-7804-4d3b-b089-2375df712e94.png)

```
> [!aside-rh]
```
Hidden box with a visual reference on your right or left side, 
**callout options:**  `[!aside-rh]` or  `[!aside-lh]`

**Tip**
<br>
to show your hidden box, hover over the thin bar on your right/left side 
To edit your callout box in `Live Preview`, select the text before and/or after the callout box so that you select your callout too. Otherwise, switch to `Source mode` to see your callout entry. Hover in edit mode is deactivated, because this callout box is too jittery to select, as it is just a thin bar.

<br>

## Aside-in (visible)
![B2](https://user-images.githubusercontent.com/48620536/222979913-e8e15146-725f-47d4-8126-b7c4055d261e.png)

```
> [!aside-r]
```
Visible box on your right or left side, **callout options:**  `[!aside-r]` or  `[!aside-l]`

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

a multi-purpose callout column box to organize multiple nested callouts, pictures, embeds. 

**Tip**
<br>
Use [predefined Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) or generate custom callouts (use [**Admonition**](https://github.com/valentine195/obsidian-admonition) by valentine195)


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
Sidebox to visualize quickly most important details, like pictures, text and links. **Options:** `infobox-l`, `infobox-r`

## Framed

```
> [!framed-l] 
>  description
```

Options: framed-r, framed-l

embed your descriptions in boxes and place them on the left or right side of your note. You can add a soft background too, eg >[[!framed-r | bg]]

<br>

## Read more…

```
> [!read-more]- 
> Lorem ipsum etc
```
Callout to shorten longer documents. 
**Options:** `> [!read-more]-`, `> [!weiterlesen]-`

> **Tip**: do not forget to add the minus after the callout, othewise this callout won't fold

<br>

## Callouts alignment

`> [!note|300]`, `> [!note|400]`, `> [!note|500]`, `> [!note|600]`, `> [!note|700]`, `> [!note|800]`
max Callout width in pixels


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
![new-features–03](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/32ad5dea-1489-421a-b529-81725fc66b17)

```
>[!font-s]
> Words Words Words Words
> Words Words Words Words
```

## Continuous text flow (around boxes, images)
for a continuous text flow, you can use 2 methods to deal with line breaks:  **merge** (ignore line breaks) or **break**  (respect line breaks) 

> By default, Dune ignores line breaks, so the toggle is off.

### global
to change line breaks globally, go to `Preferences>Style Settings>Dune>Fonts>Spacing>New Line>Linebreaks - empty` and toggle linebreak on, toggle it off to merge lines/paragraphs

### local
to merge or break lines/paragraphs locally add following to your yaml header:
- add  `cssclass: merge-prg`  (in combination with `Line break` **on**)
- add `cssclass: break-prg` (in combination with `Line break` **off**)
- or merge paragraphs individually, using the `>[!merge]` callout (in combination with `Line break` **on**)


<br>

## Merge Paragraphs Callout

![mergePP-align-l](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/0758e68e-c0d1-47ed-935b-034286c7abca)

```
>[!merge]
> Abc
```

If line break is enabled, pay attention on how to merge paragraphs individually: the first and the last paragraph are normal paragraphs, both are highlighted just for this example, in bold. The paragraphs using the merge callout are highlighted with  **A, B** and **C**

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

>Note: the `g` of `>[!framed-rg]` refers to the gutter on the far left and right side of your page.

You must enable `Readable line length` under `preferences>editor>display` for this feature to work, otherwise your layout will overlap.
Basically, with this callout you can add notes to your left or right -side gutter.

<br>

## TIMELINE
**Upgrade your bullet lists, checklists and text blocks and put them in a chronological order**. 
**Timeline** is available *for Desktop, phone, the core plugin slide and pdf export*. Now let's understand how **Timeline** is structured. Please read on.

A typical **timeline callout** looks like this:
```
>[!tline|v1]
> ## January
> **Project A**
> - [ ] a
> - [ ] b
> - [ ] c
```
### LINE 1: CALLOUT TAGS AND METATAGS
Line 1= defines this kind of callout, use `>[!tline]` and add a pipe symbol followed by `v1` or `v2` as metadata, eg. `[!tline|v1]`

- Timeline callout v1, or `>[!tline|v1]` adds a soft background shadow, this way your time blocks are more diverse and easier readable. 
- Timeline callout v2, or `>[!tline|v2]` is without background shadow

>Mix them or use one of both callouts to build your timeline

### LINE 2: TIME UNIT
Line 2= **defines a time unit**, in our example `> ## January`. *Use any time unit useful for you*, example:

- hourly (morning/noon/afternoon/evening or 6:00/8:00/10:00/14:00, etc)
- daily (1 Nov, 15 Nov, 20 Nov, etc)
- weekly (mon, tue, wed, thu, fri, sat, sun or week 12, week 18, week 35, etc)
- monthly (Jan, Feb, Mar or September, December, etc)
- Yearly (2023, 2024, etc)

### LINE 3: PROJECT (OPTIONAL)
Line 3= Add a project name (Optional)

### LINE 4: TASKS
Line 3 or 4= add your bullet lists, checklists or reminder text blocks

#### USAGE
Ideally, a Timeline template is made of **two callouts** to create an *easy-to-read alternating row flow*. On desktop you can vary the distance from the left note margin to the red line, to give longer **time unit names** more space. To do so, go to Obsidians `Settings>Style Settings>Dune>Fonts>Spacing>Line` or type in "Unified" in the search mask of **Style Settings**

>Note: Basically, with each new line in a timeline callout you are going to add new columns (reading flow is aligned horizontally) like in a **Kanban** but all inside a **time frame defined by your heading** at the beginning of your timeline callout. You can even add a picture a line before your time unit `> ## January` and after the callout heading `>[!tline|v1]`, to add a visual reference to your timeline progress.

To use this timeline callout, copy the following template and save it in your templates folder:

```
>[!tline|v1]
> ## January
> **Project A**
> - [ ] a
> - [ ] b
> - [ ] c

>[!tline|v2]
> ## January
> **Project B**
> - [ ] a
> - [ ] b
> - [ ] c
```

**Result**:
![Timeline-](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/96ccfa12-1ee0-4355-a4e3-7d363864ad97)


<br>

## Footnote

![new-features–04a](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/6189488d-c3d3-4061-89a6-8f2317dbfbad)

Kind of footnote fields
````
```fnote
words words words words 
```
````

## Multiple Line breaks

````
```br


```
````
inside this fence, add as many linebreaks as needed (The example above breaks two lines).

<br>

## Memo
![note-yell](https://user-images.githubusercontent.com/48620536/230743665-6075fa26-ad47-4d4a-b3e0-f2d9dbcb0a0d.png)

````
```memo
words words words words 
```
````
Kind of memo notes, `memo` uses by default the color yellow

### more color variations
![note-blue](https://user-images.githubusercontent.com/48620536/230743600-678dbdc6-1aee-40bc-b892-199823340726.png)

````
```memo-b
note
```
````

to add more color variations, use: red, green, blue, gray (monochrome) eg. `memo-r`, `memo-g`, `memo-b`, `memo-m`

if you want to add your own color, go to `Preferences>Style Settings>Dune>Colors>Custom Theme>Secondary Colors>Stickies color - custom`, pick a color for light / dark themes and add `memo-col` to your fences

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
