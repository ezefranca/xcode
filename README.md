# Xcode
Xcode things that I will probably use someday, forgot about that and need it again.

## Other Linker Flags


### force_load

On Xcode, `Build Settings -> Other Linker Flags`.

- `-force_load` : flag is for loading static libraries, so you put the library archive, NOT the header file as the parameter.

Example: 

```shell
-force_load GooglePlus.framework/Versions/Current/GooglePlus
-force_load GoogleOpenSource.framework/Versions/Current/GoogleOpenSource
```
https://stackoverflow.com/questions/31580245/how-to-link-the-library-with-force-load-in-xcode

<hr>
