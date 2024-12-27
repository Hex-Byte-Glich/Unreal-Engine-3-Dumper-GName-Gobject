# Unreal-Engine-3-Dumper-GName-Gobject

# step 1

-- Change GName, GObjects, ProcessEvent, ProcessEventIndex, UEngine (if the game need to use this for dumper);
|| -- Change GName, GObjects;

#step 2

```
if not syntaxcheck and process ~= nil then

  local GObjects = 0x01417620 //change to your game GObjects [ find in IDA Pro ]
  local GNames = 0x01429664 //change to your game GName [ find in IDA Pro ]
  local isWideString = false //string name in txt when generator
  local Path = 'C:\\Users\\NAME\\Desktop\\' //location dumper txt to see of all GName and GObject

  local TArray = {} //chnage spp your game
    TArray.Data = 0x0
    TArray.Num = 0x4
    TArray.Max = 0x8
  local UObject = {} //chnage spp your game
    UObject.Outer = 0x24
    UObject.FNameIndex = 0x28
    UObject.Unknown = 0x2C
    UObject.Class = 0x30
  local UClass = {} //chnage spp your game
    UClass.FNameIndex = 0x28
  local FNameEntry = {}
    FNameEntry.Name = 0x10
  local NameEnums = {} 
```
