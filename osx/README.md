# Summary

Collection of tweaks and settings for OSX.

## Fix END and HOME key

A working fix for home and end keys, working on OSX Sierra. Create [~/Library/KeyBindings/DefaultKeyBinding.dict](https://github.com/rniedzial/tweaks/osx/DefaultKeyBinding.dict)

```javascript
{
    "\UF729"  = moveToBeginningOfParagraph:; // home
    "\UF72B"  = moveToEndOfParagraph:; // end
    "$\UF729" = moveToBeginningOfParagraphAndModifySelection:; // shift-home
    "$\UF72B" = moveToEndOfParagraphAndModifySelection:; // shift-end
    "^\UF729" = moveToBeginningOfDocument:; // ctrl-home
    "^\UF72B" = moveToEndOfDocument:; // ctrl-end
    "^$\UF729" = moveToBeginningOfDocumentAndModifySelection:; // ctrl-shift-home
    "^$\UF72B" = moveToEndOfDocumentAndModifySelection:; // ctrl-shift-end
}
```
[Reference article](http://cobus.io/osx/2017/02/09/OSX_Home_End_Keys.html)
