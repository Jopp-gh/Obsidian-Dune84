
### Aside-hide

```
> [!aside-rh]
```
callout options:  `[!aside-rh]` or  `[!aside-lh]`

![B1](https://user-images.githubusercontent.com/48620536/222979880-64b7d178-7804-4d3b-b089-2375df712e94.png)

Hover over the thin bar on your right/left side to reveal a hidden box. To edit your callout box in `Live Preview`, select the text before and/or after the callout box so that you select your callout too. Otherwise, switch to `Source mode` to see your callout entry. Hover in edit mode is deactivated, because this callout box is too jittery to select, as it is just a thin bar.

<br>

### Aside-in

```
> [!aside-r]
```
callout options:  `[!aside-r]` or  `[!aside-l]`

![B2](https://user-images.githubusercontent.com/48620536/222979913-e8e15146-725f-47d4-8126-b7c4055d261e.png)

<br>

### Multi-column

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
a multi-purpose callout column box to organize multiple nested callouts, pictures, embeds. Use [predefined Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) or generate custom callouts (use [**Admonition**](https://github.com/valentine195/obsidian-admonition) by valentine195)

![B3](https://user-images.githubusercontent.com/48620536/222980074-7f5294b8-d4ad-4cf5-8436-97f909303e86.png)

<br>

### Sidebox

```
> [!infobox-r]
> ## Title
> ![[Pict.png]]
> ## Info
> A|  B |
> ---|---|
> Text| ([Links](https://en.wikipedia.org/wiki/Frank_Herbert)) |
```
Options: `infobox-l`, `infobox-r`

![B4](https://user-images.githubusercontent.com/48620536/222980230-ca87423e-20fb-4680-8997-0b1a74e3c4a3.png)

<br>

### Read more…
Callout to shorten longer documents

```
> [!read-more…]- 
> Lorem ipsum etc
```

Options: `> [!read-more…]-`, `> [!weiterlesen…]-`

<br>

### Footnote, Memo

````
```fnote
words words words words 
```
````
![Lorem ipsum etc2](https://user-images.githubusercontent.com/48620536/224421103-b70f59bb-dd4d-4452-a65c-44c67b912999.png)

````
```memo
words words words words 
```
````
![Lorem ipsum etc1](https://user-images.githubusercontent.com/48620536/224421063-c53dd61d-7adb-4ab2-b3e1-fef9bb81787c.png)

<br>

### help bubbles

`<span class="addtip">highlighted words<span class="tiptext">Insert here your custom help text</span></span>`

![help bubbles](https://user-images.githubusercontent.com/48620536/228632119-35088c88-6138-4787-ad7a-f7109edeef33.png)

help bubbles on hover.

Beware, you cannot style text in **help bubbles**, like bold, italic and so on wont work. Just keep things simple.
To quickly instert help bubbles, use [Quickadd](https://github.com/chhoumann/quickadd) by chhoumann and create a new "Capture", call this action "help bubbles" activate the toggle **Capture to active note** , paste the code above in the bottom field of **Capture format**, then restart Obsidian to get your new  Quickadd capture available in your command palette.

Next time you want to add help bubbles, select the target word(s) in your note, launch the command palette and type "help bubbles", apply. Done this, your target word(s) will get a dotted underline. Now, click on this word(s) to expand the html tag and replace  **Insert here your custom help text** in`tiptext">Insert here your custom help text</span></span>` with your own help bubble text. 
