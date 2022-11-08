# system.sav Offsets

## Offsets of Interest

#### **0x4b7 -** _"Hello Abyss"_ completion flag

`00` = _"Hello Abyss"_ incomplete; _"Deep in Abyss"_ locked.\
`01` = _"Hello Abyss"_ complete; _"Deep in Abyss"_ unlocked

## Settings Offsets

#### **0x474 - Brightness**

_(values from 0 to 100, converted to base16)_

`00` = Dark\
`32` = Medium\
`64` = Bright

#### 0x475 - Text Language

`00` = English\
`01` = Japanese\
`02` = Chinese

#### 0x476 - Voice Language

`00` = English\
`01` = Japanese

#### 0x477 - Confirmation Skip

`00` = Off\
`01` = On

#### 0x47b - Text Speed

`00` = Slow\
`01` = Normal\
`02` = Fast

#### 0x488 - Minimap Fixed

`00` = Off\
`01` = On

#### 0x48c - Invert Camera Y

`00` = Not nverted\
`01` = Inverted

#### 0x490 - Invert Camera X

`00` = Not inverted\
`01` = Inverted

#### 0x494 - Camera, Y Sensitivity

_(values from 0 to 100, converted to base16)_

`00` = Slow\
`32` = Medium\
`64` = Fast

#### 0x495 - Camera, X Sensitivity

_(values from 0 to 100, converted to base16)_

`00` = Slow\
`32` = Medium\
`64` = Fast

#### 0x496 - Controller Vibration

`00` = No vibration\
`01` = Vibration

#### 0x49a - Master Volume

_(values from 0 to 100, converted to base16)_

`00` = Muted\
`32` = Half-volume\
`64` = Full volume

#### 0x49b - BGM Volume

_(values from 0 to 100, converted to base16)_

`00` = Muted\
`32` = Half-volume\
`64` = Full volume

#### 0x49c - Voice Volume

_(values from 0 to 100, converted to base16)_

`00` = Muted\
`32` = Half-volume\
`64` = Full volume

**0x49d - SFX Volume**

_(values from 0 to 100, converted to base16)_

`00` = Muted\
`32` = Half-volume\
`64` = Full volume

#### **0x49e - Environment Volume**

_(values from 0 to 100, converted to base16)_

`00` = Muted\
`32` = Half-volume\
`64` = Full volume

#### **0x4b1 - Mouse Sensitivity**

_(values from 0 to 100, converted to base16)_

`00` = Slow\
`32` = Medium\
`64` = Fast

#### 0x4b2 - Guide

`00` = Gamepad\
`01` = DUALSHOCK 4\
`02` = Keyboard

#### 0x49f - Screen Mode

`00` = Fullscreen\
`01` = Borderless\
`02` = Windowed

#### 0x4a0 - Resolution Width

_(values in Single(float32), Only specific combinations from game settings are working - use values from same numbers)_

`800` - 1\
`1024` - 2\
`1280` - 3\
`1440` - 4\
`1600` - 5\
`1920` - 6

#### 0x4a4 - Resolution Height

_(values in Single(float32), Only specific combinations from game settings are working - use values from same numbers)_

`600` - 1\
`768` - 2\
`800` - 3\
`900` - 4, 5\
`1080` - 6

#### 0x4a8 - V-Sync

`00` = V-Sync off\
`01` = V-Sync on

#### 0x4a9 - Display Range Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4aa - Anti-Aliasing Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4ab - Post Processing Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4ac - Shadow Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4ad - Texture Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4ae - Effect Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4af - Foliage Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

#### 0x4b0 - Shading Quality

_(values from 0 to 4, lower value is lowest quality)_

`00` = Low\
`01` = Medium\
`02` = High\
`03` = Epic\
`04` = Cinematic&#x20;

## Action Keys

### 0x4bb - number of defined action keys
_(value converted to base16)_

`21` - 33 (default value)

_(Putting specific offsets won't be possible for the rest of the file)_

### Action Keys defined in order
_(Every key has 2 inputs each)_

_(Gamepad)_

`1` - Use Other Items\
`2` - Crouch\
`3` - Collect\
`4` - Jump\
`5` - Select Arrow/Bullet (Up)\
`6` - Select Arrow/Bullet (Down)\
`7` - Scroll (Up)\
`8` - Put Weapon Away\
`9` - Dash/Dodge\
`10` - Item Menu\
`11` - Battle Stance\
`12` - Use Attack Items\
`13` - Scroll (Down)\
`14` - Lantern\
`15` - Display System Menu\
`16` - Display Menu\

_(Keyboard)_

`17` - Use Other Items\
`18` - Crouch\
`19` - Collect\
`20` - Jump\
`21` - Select Arrow/Bullet (Up)\
`22` - Select Arrow/Bullet (Down)\
`23` - Scroll (Up)\
`24` - Put Weapon Away\
`25` - Dash/Dodge\
`26` - Item Menu\
`27` - Battle Stance\
`28` - Use Attack Items\
`29` - Scroll (Down)\
`30` - Lantern\
`31` - Display System Menu\
`32` - Display Menu\
`33` - Crouch (second one)

### Example of first Action Key
_(In base16)_

`07 00 00 00 50 41 44 5F 52 55 00 17 00 00 00 47 61 6D 65 70 61 64 5F 46 61 63 65 42 75 74 74 6F 6E 5F 54 6F 70 00`\
`07` - 7 (length of first input name)\
`00 00 00` - empty spaces\
`50 41 44 5F 52 55 00` - "PAD_RU " (converted to text)\
`17` - 23 (length of second input name)\
`00 00 00` - empty spaces\
`47 61 6D 65 70 61 64 5F 46 61 63 65 42 75 74 74 6F 6E 5F 54 6F 70 00` - "Gamepad_FaceButton_Top " (converted to text)\

_(Repeats for every key)_

## Movement Keys

File defines 14 Movement Keys

### Movement Keys defined in order

`1` - MoveForward (Gamepad)\
`2` - MoveForward (Keyboard)\
`3` - MoveForward (Keyboard)\
`4` - MoveRight (Gamepad)\
`5` - MoveRight (Keyboard)\
`6` - MoveRight (Keyboard)\
`7` - TurnRate (Gamepad)\
`8` - TurnRate (Keyboard)\
`9` - TurnRate (Keyboard)\
`10` - LookUpRate (Gamepad)\
`11` - LookUpRate (Keyboard)\
`12` - LookUpRate (Keyboard)\
`13` - Turn (Mouse)\
`14` - Lookup (Mouse)

### Example of first Movement Key
_(In base16)_

`0C 00 00 00 4D 6F 76 65 46 6F 72 77 61 72 64 00 0E 00 00 00 47 61 6D 65 70 61 64 5F 4C 65 66 74 59 00 00 00 80 3F`\
`0C` - 12 (length of key name)\
`00 00 00` - empty spaces\
`4D 6F 76 65 46 6F 72 77 61 72 64 00` - "MoveForward "  (converted to text)\
`0E` - 14 (length of input name)\
`00 00 00` - empty spaces\
`47 61 6D 65 70 61 64 5F 4C 65 66 74 59 00` - "Gamepad_LeftY" (converted to text)\
`00 00 80 3F` - 1 (converted to Single(float32))

_(Repeats for every key)_
