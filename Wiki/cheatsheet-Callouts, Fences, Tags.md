## CALLOUTS

### CALLOUTS ALIGNMENT
Callout floats left / right

`> [!note|l]`
`> [!note|r]`

<br>

### CALLOUTS COLORS
5 callout tints

```
> [!note|red]
> [!note|green]
> [!note|blue]
> [!note|gray]
```

#### Deutsch

```
> [!note|rot]
> [!note|grün]
> [!note|blau]
> [!note|grau]
```

<br>

### TEXT AND IMAGE ALIGNMENT
align columns to the left, right or around the middle axis

`>[!column|l]`, 
`>[!column|r]`,
`>[!column|a]`


#### Deutsch

`>[!spalte|l]`, 
`>[!spalte|r]`,
`>[!spalte|a]`

<br>

### MULTICOLUMN
Add a multi-column box and blank sub-callouts or custom callouts

```
> [!multi-column]
>
>> [!blank-container]
>> abc
>
>> [!blank-container]
>> abc
```

```
> [!multi-column]
>
>> [!note]
>> abc
>
>> [!caution]
>> abc
```

#### Deutsch

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
colors for the `multi-column` callout

```
> [!multi-column|red]
> [!multi-column|green]
> [!multi-column|blue]
> [!multi-column|gray]
```

#### Deutsch

```
> [!mehrspaltig|rot]
> [!mehrspaltig|grün]
> [!mehrspaltig|blau]
> [!mehrspaltig|grau]
```


<br>

### TEXT BOXES
add a **citation callout** and place it on the left of right hand side. 

`>[!citation]`
`>[!citation|l]`
`>[!citation|r]`

#### Deutsch

`>[!zitat]`
`>[!zitat|l]`
`>[!zitat|r]`


#### Aside box

add a **aside callout** and place it on the left of right hand side. 

```
>[!aside-l]
>[!aside-r]
```

#### Deutsch

```
>[!seite-l]
>[!seite-r]
```

#### Hidden aside boxes
on the left / right on-page

```
>[!aside-lh]
>[!aside-rh]
```

#### Deutsch

```
>[!seite-lv]
>[!seite-rv]
```

#### Read-more
shortens long documents. Dig into details on demand

`>[!read-more]`

#### Deutsch

`>[!weiterlesen]`


#### Infobox
accepts a mix of headers, text, tables

`>[!infobox|l]`
`>[!infobox|r]`


<br>

### HIGHLIGHT TEXT BLOCKS
highlight a paragraph with a left-hand-side colored border

`>[!column|hl]`
`>[!column|hlr]`
`>[!column|hlg]`
`>[!column|hlb]`
`>[!column|hlm]`

#### Deutsch

`>[!spalte|w]`
`>[!spalte|wr]`
`>[!spalte|wg]`
`>[!spalte|wb]`
`>[!spalte|wm]`


### SMALLER AND LARGER TEXT BLOCKS
decrease  or increase font size

```
>[!font-s]
> abc
```

```
>[!font-l]
> abc
```

#### Deutsch

```
>[!schrift-g]
>[!schrift-k]
```

<br>

## FENCES
#### Memo colors
red, green, blue, monochrome

````
```memo-r
notes
```
````



````
```memo-g
notes
```
````



````
```memo-b
notes
```
````


````
```memo-m
notes
```
````



### PARAGRAPH BREAK
add -n paragraphs of linebreak


````
```br

```
````

<br>

### HORIZONTAL LINES
simple delimiters

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

#### Deutsch
einfache Trenner

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


**beautiful delimiters**

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

#### Deutsch
schöne Trenner

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

## TAGS
### TEXT COLORS
colored - **bold**, colored - *italic*, colored - highlight

```
Bold

#red **Abc**
#green **Abc**
#blue **Abc**
#gray **Abc**
```


```
Italic

#red *Abc*
#green *Abc*
#blue *Abc*
#gray *Abc*
```


```
highlight

#red ==Abc==
#green ==Abc==
#blue ==Abc==
#gray ==Abc==
```


#### Deutsch

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
raisecap and dropcap

```
#raisecap ==Abc==
#dropcap ==Abc==
```


#### Deutsch

Majuskel und Initiale

```
#maiuskel ==Abc==
#initiale ==Abc==
```



### CITATION QUOTE
citation marks for sentences, words

```
#cite-de ==Abc==
#cite-br ==Abc==
#cite-fr ==Abc==
```

#### Deutsch

```
#zitat-de ==Abc==`
#zitat-br ==Abc==`
#zitat-fr ==Abc==`
```


<br>

### SUB & SUP

```
Words #sup ==sup==
Words #sub ==sub==
```

### SPOILER
hide text, short and long version

`#-spoiler ==Abc==`

`#-tips ==Abc==`


#### Deutsch

`#-geheim ==Abc==`


<br>

### LINES
underlined, double underlined, strikeout

```
#line-a ==Abc==
#line-b ==Abc==
#line-c ==Abc==
```

#### Deutsch

```
#strich-a ==Abc==
#strich-b ==Abc==
#strich-c ==Abc==
```


<br>

### SENTENCE INDENT
Indent sentences

`#indent ==Abc==`

#### Deutsch

`#einzug ==Abc== `
