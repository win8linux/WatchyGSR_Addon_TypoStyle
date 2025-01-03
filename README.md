# TypoStyle for Watchy GSR

![TypoStyle watchface](TypoStyle.png)

A port of the [TypoStyle](https://github.com/spinalcode/TypoStyle) watchface originally made by spinalcode for the original Watchy firmware to Watchy GSR.

## Adding to a Watchy GSR build
1. Add this repo as a submodule in a Watchy GSR repo:
```sh
git submodule add https://github.com/win8linux/WatchyGSR_Addon_TypoStyle.git "Watchface Addons/TypoStyle"
```
2. Add the following include to `src/GSR.ino` in Watchy GSR:
```cpp
#include "../Watchface Addons/TypoStyle/GSRWatchFaceTypoStyle.h"
```
3. Compile!
