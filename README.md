# Unreal-Engine-3-Dumper-GName-Gobject

# step 1

-- Change GName, GObjects, ProcessEvent, ProcessEventIndex, UEngine (if the game need to use this for dumper);
|| -- Change GName, GObjects;

#step 2

```
  local TArray = {}
    TArray.Data = 0x0
    TArray.Num = 0x4
    TArray.Max = 0x8
  local UObject = {}
    UObject.Outer = 0x24
    UObject.FNameIndex = 0x28
    UObject.Unknown = 0x2C
    UObject.Class = 0x30
  local UClass = {}
    UClass.FNameIndex = 0x28
  local FNameEntry = {}
    FNameEntry.Name = 0x10
  local NameEnums = {} 
```
