# Text highlights
## Text colors

![txt-fat](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/aef8de34-c1c4-43ce-aae2-419029368c97)

`#red **Abc**`
`#green **Abc**`
`#blue **Abc**`
`#gray **Abc**`

red, green, blue, gray - fat

![txt-ital](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/1cd27a55-eb76-4bc5-b62c-5d723e42bb39)

`#red *Abc*`
`#green *Abc*`
`#blue *Abc*`
`#gray *Abc*`

red, green, blue, gray - italic

![txt-highl](https://github.com/Jopp-gh/Obsidian-Dune84/assets/48620536/7d166071-1e26-4306-80a0-ed4648a88c09)

`#red ==text==`
`#green ==text==`
`#blue ==text==`
`#gray ==text==`

red, green, blue - highlight


<br>


## help bubbles

![help bubbles](https://user-images.githubusercontent.com/48620536/228632119-35088c88-6138-4787-ad7a-f7109edeef33.png)

help bubbles on hover.

### Usage 

**Tip**: To quickly instert help bubbles, use [Quickadd](https://github.com/chhoumann/quickadd) by chhoumann

a) open **Quickadd** and create a new **Capture** and call your action "help bubbles" 
<br>
b) toggle **Capture to active note** on, paste the **code template** below as it is in the bottom field called **Capture format**
<br>
c) then *restart Obsidian* to get your new Quickadd capture available in your command palette.

#### code template
`<span class="addtip">{{VALUE}}<span class="tiptext">Insert here your custom help text</span></span>`

<br>

Next time you want to add help bubbles to your word(s): 
1. select the target word(s) in your note
2. launch the command palette and type "help bubbles"
3. apply. Done this, your target word(s) will get a dotted underline.
4. Now, click on this word(s) to expand the html tag and replace  **Insert here your custom help text** in`tiptext">Insert here your custom help text</span></span>` with your own help bubble text. 

**Note**: you cannot style text in **help bubbles**, like bold, italic and so on wont work. Just keep things simple.

<br>

## Mini Admonitions

`- [t] t`
<br>
`- [a] a`
<br>
`- [>] >`
<br>
`- [<] <`
<br>
`- [-] -`
<br>
`- [b] b`
<br>
`- [#] #`
<br>
`- [p] p`
<br>
`- [<] <`
<br>
`- [e] e`
<br>
`- [!] !`
<br>
`- [l] l`
<br>
`- [h] h`
<br>
`- [g] g`
<br>
`- [w] w`
<br>
`- [+] +`
<br>
`- [q] q`
<br>
`- [n] n`
<br>
`- [i] i`
<br>
`- [d] d`
<br>
`- [f] f`
<br>
`- [m] m`
<br>
`- [/] /`
<br>
`- [?] ?`
<br>
`- [s] s`

![bmini-admo](https://user-images.githubusercontent.com/48620536/228631190-f9878334-c1bb-4113-8fba-f62f785aba07.png)

24 mini admonitions

## Other uses
- [q] q 
	- test 1
	- [x] test 2

![L2](https://user-images.githubusercontent.com/48620536/222980616-5650e216-9d3e-4716-ad0f-e59cc7fdff8f.png)

<br>

## Simple Horizontal lines
`cssclass: fade`
`cssclass: fade-2`
`cssclass: fade-3`
`cssclass: stars`

simple delimiter to divide chapters or paragraphs. If you want beautiful delimiters, check out [Poetry delimiters](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/Wiki/Poetry.md#horizontal-line-styles)

### Usage
1. First, pick a horizontal line style eg. **fade-2** and add this style to your yaml header
2. add two paragraphs and write 3 dashes `---` 

**Tip**: you can change delimiter color too, go to: **Style Settings>Dune>Colors>Extra Colors>Color for Hr**

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
