# The ro's HelixPico Layout
## Layout

### Eucalyn R
```
 ,-----------------------------------------.             ,-----------------------------------------.
 | Tab  |   Q  |   W  |   ,  |   .  |   ;  |             |   M  |   R  |   D  |   Y  |   P  | Bksp |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |EscCtl|   A  |   O  |   E  |   I  |   U  |             |   B  |   G  |   T  |   S  |   N  |  '   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   F  |             |   H  |   J  |   K  |   L  |   /  |RShift|
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |Adjust| Esc  | Alt  | GUI  |EiLCmd|TabLow|Space | Bksp |EntRai|KaRCmd| Left | Down |  Up  |Right |
 `-------------------------------------------------------------------------------------------------'
```

### Qwerty
```
 ,-----------------------------------------.             ,-----------------------------------------.
 | Tab  |   Q  |   W  |   E  |   R  |   T  |             |   Y  |   U  |   I  |   O  |   P  | Bksp |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Ctrl |   A  |   S  |   D  |   F  |   G  |             |   H  |   J  |   K  |   L  |   ;  |  '   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   B  |             |   N  |   M  |   ,  |   .  |   /  |Enter |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |Adjust| Esc  | Alt  | GUI  | EISU |Lower |Space |Space |Raise | KANA | Left | Down |  Up  |Right |
 `-------------------------------------------------------------------------------------------------'
```

### Colemak
```
 ,-----------------------------------------.             ,-----------------------------------------.
 | Tab  |   Q  |   W  |   F  |   P  |   G  |             |   J  |   L  |   U  |   Y  |   ;  | Bksp |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Ctrl |   A  |   R  |   S  |   T  |   D  |             |   H  |   N  |   E  |   I  |   O  |  '   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   B  |             |   K  |   M  |   ,  |   .  |   /  |Enter |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |Adjust| Esc  | Alt  | GUI  | EISU |Lower |Space |Space |Raise | KANA | Left | Down |  Up  |Right |
 `-------------------------------------------------------------------------------------------------'
```

### Dvorak
```
 ,-----------------------------------------.             ,-----------------------------------------.
 | Tab  |   '  |   ,  |   .  |   P  |   Y  |             |   F  |   G  |   C  |   R  |   L  | Bksp |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Ctrl |   A  |   O  |   E  |   U  |   I  |             |   D  |   H  |   T  |   N  |   S  |  /   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 | Shift|   ;  |   Q  |   J  |   K  |   X  |             |   B  |   M  |   W  |   V  |   Z  |Enter |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |Adjust| Esc  | Alt  | GUI  | EISU |Lower |Space |Space |Raise | KANA | Left | Down |  Up  |Right |
 `-------------------------------------------------------------------------------------------------'
```

## Layers

|Priority|number|name|description|
| ---- | ---- | --- | --- |
|high|16|Adjust|Functions|
||5|Raise|Numeric charactors|
||4|Lower|Other charactors|
||3|Eucalyn|Eucalyn layout|
||2|Dvorak|Dvorak layout|
||1|Colemak|Colemak layout|
|low|0|Qwerty|QWERTY layout(base)|

### Lower
```
 ,-----------------------------------------.             ,-----------------------------------------.
 |   ~  |   !  |   @  |   #  |   $  |   %  |             |   ^  |   &  |   *  |   (  |   )  | Del  |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |  F1  |  F2  |  F3  |  F4  |  F5  |             |  F6  |   _  |   +  |   {  |   }  |  |   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |  F7  |  F8  |  F9  |  F10 |  F11 |             |  F12 |      | PrSc | Home | End  |      |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |      |      |      |      |      |      |      | Del  |      |      | Next | Vol- | Vol+ | Play |
 `-------------------------------------------------------------------------------------------------'
```

### Raise
```
 ,-----------------------------------------.             ,-----------------------------------------.
 |   `  |   1  |   2  |   3  |   4  |   5  |             |   6  |   7  |   8  |   9  |   0  | Del  |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |  F1  |  F2  |  F3  |  F4  |  F5  |             |  F6  |   -  |   =  |   [  |   ]  |  \   |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |  F7  |  F8  |  F9  |  F10 |  F11 |             |  F12 |      | PrSc |PageDn|PageUp|      |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |      |      |      |      |      |      |      | Del  |      |      | Next | Vol- | Vol+ | Play |
 `-------------------------------------------------------------------------------------------------'
```

### Adjust (Lower + Raise)
```
 ,-----------------------------------------.             ,-----------------------------------------.
 |      | Reset|      |      |      |      |             |      |      |      |      |      |      |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |Aud on|Audoff|MU TOG|MU MOD| Mac  |             | Win  |Qwerty|Colemk|Dvorak|Eucaln|      |
 |------+------+------+------+------+------|             |------+------+------+------+------+------|
 |      |CK TOG|CK RST| CK UP|CK DWN|      |             |      |      |RGB ON| HUE+ | SAT+ | VAL+ |
 |------+------+------+------+------+------+-------------+------+------+------+------+------+------|
 |      |      |      |      |      |      |      |      |      |      | MODE | HUE- | SAT- | VAL- |
 `-------------------------------------------------------------------------------------------------'
```

## Customize

see `qmk_firmware/keyboards/helix/pico/keymaps/default/rules.mk`

```
# Helix keyboard customize
# you can edit follows 6 Variables
#  jp: 以下の6つの変数を必要に応じて編集します。
OLED_ENABLE = no            # OLED_ENABLE
LOCAL_GLCDFONT = no         # use each keymaps "helixfont.h" insted of "common/glcdfont.c"
LED_BACK_ENABLE = no        # LED backlight (Enable WS2812 RGB underlight.)
LED_UNDERGLOW_ENABLE = no   # LED underglow (Enable WS2812 RGB underlight.)
LED_ANIMATIONS = yes        # LED animations
IOS_DEVICE_ENABLE = no      # connect to IOS device (iPad,iPhone)

```
## Compile

go to qmk top directory.
```
$ cd qmk_firmware
```

build
```
$ make helix/pico:roeucln
```

flash to keyboard
```
$ make helix/pico:roeucln:avrdude
```

## Link
* more detail wrote in Japanese [helix/Doc/firmware_jp.md](https://github.com/MakotoKurauchi/helix/blob/master/Doc/firmware_jp.md)
* [Helix top](https://github.com/MakotoKurauchi/helix)
