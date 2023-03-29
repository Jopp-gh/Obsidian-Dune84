### Contact list

First, add `cssclass: contacts` to your yaml header, otherwise this table wont look right.
To start, add a simple table, use:

```
| A   | B   | C   | D   |
| --- | --- | --- | --- |
| 1   | 2   | 3   | 4   |
| x   |     |     |     |
| y   |     |     |     |
```

then and start adding data, but pay attention - the very first column of this table is reserved for profile pictures. Images in there will scale down and get a round cutout (see picture below)

If you prefer, copy the template below, add and remove columns you need in Obsidian and finally, save your table as template in your templates folder. Done.

```
|                    | name              | tel           | mail          | group   | relations         |
| ------------------ | ----------------- | ------------- | ------------- | ------- | ----------------- |
| ![[profile1.png]]  | [[Frank Herbert]] | +765 0967887  | some@mail.com | #autor  | [[Anne Hubbard]]  |
| ![[profile2.jpg]]  | [[Anne Hubbard]]  | +765 0939885  | some@mail.com | #client | [[Frank Herbert]] |
```

![Contact-ls](https://user-images.githubusercontent.com/48620536/228630560-99585883-7b52-4760-ac43-80b67caaf8b4.png)

