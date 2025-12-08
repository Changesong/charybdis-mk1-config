# Charybdis 4x6 Keymap Documentation

## Layer Overview

| Layer | Name         | Purpose                        | Access Method                     |
|-------|--------------|--------------------------------|-----------------------------------|
| 0     | QWERTY       | Default typing layer           | Default / `To0_macro`             |
| 1     | F_layers     | Function keys & navigation     | Hold right thumb `mo 1`           |
| 2     | BT_layers    | Bluetooth controls             | Hold `B` key / `To2_macro`        |
| 3     | scroll-layers| Trackball scroll mode          | Hold `F` key                      |
| 4     | snipe-layers | Trackball precision/snipe mode | Hold `S` key                      |

---

## Layer Access Keys (Special Keys)

### Layer-Tap Keys (on QWERTY layer)
These keys act as normal keys when tapped, but activate a layer when held:

| Key Position | Tap    | Hold              |
|--------------|--------|-------------------|
| `S`          | Types S| Activates Layer 4 (snipe) |
| `F`          | Types F| Activates Layer 3 (scroll)|
| `B`          | Types B| Activates Layer 2 (BT)    |

### Momentary Layer Key
| Key Position       | Action                      |
|--------------------|-----------------------------|
| Right thumb (mo 1) | Hold to activate F_layers   |

---

## Layer 0: QWERTY (Default)

```
┌───────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────────┐
│  ESC  │  1  │  2  │  3  │  4  │  5  │       │  6  │  7  │  8  │  9  │  0  │ BKSPACE │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│  TAB  │  Q  │  W  │  E  │  R  │  T  │       │  Y  │  U  │  I  │  O  │  P  │    \    │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│ CAPS  │  A  │ S/L4│  D  │ F/L3│  G  │       │  H  │  J  │  K  │  L  │  ;  │    '    │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│ SHIFT │  Z  │  X  │  C  │  V  │ B/L2│       │  N  │  M  │  ,  │  .  │  /  │  SHIFT  │
└───────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────────┘
                    ┌─────┬─────┬─────┐       ┌─────┬─────┐
                    │CTRL │SPACE│ mo1 │       │ DEL │SPACE│  (Right side has trackball)
                    └─────┴─────┴─────┘       └─────┴─────┘
                          ┌─────┬─────┐       ┌─────┐
                          │ WIN │ ALT │       │ENTER│
                          └─────┴─────┘       └─────┘
```

**Legend:** `S/L4` = S on tap, Layer 4 on hold

---

## Layer 1: F_layers (Function & Navigation)

Activated by holding right thumb key (`mo 1`).

```
┌─────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────┐
│ F1  │ F2  │ F3  │ F4  │ F5  │ F6  │       │ F7  │ F8  │ F9  │ F10 │ F11 │ F12 │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │  `  │  [  │  UP │  ]  │  -  │  =  │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │LCLK │LEFT │DOWN │RIGHT│PGUP │ DEL │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │LCLK │RCLK │     │     │PGDN │ INS │
└─────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────┘
                    ┌─────┬─────┬─────┐       ┌─────┬─────┐
                    │     │     │ TO0 │       │LCLK │RCLK │
                    └─────┴─────┴─────┘       └─────┴─────┘
```

**Key features:**
- Full F1-F12 row
- Arrow keys on right hand (IJKL-style, but actually on UIO and JKL)
- Brackets `[ ]`, grave `` ` ``, minus `-`, equals `=`
- Page Up/Down, Delete, Insert
- Mouse clicks available on trackball side

---

## Layer 2: BT_layers (Bluetooth)

Activated by holding `B` key or via `To2_macro`.

```
┌─────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │ BT0 │ BT1 │ BT2 │ BT3 │ BT4 │       │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │CLALL│     │     │     │     │       │     │     │     │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │BTCLR│     │     │       │BTNXT│     │     │     │     │     │
└─────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────┘
```

**Key features:**
- `BT0`-`BT4`: Select Bluetooth profile 0-4
- `CLALL`: Clear all Bluetooth pairings
- `BTCLR`: Clear current Bluetooth pairing
- `BTNXT`: Switch to next Bluetooth profile

---

## Layer 3: Scroll Layer

Activated by holding `F` key. Enables trackball scroll mode.

All keys transparent (pass through to layer below).

---

## Layer 4: Snipe Layer

Activated by holding `S` key. Enables precision/snipe trackball mode.

```
                                            ┌─────┬─────┐
Right hand home row has mouse clicks:       │LCLK │RCLK │ (on H, J positions)
                                            └─────┴─────┘
                    ┌─────┬─────┐
Thumb cluster:      │LCLK │RCLK │
                    └─────┴─────┘
```

---

## RGB Macros

| Macro       | Action                                              |
|-------------|-----------------------------------------------------|
| `To0_macro` | Return to Layer 0, restore RGB effect               |
| `To1_macro` | Go to Layer 1, set RGB to cyan (HSB 128,100,50)     |
| `To2_macro` | Go to Layer 2, set RGB to magenta (HSB 250,100,50)  |

---

## Timing Settings

```
Tap-hold timing (layer-tap keys):
- Tapping term: 200ms (hold threshold)
- Quick-tap: 150ms (for rapid repeated taps)
- Flavor: balanced
```
