# Photoshop Keymap for GIMP.

GIMP 不是 Photoshop 替代品。

本配置是将 Photoshop 快捷键移植到 GIMP。

建议采用 GIMP 自带的快捷键，我个人认为它对按键的分配比 Adobe 更合理。


## 安装

复制 `menurc` 文件到配置目录：

Linux/Mac: `~/.gimp-2.*`

Windows: `%appdata%\GIMP\2.10\`


*From Photoshop CC 2019.

## File
| Command        | Keybinding                     |   | Photoshop |
|:---------------|:-------------------------------|---|-----------|
| New            | `Ctrl` + `N`                   |   |           |
| Open           | `Ctrl` + `O`                   |   |           |
| Open as Layers | `Ctrl` + `Shift` + `O`         |   |           |
| Save           | `Ctrl` + `S`                   |   |           |
| Save As        | `Ctrl` + `Shift` + `S`         |   |           |
| Export As      | `Ctrl` + `Shift` + `Alt` + `W` | * |           |
| Print          | `Ctrl` + `P`                   |   |           |
| Close View     | `Ctrl` + `W`                   |   |           |
| Close all      | `Ctrl`+ `Shift` + `W`          |   |           |
| Quit           | `Ctrl` + `Q`                   |   |           |

## Edit
| Command            | Keybinding                     |   |  |
|:-------------------|:-------------------------------|---|--|
| Undo               | `Ctrl` + `Z`                   |   |  |
| Redo               | `Ctrl` + `Y`                   |   |  |
| Cut                | `Ctrl` + `X`                   |   |  |
| Copy               | `Ctrl` + `C`                   |   |  |
| Copy Visible       | `Ctrl` + `Shift` + `C`         |   |  |
| Paste              | `Ctrl` + `V`                   |   |  |
| Clear              | `Delete`                       |   |  |
| Paste In Place     | `Ctrl` + `Shift` + `V`         | * |  |
| Fill with BG Color | `Ctrl` + `Delete`              | * |  |
| Fill with FG Color | `Alt` + `Delete`               | * |  |
| Fill with Pattern  | `Shift` + `F5`                 | * |  |
| Keyboard Shortcuts | `Ctrl` + `Shift` + `Alt` + `K` | * |  |

## Select
| Command | Keybinding             |   |  |
|:--------|:-----------------------|---|--|
| All     | `Ctrl` + `A`           | * |  |
| None    | `Ctrl` + `D`           | * |  |
| Invert  | `Ctrl` + `Shift` + `I` | * |  |
| Float   | `Ctrl` + `Shift` + `L` |   |  |
| Feather | `Shift` + `F6`         | * |  |

## View
| Command             | Keybinding   |   |  |
|:--------------------|:-------------|---|--|
| Zoom Out            | `Ctrl` + `-` | * |  |
| Zoom In             | `Ctrl` + `=` | * |  |
| Fit Image in Window | `Ctrl` + `0` | * |  |
| 1:1 (100%)          | `Ctrl` + `1` | * |  |
| Show Guides         | `Ctrl` + `;` | * |  |
| Show Grid           | `Ctrl` + `'` | * |  |
| Show Rulers         | `Ctrl` + `R` | * |  |

## Image/Colors
| Command              | Keybinding             |   |  |
|:---------------------|:-----------------------|---|--|
| Canvas Size          | `Ctrl` + `Alt` + `C`   | * |  |
| Scale Image          | `Ctrl` + `Alt` + `I`   | * |  |
| Merge Visible Layers | `Ctrl` + `Shift` + `E` | * |  |
| Color Balance        | `Ctrl` + `B`           | * |  |
| Hue-Saturation       | `Ctrl` + `U`           | * |  |
| Levels               | `Ctrl` + `L`           | * |  |
| Curves               | `Ctrl` + `M`           | * |  |
| Desaturate           | `Ctrl` + `Shift` + `U` | * |  |
| Invert               | `Ctrl` + `I`           | * |  |

## Layers
| Command               | Keybinding             |   |  |
|:----------------------|:-----------------------|---|--|
| New Last Values       | `Ctrl` + `Shift` + `N` | * |  |
| New Layer Group       | `Ctrl` + `G`           | * |  |
| Duplicate Layer       | `Ctrl` + `J`           | * |  |
| Merge Down            | `Ctrl` + `E`           | * |  |
| Delete Layer          | `Shift` + `Delete`     | * |  |
| Select Next Layer     | `Alt` + `[`            | * |  |
| Select Previous Layer | `Alt` + `]`            | * |  |
| Raise Layer           | `Ctrl` + `]`           | * |  |
| Raise To Top          | `Ctrl` + `Shift` + `]` | * |  |
| Lower Layer           | `Ctrl` + `[`           | * |  |
| Lower To Bottom       | `Ctrl` + `Shift` + `[` | * |  |
| Lock Position         | `Ctrl` + `/`           | * |  |
| Layer Visible         | `Ctrl` + `,`           | * |  |


## Filters
| Command            | Keybinding           |   |  |
|:-------------------|:---------------------|---|--|
| Repeat Last Filter | `Ctrl` + `Alt` + `F` | * |  |

## Window - Dialogs
| Command | Keybinding |   |  |
|---------|:-----------|:--|--|
| Colors  | `F6`       | * |  |
| Layers  | `F7`       | * |  |

## Tools
| Command           | Keybinding    |   |  |
|:------------------|:--------------|---|--|
| Rectangle Select  | `M`           | * |  |
| Ellipse Select    | `Shift` + `M` | * |  |
| Free Select       | `L`           | * |  |
| Fuzzy Select      | `W`           | * |  |
| By Color Select   | `Shift` + `O` |   |  |
| Align             | `Q`           |   |  |
| Move              | `V`           | * |  |
| Crop              | `C`           | * |  |
| Rotate            | `Shift` + `R` |   |  |
| Scale             | `Shift` + `S` |   |  |
| Shear             | `Shift` + `H` |   |  |
| Perspective       | `Shift` + `P` |   |  |
| Unified Transform | `Ctrl` + `T`  | * |  |
| Handle Transform  | `Shift` + `L` |   |  |
| Paintbrush        | `B`           | * |  |
| Pencil            | `Shift` + `B` | * |  |
| Gradient          | `G`           |   |  |
| Bucket Fill       | `Shift` + `G` |   |  |
| Eraser            | `E`           | * |  |
| Clone Stamp Tool  | `S`           | * |  |
| Heal              | `J`           | * |  |
| Dodge / Burn      | `O`           | * |  |
| Paths             | `P`           | * |  |
| Flip              | `F`           |   |  |
| Text              | `T`           |   |  |
| Zoom              | `Z`           | * |  |
| Color Picker      | `I`           | * |  |
| Default Colors    | `D`           |   |  |
| Swap Colors       | `X`           |   |  |

## Misc.
| Command           | Keybinding        |   |  |
|:------------------|:------------------|---|--|
| Path to Selection | `Ctrl` + `Return` | * |  |

---

## References

- [Photoshop-ish Keyboard Shortcuts for The Gimp 2.8](http://epierce.freeshell.org/gimp/gimp_ps.php)

---

- [Gimp Tool](https://i.loli.net/2019/03/26/5c9a29125ff46.png)
- [Photosho Toolbar](https://i.loli.net/2019/03/26/5c9a29133a33a.png)
- [菜单 Diff](https://i.loli.net/2019/03/26/5c9a291419836.png)
