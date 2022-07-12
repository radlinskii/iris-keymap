# Iris rev. 6 keymap by radlinskii

![iris rev  6 by radlinskii lighting demo](https://user-images.githubusercontent.com/26116041/177010817-b87bbca4-4e71-4278-81b6-b85b6e5f978c.gif)

Keymap configuration files used to flash [Keebio's](https://keeb.io) Iris rev. 6 keyboard using [QMK](https://qmk.fm).

A version of the files necessary for flashing can also be found in the official qmk firmware repository [github.com/qmk/qmk_firmware/keyboards/keebio/iris/keymaps/radlinskii](https://github.com/qmk/qmk_firmware/tree/master/keyboards/keebio/iris/keymaps/radlinskii).

For usage information go to [QMK docs](https://docs.qmk.fm/#/newbs).

## Features:

-   [RGB Lighting layers](https://docs.qmk.fm/#/feature_rgblight?id=lighting-layers)
-   [MOD-TAPS](https://docs.qmk.fm/#/mod_tap)
-   [MOUSE KEYS](https://docs.qmk.fm/#/keycodes?id=mouse-keys)

## Layers:

### colemak - default

> [Colemak DH](https://colemakmods.github.io/mod-dh/) keyboard layout.

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="colemak layer keymap" src="https://user-images.githubusercontent.com/26116041/173403537-f2222651-c8ea-4c8b-b828-97520a222344.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="colemak layer lighting" src="https://user-images.githubusercontent.com/26116041/173681398-cdcff1a5-ae79-4409-950a-1b671c350f07.jpeg">

</details>

### qwerty - alternative default

> Can be set as persistent default layer.

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="qwerty layer keymap" src="https://user-images.githubusercontent.com/26116041/173403371-1551976a-2f95-4dbd-ba07-96936651871d.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="qwerty layer lighting" src="https://user-images.githubusercontent.com/26116041/173681525-aee3c927-995a-4f83-b688-ed8bfd3f8bb6.jpeg">

</details>

### numeric + symbols

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="numeric and symbols layer keymap" src="https://user-images.githubusercontent.com/26116041/177011426-a3fcc280-02ca-48c4-80a1-30d793bf13d5.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="numeric and symbols layer lighting" src="https://user-images.githubusercontent.com/26116041/173681689-0b864e35-0e02-4204-a469-6e872e704903.jpeg">

</details>

### navigation

> Layer with arrow navigation.

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="navigation layer keymap" src="https://user-images.githubusercontent.com/26116041/173408142-1e1c297e-57db-42f8-bc18-a04dd4e202c9.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="navigation layer lighting" src="https://user-images.githubusercontent.com/26116041/173681859-fa6f071a-98e9-48f8-a9a0-76d7510b302a.jpeg">

</details>

### mouse

> Layer with mouse navigation on the same keys as arrow navigation.

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="mouse layer keymap" src="https://user-images.githubusercontent.com/26116041/173402955-050ffd77-7b60-45dc-8e89-54cd43793132.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="mouse layer lighting" src="https://user-images.githubusercontent.com/26116041/173682436-07c32e5e-f415-463d-8c93-d2cbd4e406a1.jpeg">

</details>

### media and miscellaneous

> Used for media keys, switching default layer and keyboard reset.

<details>
    <summary>
        keymap
    </summary>

<img width="800" alt="media and miscellaneous layer keymap" src="https://user-images.githubusercontent.com/26116041/173402837-75ce8ab1-7fbe-454b-b165-b22d171f9ad1.png">

</details>
<details>
    <summary>
        lighting
    </summary>

<img width="800" alt="media and miscellaneous layer lighting" src="https://user-images.githubusercontent.com/26116041/173682188-3eab9c09-d466-4729-89ac-48e09f55564c.jpeg">

</details>

## Usage

Use [qmk-firmware](https://qmk.fm) to compile the keymap, example:

```bash
qmk compile -kb keebio/iris/rev6 -km radlinskii && cp ~/qmk_firmware/.build/keebio_iris_rev6_radlinskii.hex ~/Desktop/keebio_iris_rev6_radlinskii.hex
```
