# Contact list

![Contact-ls](https://user-images.githubusercontent.com/48620536/228630560-99585883-7b52-4760-ac43-80b67caaf8b4.png)


### Usage
1. First, add `cssclass: contacts` to your yaml header
2. to start, add a simple table, copy:

```
|     | name| tel | mail| group| relations |
| --- | --- | --- | --- | ---- | --------- |
|     |     |     |     |      |           |
|     |     |     |     |      |           |
|     |     |     |     |      |           |
```

3. then start adding data, but pay attention - the very first column is reserved for profile pictures only. Images in there will display in an uniform size and get a round cutout (see picture at bottom page)

### Example
```
|                    | name              | tel           | mail          | group   | relations         |
| ------------------ | ----------------- | ------------- | ------------- | ------- | ----------------- |
| ![[profile1.png]]  | [[Frank Herbert]] | +765 0967887  | some@mail.com | #autor  | [[Anne Hubbard]]  |
| ![[profile2.jpg]]  | [[Anne Hubbard]]  | +765 0939885  | some@mail.com | #client | [[Frank Herbert]] |
```

### Customize

you can add more columns if you desire, but do not change the very first column as it is reserved for images only

---
[go back to the ReadMe](https://github.com/Jopp-gh/Obsidian-Dune84/tree/main)
