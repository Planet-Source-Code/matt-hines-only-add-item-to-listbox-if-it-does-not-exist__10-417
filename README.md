<div align="center">

## Only add item to listbox if it does not exist


</div>

### Description

This short code will check if a certain item is already in your listbox, if not then it will add it. Its good for preventing duplicates.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Matt Hines](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/matt-hines.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__10-1.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/matt-hines-only-add-item-to-listbox-if-it-does-not-exist__10-417/archive/master.zip)





### Source Code

```
dim str as string = "String to add goes here"
If listbox.FindString(str) = -1 Then listbox.Items.Add(str)
This code will only add the item if it is not already in the listbox.
```

