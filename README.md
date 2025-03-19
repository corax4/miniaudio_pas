# miniaudio_pas

Pascal bindings for miniaudio library.

Based on [CPas](https://github.com/tinyBigGAMES/CPas) library. 
Modified for dynamic library loading.

Before using any library function You need to initialize library:

```pascal
if not MALibInit('C:\Path\To\miniaudio.dll') then DoSomeErrorHandling;
```
