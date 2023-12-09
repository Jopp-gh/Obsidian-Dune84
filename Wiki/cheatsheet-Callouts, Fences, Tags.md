## CALLOUTS

### CALLOUTS ALIGNMENT

```
> [!note|300]
> [!note|400]
> [!note|500]
> [!note|600]
> [!note|700]
> [!note|800]
```

Callout width defined in pixels

```
> [!note|left]
> [!note|right]
```

**German**

```
> [!note|links]
> [!note|rechts]
```

Callout floats left / right

<br>

### CALLOUTS COLORS

```
> [!note|yellow]
> [!note|red]
> [!note|green]
> [!note|blue]
> [!note|gray]
> [!note|col]
```

5 callout tints

**German**

```
> [!note|gelb]
> [!note|rot]
> [!note|grün]
> [!note|blau]
> [!note|grau]
> [!note|farbe]
```

<br>

### TEXT AND IMAGE ALIGNMENT

```
>[!framed-l]
> abc
```

```
>[!framed-r]
> abc
```

```
>[!framed-c]
> abc
```

align images or text to the left, right or at the center

<br>

### MULTICOLUMN

```
> [!multi-column]
>
>> [!blank-container]
>> abc
>
>> [!blank-container]
>> abc
```

#### MULTICOLUMN - COLORS

```
> [!multi-column|yellow]
> [!multi-column|red]
> [!multi-column|green]
> [!multi-column|blue]
> [!multi-column|gray]
> [!multi-column|col]
```

**German**

```
> [!multi-column|gelb]
> [!multi-column|rot]
> [!multi-column|grün]
> [!multi-column|blau]
> [!multi-column|grau]
> [!multi-column|farbe]
```

colors for the `multi-column` callout

<br>

### TEXT BOXES

```
>[!framed | bg]
>[!framed | cite]
```

add **background shadow** or add a **citation symbol** and a background shadow

```
>[!framed-lg]
>[!framed-rg]
```

place **smaller text blocks** in the left / right gutter. *Readable line width* required

```
>[!aside-l]
>[!aside-r]
```

**visible text boxes** on the left / right on-page

```
>[!aside-lh]
>[!aside-rh]
```

**hidden text boxes** on the left / right on-page.

```
>[!read-more]
>[!weiterlesen]
```

shortens long documents. Dig into details on demand

`>[!infobox] or >[!infobox-l]`

`>[!infobox-r]`

accepts a mix of headers, text, tables

<br>

### PICTURE BOXES

`>[!moodboard]`

create moodboard masonry


### SMALLER AND LARGER TEXT BLOCKS

```
>[!font-s]
> abc
```

decrease font size

```
>[!font-l]
> abc
```

increase font size

**German**

```
>[!schrift-g]
>[!schrift-k]
```

<br>

### MERGE TEXT BLOCKS

`>[!merge]`

merge text blocks if *Linebreak - blank* are activated

### TLINE

```
>[!tline | v1]
>[!tline | v2]
```

alternating time-frame callouts

<br>

## FENCES
### MEMO COLORS

````
```memo
notes
```
````

yellow

````
```memo-r
notes
```
````

red

````
```memo-g
notes
```
````

green

````
```memo-b
notes
```
````

blue

````
```memo-m
notes
```
````
monochrome


### PARAGRAPH BREAK

````
```br

```
````

add -n paragraphs linebreak

<br>

## TAGS
### TEXT COLORS

```
Bold

#red **Abc**
#green **Abc**
#blue **Abc**
#gray **Abc**
#hlcol **Abc**
```

colored - **bold**

```
Italic

#red *Abc*
#green *Abc*
#blue *Abc*
#gray *Abc*
#hlcol *Abc*
```

colored - *italic*

```
highlight

#red ==Abc==
#green ==Abc==
#blue ==Abc==
#gray ==Abc==
#hlcol ==Abc==
```

colored - highlight

```
Bold

#red-s **Abc** ,
#green-s **Abc**,
#blue-s **Abc**
#hlcol-s **Abc**

Italic

#red-s *Abc* ,
#green-s *Abc*,
#blue-s *Abc*
#hlcol-s *Abc*

```

smaller colored text

```
Bold

#red-l **Abc**,
#green-l **Abc**,
#blue-l **Abc**
#hlcol-l *Abc*

Italic

#red-l *Abc*,
#green-l *Abc*,
#blue-l *Abc*
#hlcol-l *Abc*
```

larger colored text

**German**

```
Bold

#rot-k **Abc** 
#grün-k **Abc**
#blau-k **Abc**
#grau-k **Abc**
#mfarbe-k **Abc**

Italic

#rot-k *Abc* 
#grün-k *Abc*
#blau-k *Abc*
#grau-k *Abc*
#mfarbe-k *Abc*

```

smaller colored text

```
Bold

#rot-g **Abc** 
#grün-g **Abc**
#blau-g **Abc**
#grau-g **Abc**
#mfarbe-g **Abc**

Italic

#rot-g *Abc* , 
#grün-g *Abc*, 
#blau-g *Abc*
#grau-g *Abc*
#mfarbe-g *Abc*

```

larger colored text

```
highlight

#rot ==Abc==
#grün ==Abc==
#blau ==Abc==
#grau ==Abc==
#mfarbe ==Abc==
```

<br>

### FONT FAMILY

```
#font-1 ==Abc==
#font-2 ==Abc==
#font-3 ==Abc==
#font-4 ==Abc==
```

**German**

```
#schrift-1 ==Abc==
#schrift-2 ==Abc==
#schrift-3 ==Abc==
#schrift-4 ==Abc==
```

Inline font change

### POETRY

```
#raisecap ==Abc==
#dropcap ==Abc==
```

Initial Letters - raisecap and dropcap

```
#initiale ==Abc==
#initiale-t==Abc==
```

Initiale - hoch und tiefgestellt

### FONT SIZE

`#font-s ==Abc==`

decrease inline font size

`#font-l ==Abc==`

increase inline font size

**German**

```
#schrift-g ==Abc==
#schrift-k ==Abc==
```

### CITATION QUOTE

```
#cite-de ==Abc==
#cite-br ==Abc==
#cite-fr ==Abc==
```

**German**

```
#zitat-de ==Abc==`
#zitat-br ==Abc==`
#zitat-fr ==Abc==`
```

citation marks for sentences, words

<br>

### SUB & SUP

```
Words #sup ==sup==
Words #sub ==sub==
```

### SPOILER

`#-spoiler ==Abc==`

**German**

`#-geheim ==Abc==`

hide text, long version

`#tips ==Abc==`

hide text, short version

<br>

### LINES
```
#line-a ==Abc==
#line-b ==Abc==
#line-c ==Abc==
```

**German**

```
#strich-a ==Abc==
#strich-b ==Abc==
#strich-c ==Abc==
```

underlined, double underlined, strikeout

<br>

### SENTENCE INDENT

`#indent ==Abc==`

**German**

`#einzug ==Abc== `

Indent sentences

<br>

### TAG ICONS

```
#-ppl ==Abc== 
#-mail ==Abc== 
#-tel ==Abc45== 
#-read ==Abc== 
#-edit ==Abc== 
#-promo ==Abc== 
#-loc ==Abc==
#-key ==Abc== 
#-pin ==Abc==
#-cal ==Abc== 
#-idea ==Abc==
#-profit ==Abc== 
#-check ==Abc== 
```

**German**

```
#-kontakt ==Abc== 
#-brief ==Abc== 
#-tel ==Abc45== 
#-lese ==Abc== 
#-arbeit ==Abc== 
#-promo ==Abc== 
#-ort ==Abc==
#-schlüssel ==Abc== 
#-merke ==Abc==
#-kal ==Abc== 
#-idee ==Abc==
#-profit ==Abc== 
#-prüfe ==Abc== 
```
