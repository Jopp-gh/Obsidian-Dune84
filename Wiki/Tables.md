```
---
cssclass: wideTable
---
```
Use **wideTable** to cover the whole page


### Default table
```
| A   | B   | C   | D   |
| --- | --- | --- | --- |
| 1   | 2   | 3   | 4   |
| x   |     |     |     |
| y   |     |     |     |
```
![table–01](https://user-images.githubusercontent.com/48620536/222981305-a52437da-d700-431a-be7e-4e55f2dc39f6.png)

### Custom tables
`cssclass: table-fc`

![table–02](https://user-images.githubusercontent.com/48620536/222981323-4bcacbe3-b1f4-49fe-a2ae-cc405ba952c3.png)

`cssclass: table-lc`

![table–04](https://user-images.githubusercontent.com/48620536/222981341-314f43dd-5e78-47c5-9721-ae9a4fa042b2.png)

`cssclass: table-alt`

![table–03](https://user-images.githubusercontent.com/48620536/222981330-2811bff8-c8ac-49b3-ade6-0c882d111117.png)

`cssclass: table-lr`

![table–05](https://user-images.githubusercontent.com/48620536/222981350-e5d4cd9d-a599-454b-9365-d6f7b6216185.png)


## styled tables

`cssclass: wideTable, academia`

![tableSt–01](https://user-images.githubusercontent.com/48620536/223588651-fd627851-6155-4d78-a764-d9c9094bcfb8.png)


`cssclass: wideTable, whiteBlue`

![tableSt–02](https://user-images.githubusercontent.com/48620536/223588682-3fa904e0-8181-4d60-9485-0678f8d71862.png)

<br>

### Contact list

First, add `cssclass: contacts` to your yaml header, otherwise this table wont look right.
To start, add a simple table (as seen under **Default table** above) and start adding data, but pay attention the very first column of this particular table is reserved for profile pictures. Images in there will scale down and get a round shape (see attachments below)
Otherwise, if you dont wanna start from scratch with a contact table, copy my contact-list template below, add and remove the columns you need in Obsidian and finally, save your table as template in your templates folder. Done.

```
| Ω                  | name              | tel           | mail          | group   | relations         |
| ------------------ | ----------------- | ------------- | ------------- | ------- | ----------------- |
| ![[profile1.png]]  | [[Frank Herbert]] | +765 0967887  | some@mail.com | #autor  | [[Anne Hubbard]]  |
| ![[profile2.jpg]]  | [[Anne Hubbard]]  | +765 0939885  | some@mail.com | #client | [[Frank Herbert]] |
```

![contacts](https://user-images.githubusercontent.com/48620536/226483924-8f571fd0-067b-45fb-8119-c8061d0e0c98.png)
