# Charybdis 4x6 Keymap Documentation

## Layer Overview

| Layer | Name         | Purpose                        | Access Method                     |
|-------|--------------|--------------------------------|-----------------------------------|
| 0     | QWERTY       | Default typing layer           | Default                           |
| 1     | F_layers     | Function keys & navigation     | Hold left thumb `mo 1`            |
| 2     | BT_layers    | Bluetooth controls             | Hold `B` key                      |
| 3     | scroll-layers| Trackball scroll mode          | Hold `F` key                      |
| 4     | snipe-layers | Trackball precision/snipe mode | Hold `S` key                      |
| 5     | symbols      | Programming symbols            | Hold left thumb `mo 5`            |

---

## Layer Access Keys (Special Keys)

### Layer-Tap Keys (on QWERTY layer)
These keys act as normal keys when tapped, but activate a layer when held:

| Key Position | Tap    | Hold              |
|--------------|--------|-------------------|
| `S`          | Types S| Activates Layer 4 (snipe) |
| `F`          | Types F| Activates Layer 3 (scroll)|
| `B`          | Types B| Activates Layer 2 (BT)    |

### Momentary Layer Keys
| Key Position       | Action                      |
|--------------------|-----------------------------|
| Left thumb (mo 1)  | Hold to activate F_layers   |
| Left thumb (mo 5)  | Hold to activate Symbols    |

---

## Layer 0: QWERTY (Default)

```
┌───────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────────┐
│  ESC  │  1  │  2  │  3  │  4  │  5  │       │  6  │  7  │  8  │  9  │  0  │ BKSPACE │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│  TAB  │  Q  │  W  │  E  │  R  │  T  │       │  Y  │  U  │  I  │  O  │  P  │   INS   │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│ SHIFT │  A  │ S/L4│  D  │ F/L3│  G  │       │  H  │  J  │  K  │  L  │  ;  │    '    │
├───────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────────┤
│ CTRL  │  Z  │  X  │  C  │  V  │ B/L2│       │  N  │  M  │  ,  │  .  │  /  │  RALT   │
└───────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────────┘
                    ┌─────┬─────┬─────┐       ┌─────┬─────┐
                    │SHIFT│ mo5 │ mo1 │       │ DEL │SPACE│  (Right side has trackball)
                    └─────┴─────┴─────┘       └─────┴─────┘
                          ┌─────┬─────┐       ┌─────┐
                          │ WIN │ ALT │       │ENTER│
                          └─────┴─────┘       └─────┘
```

**Legend:** `S/L4` = S on tap, Layer 4 on hold

---

## Layer 1: F_layers (Function & Navigation)

Activated by holding left thumb key (`mo 1`).

```
┌─────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────┐
│ F1  │ F2  │ F3  │ F4  │ F5  │ F6  │       │ F7  │ F8  │ F9  │ F10 │ F11 │ F12 │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │     │PgDn │PgUp │     │     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │LEFT │DOWN │ UP  │RIGHT│     │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │     │     │     │     │       │     │     │     │     │     │     │
└─────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────┘
                    ┌─────┬─────┬─────┐       ┌─────┬─────┐
                    │     │     │     │       │     │     │
                    └─────┴─────┴─────┘       └─────┴─────┘
```

**Key features:**
- Full F1-F12 row
- Arrow keys on HJKL (vim-style)
- Page Up/Down on U/I

---

## Layer 2: BT_layers (Bluetooth)

Activated by holding `B` key.

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

All keys transparent (pass through to layer below) except:
```
                    ┌─────┬─────┐
Thumb cluster:      │LCLK │RCLK │  (on Win/Alt positions)
                    └─────┴─────┘
```

---

## Layer 4: Snipe Layer

Activated by holding `S` key. Enables precision/snipe trackball mode.

All keys transparent (pass through to layer below) except:
```
                    ┌─────┬─────┐
Thumb cluster:      │LCLK │RCLK │  (on Win/Alt positions)
                    └─────┴─────┘
```

---

## Layer 5: Symbols

Activated by holding left thumb key (`mo 5`).

```
┌─────┬─────┬─────┬─────┬─────┬─────┐       ┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │  !  │  @  │  #  │  $  │  %  │       │  ^  │  &  │  *  │  (  │  )  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  `  │  <  │  >  │  |  │  \  │       │  "  │  +  │  /  │  _  │  :  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  ~  │  {  │  }  │  &  │  ?  │       │  '  │  -  │  *  │  =  │  ;  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤       ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │  (  │  )  │  [  │  ]  │       │     │     │     │     │     │     │
└─────┴─────┴─────┴─────┴─────┴─────┘       └─────┴─────┴─────┴─────┴─────┴─────┘
```

**Key features:**
- Shifted number row symbols (!@#$%^&*())
- Brackets and braces: `[ ] { } < >`
- Common programming symbols organized for easy access
- Quote characters: `` ` `` `"` `'`
- Operators: `+ - * / = | \ & ? : ;`
- Underscore and tilde for identifiers

---

## Timing Settings

```
Tap-hold timing (layer-tap keys):
- Tapping term: 300ms (hold threshold)
- Quick-tap: 150ms (for rapid repeated taps)
- Require prior idle: 125ms
- Flavor: balanced
```
