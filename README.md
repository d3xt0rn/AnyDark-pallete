# AnyDark

**AnyDark** is a high-contrast dark color palette designed for terminals, editors, shells, and other developer tools.

It comes in two variants:

* **Classic** — balanced, warm, and slightly softer.
* **Xstyle** — darker, brighter, and more contrast-heavy.

> [!NOTE]
> AnyDark is designed to stay colorful and readable without becoming a washed-out gray theme.

## Preview
**Classic**
<img width="1220" height="149" alt="image" src="https://github.com/user-attachments/assets/9d5c0906-6fdf-41d4-be20-8519d8471f98" />

**Xstyle**
<img width="1222" height="149" alt="image" src="https://github.com/user-attachments/assets/458c8c41-f52f-4122-b7bb-aabce70cf291" />

---

## Variants

| Variant     | Style           | Contrast  | Best for            |
| ----------- | --------------- | --------- | ------------------- |
| **Classic** | Warm & balanced | High      | Everyday use        |
| **Xstyle**  | Dark & vivid    | Very high | Maximum readability |

### Classic

Classic uses a slightly lighter background and more restrained ANSI colors. It keeps the palette colorful while maintaining a comfortable visual balance.

### Xstyle

Xstyle pushes the contrast further with a darker background and significantly brighter ANSI colors.

> [!IMPORTANT]
> **Xstyle** is intentionally more vivid than Classic. If you prefer strong colors and highly visible syntax, Xstyle is the recommended variant.

---

# Classic

```conf
background #171717
foreground #EFE8E1
cursor #FF6A00
selection_background #E07000
selection_foreground #EFE8E1

color0  #171717
color1  #EC363C
color2  #19E657
color3  #E9BE3F
color4  #4A85E3
color5  #AF46EC
color6  #48C0EF
color7  #EFE8E1

color8  #4A4A4A
color9  #FF696F
color10 #4CF98A
color11 #FCEF6F
color12 #8DB8F6
color13 #DF79FF
color14 #7BF3FF
color15 #FFFBF4
```

### Classic Colors

| ANSI    | Normal    | Bright    |
| ------- | --------- | --------- |
| Black   | `#171717` | `#4A4A4A` |
| Red     | `#EC363C` | `#FF696F` |
| Green   | `#19E657` | `#4CF98A` |
| Yellow  | `#E9BE3F` | `#FCEF6F` |
| Blue    | `#4A85E3` | `#8DB8F6` |
| Magenta | `#AF46EC` | `#DF79FF` |
| Cyan    | `#48C0EF` | `#7BF3FF` |
| White   | `#EFE8E1` | `#FFFBF4` |

**Accent**

* Cursor: `#FF6A00`
* Selection: `#E07000`

---

# Xstyle

```conf
background #0B0D0F
foreground #FFF8F0
cursor #FF8500

selection_background #B85A12
selection_foreground #FFF8F0

color0  #0B0D0F
color1  #FF3038
color2  #20FF58
color3  #FFD02F
color4  #3F9BFF
color5  #C43CFF
color6  #20DFFF
color7  #FFF8F0

color8  #60656B
color9  #FF7077
color10 #69FF91
color11 #FFE875
color12 #83BCFF
color13 #E181FF
color14 #6EEDFF
color15 #FFFFFF
```

### Xstyle Colors

| ANSI    | Normal    | Bright    |
| ------- | --------- | --------- |
| Black   | `#0B0D0F` | `#60656B` |
| Red     | `#FF3038` | `#FF7077` |
| Green   | `#20FF58` | `#69FF91` |
| Yellow  | `#FFD02F` | `#FFE875` |
| Blue    | `#3F9BFF` | `#83BCFF` |
| Magenta | `#C43CFF` | `#E181FF` |
| Cyan    | `#20DFFF` | `#6EEDFF` |
| White   | `#FFF8F0` | `#FFFFFF` |

**Accent**

* Cursor: `#FF8500`
* Selection: `#B85A12`

---

## Design Philosophy

AnyDark follows a few simple principles:

* **Dark backgrounds** — reduce visual noise and make ANSI colors stand out.
* **High contrast** — text and syntax should remain readable at a glance.
* **Strong colors** — avoid dull, washed-out ANSI colors.
* **Warm whites** — reduce the cold gray appearance common in dark themes.
* **Orange accents** — cursor and selection provide a consistent visual identity.
* **Distinct bright colors** — bright ANSI colors are intentionally different from their normal counterparts.

> [!NOTE]
> AnyDark is not intended to be a strict color-standard palette. The colors are tuned for visual consistency and readability.

---

## Recommended Variant

### Choose **Classic** if you want:

* A balanced dark theme
* Strong colors without excessive brightness
* A warmer, more relaxed appearance
* Good everyday readability

### Choose **Xstyle** if you want:

* Maximum contrast
* A darker background
* Brighter ANSI colors
* More aggressive syntax highlighting
* A more vivid terminal

> [!TIP]
> If you are unsure, start with **Classic**. Xstyle is the better choice if you specifically prefer very high-contrast terminal themes.

---

## License

Use, modify, and adapt AnyDark freely unless a separate license is provided by the project.

---

## Credits

Created as the **AnyDark** color palette.

**Variants:** `Classic` · `Xstyle`
