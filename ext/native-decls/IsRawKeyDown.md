---
ns: CFX
apiset: client
---
## IS_RAW_KEY_DOWN

```c
BOOL IS_RAW_KEY_DOWN(int rawKeyIndex);
```

Gets if the specified `rawKeyIndex` is pressed down on the keyboard.

This will not be triggered if the key is disabled with [DISABLE_RAW_KEY_THIS_FRAME](#_0x8BCF0014)

Virtual key codes can be found [here](https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes)

## Parameters
* **rawKeyIndex**: Index of raw key from keyboard.

## Return value
Returns bool value of down state.

## Examples
```lua
if IsRawKeyDown(32) then -- KEY_SPACE
    print("Spacebar is down")
end
```
