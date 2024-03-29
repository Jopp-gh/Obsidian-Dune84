# Contact list

![Contact-ls](https://user-images.githubusercontent.com/48620536/228630560-99585883-7b52-4760-ac43-80b67caaf8b4.png)

> **note**: for profile pictures, only use squared pictures, otherwise zoomed profiles will display cut borders.

### Usage
1. First, add `cssclass: contacts` to your yaml header
2. then add a simple table, copy the template below:

```
|     | name| tel | mail| group| relations |
| --- | --- | --- | --- | ---- | --------- |
|     |     |     |     |      |           |
|     |     |     |     |      |           |
|     |     |     |     |      |           |
```

3. finally, add your data but pay attention - *the very first column is reserved for profile pictures only*. Images in there will display with an uniform size and a round cutout (see picture on top)

### Example
```
|                    | name              | tel           | mail          | group   | relations         |
| ------------------ | ----------------- | ------------- | ------------- | ------- | ----------------- |
| ![[profile1.png]]  | [[Frank Herbert]] | +765 0967887  | some@mail.com | #autor  | [[Anne Hubbard]]  |
| ![[profile2.jpg]]  | [[Anne Hubbard]]  | +765 0939885  | some@mail.com | #client | [[Frank Herbert]] |
```

>**Customize**: you can add **more columns**, *but do not change the very first column* as it is reserved to images only

### Related

to replace your vault name with a identity / profile picture, check out how to apply your [Profile](https://github.com/Jopp-gh/Obsidian-Dune84/blob/main/Wiki/Profile.md) or Avatar.

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
