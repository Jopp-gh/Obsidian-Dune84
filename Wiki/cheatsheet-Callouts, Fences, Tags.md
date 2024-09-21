## CALLOUTS

### CALLOUTS ALIGNMENT


`> [!note|l]`
`> [!note|r]`

Callout floats left / right

<br>

### CALLOUTS COLORS

```
> [!note|red]
> [!note|green]
> [!note|blue]
> [!note|gray]
```

5 callout tints

**Deutsch**
```
> [!note|rot]
> [!note|grün]
> [!note|blau]
> [!note|grau]
```

<br>

### TEXT AND IMAGE ALIGNMENT


`>[!column|l]`, 
`>[!column|r]`,
`>[!column|a]`

align columns to the left, right or around the middle axis

**Deutsch**
`>[!spalte|l]`, 
`>[!spalte|r]`,
`>[!spalte|a]`
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
Add blank sub-callouts
```
> [!multi-column]
>
>> [!note]
>> abc
>
>> [!caution]
>> abc
```
add common sub-callouts inside your callout box

**Deutsch**
```
> [!mehrspaltig]
>
>> [!leerraum]
>> abc
>
>> [!leerraum]
>> abc
```

#### MULTICOLUMN - COLORS

```
> [!multi-column|red]
> [!multi-column|green]
> [!multi-column|blue]
> [!multi-column|gray]
```

**Deutsch**

```
> [!mehrspaltig|rot]
> [!mehrspaltig|grün]
> [!mehrspaltig|blau]
> [!mehrspaltig|grau]
```

colors for the `multi-column` callout

<br>

### TEXT BOXES

`>[!citation]`
`>[!citation|l]`
`>[!citation|r]`

**Deutsch**
`>[!zitat]`
`>[!zitat|l]`
`>[!zitat|r]`

add a **citation callout** and place it on the left of right hand side. 

```
>[!aside-l]
>[!aside-r]
```
**Deutsch**
```
>[!seite-l]
>[!seite-r]
```

**visible text boxes** on the left / right on-page

```
>[!aside-lh]
>[!aside-rh]
```
**Deutsch**
```
>[!seite-lv]
>[!seite-rv]
```

**hidden text boxes** on the left / right on-page.

`>[!read-more]`

**Deutsch**
`>[!weiterlesen]`


shortens long documents. Dig into details on demand

`>[!infobox|l]`
`>[!infobox|r]`

accepts a mix of headers, text, tables

<br>
### HIGHLIGHT TEXT BLOCKS

`>[!column|hl]`
`>[!column|hlr]`
`>[!column|hlg]`
`>[!column|hlb]`
`>[!column|hlm]`

**Deutsch**
`>[!spalte|w]`
`>[!spalte|wr]`
`>[!spalte|wg]`
`>[!spalte|wb]`
`>[!spalte|wm]`

highlight a paragraph with a left-hand-side colored border

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

**Deutsch**

```
>[!schrift-g]
>[!schrift-k]
```

<br>
## FENCES
### MEMO COLORS

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

add -n paragraphs of linebreak

<br>
### HORIZONTAL LINES

````
```fade
```
````
````
```fade2
```
````
````
```fade3
```
````
````
```stars
```
````
simple delimiters
````
```trenner
```
````
````
```trenner2
```
````
````
```trenner3
```
````
````
```sterne
```
````
beautiful delimiters

**Deutsch**
````
```wave-a
```
````
````
```wave-b
```
````
````
```wave-c
```
````
````
```wave-d
```
````

einfache Trenner
````
```deko
```
````
````
```deko2
```
````
````
```deko3
```
````
````
```deko4
```
````
schöne Trenner

## TAGS
### TEXT COLORS

```
Bold

#red **Abc**
#green **Abc**
#blue **Abc**
#gray **Abc**
```

colored - **bold**

```
Italic

#red *Abc*
#green *Abc*
#blue *Abc*
#gray *Abc*
```

colored - *italic*

```
highlight

#red ==Abc==
#green ==Abc==
#blue ==Abc==
#gray ==Abc==
```

colored - highlight


**Deutsch**

```
Markiert. Auch mit Fett und Kursiv möglich.

#rot ==Abc==
#grün ==Abc==
#blau ==Abc==
#grau ==Abc==
#mfarbe ==Abc==
```

<br>

### POETRY

```
#raisecap ==Abc==
#dropcap ==Abc==
```

raisecap and dropcap

**Deutsch**

```
#maiuskel ==Abc==
#initiale ==Abc==
```

Majuskel und Initiale


### CITATION QUOTE

```
#cite-de ==Abc==
#cite-br ==Abc==
#cite-fr ==Abc==
```

**Deutsch**

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

hide text, long version

`#-tips ==Abc==`

hide text, short version

**Deutsch**
`#-geheim ==Abc==`




<br>

### LINES
```
#line-a ==Abc==
#line-b ==Abc==
#line-c ==Abc==
```

**Deutsch**

```
#strich-a ==Abc==
#strich-b ==Abc==
#strich-c ==Abc==
```

underlined, double underlined, strikeout

<br>

### SENTENCE INDENT

`#indent ==Abc==`

**Deutsch**

`#einzug ==Abc== `

Indent sentences

<br>
