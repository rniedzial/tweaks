# Summary

Collection of tweaks and settings for OSX.

## Fix END and HOME key

You could remap home and end by creating []~/Library/KeyBindings/DefaultKeyBinding.dict](https://github.com/rniedzial/tweaks/osx/DefaultKeyBinding.dict)

```javascript
{
    "\UF729"  = moveToBeginningOfParagraph:; // home
    "\UF72B"  = moveToEndOfParagraph:; // end
    "$\UF729" = moveToBeginningOfParagraphAndModifySelection:; // shift-home
    "$\UF72B" = moveToEndOfParagraphAndModifySelection:; // shift-end
}
```

[StackExchange article](https://apple.stackexchange.com/questions/16135/remap-home-and-end-to-beginning-and-end-of-line)
