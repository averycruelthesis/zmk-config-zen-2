# ZMK Keymap Reference - Corneish Zen

## Layout Overview
3x6 keys + 3 thumb keys per side

---

## QWERTY Layer (Base)
```
┌─────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬─────┐
│ ESC │  Q  │  W  │  E  │  R  │  T  │   │  Y  │  U  │  I  │  O  │  P  │BSPC │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│LSFT │  A  │  S  │  D  │  F  │  G  │   │  H  │  J  │  K  │  L  │  ;  │ENTER│
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│LCTL │  Z  │  X  │  C  │  V  │  B  │   │  N  │  M  │  ,  │  .  │  /  │RALT │
└─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                  │LCMD │ SPC │ TAB │   │ENTER│LSFT │ CMD │
                  │     │     │NVNM │   │ SYM │     │ OSL │
                  └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

---

## NAVNUM Layer (Left thumb hold)
```
┌─────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │     │  7  │  8  │  9  │LOCK │   │N_TAB│  G  │  &  │  0  │     │ V+  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │  4  │  5  │  6  │  0  │   │     │  ←  │  ↓  │  ↑  │  →  │ V-  │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │  1  │  2  │  3  │  X  │   │  =  │  *  │  -  │  +  │  /  │     │
└─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                  │     │     │ ### │   │     │     │     │
                  └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

**Volume Controls**: V+ (Vol Up), V- (Vol Down)  
**Macros**: LOCK (Cmd+Ctrl+Q), N_TAB (Cmd+T)

---

## SYMBOLS Layer (Right thumb hold)
```
┌─────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │  :  │  &  │  <  │  >  │  %  │   │  ~  │  {  │  }  │  |  │  !  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │  ;  │  $  │  (  │  )  │  '  │   │  "  │  [  │  ]  │  _  │  \  │     │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │  ^  │  @  │  #  │  `  │   │  =  │  *  │  -  │  +  │  /  │     │
└─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                  │     │     │     │   │ ### │     │     │
                  └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

---

## OSL Layer (Right thumb hold+tap)
```
┌─────┬─────┬─────┬─────┬─────┬─────┐   ┌─────┬─────┬─────┬─────┬─────┬─────┐
│     │Sc5  │C←   │C↑   │C→   │Sc4  │   │     │ F7  │ F8  │ F9  │ F12 │ BT← │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│CAPS │Cmd+Z│Cmd+X│Cmd+C│Cmd+V│Paste│   │     │ F4  │ F5  │ F6  │ F11 │ BT→ │
├─────┼─────┼─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┼─────┼─────┤
│     │     │Cmd+B│Cmd+I│Cmd+U│     │   │     │ F1  │ F2  │ F3  │ F10 │BTCLR│
└─────┴─────┴─────┼─────┼─────┼─────┤   ├─────┼─────┼─────┼─────┴─────┴─────┘
                  │     │→QWT │→NVN │   │→SYM │     │ ### │
                  └─────┴─────┴─────┘   └─────┴─────┴─────┘
```

**Shortcuts**:
- Sc4/Sc5: Cmd+Shift+4/5 (Screenshots)
- C←/C→: Ctrl+Left/Right (Desktop switch)
- Paste: Cmd+Alt+Shift+V (Paste special)
- BT←/BT→: Bluetooth Previous/Next
- BTCLR: Bluetooth Clear

---

## Key Activation Guide

- **NVNM**: Hold left thumb key (TAB key position)
- **SYM**: Hold right thumb key (ENTER key position)  
- **OSL**: Hold then tap right thumb key (CMD key position)

## Tips for Learning

1. **Volume**: NVNM layer, top/middle right corner
2. **Numbers**: NVNM layer, left hand 3x3 grid
3. **Arrows**: NVNM layer, right hand cluster
4. **Brackets**: SYM layer, right side
5. **Function keys**: OSL layer, right side

---

*Generated for ZMK Corneish Zen - Print this for your desk reference!*