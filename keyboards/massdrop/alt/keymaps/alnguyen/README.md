# megalithic (megakeys)

A macOS-specific keymap for [Drop ALT](https://drop.com/buy/drop-alt-mechanical-keyboard) configured in a standard 65% ANSI layout.


### Setup

1. `brew tap osx-cross/avr; brew tap PX4/homebrew-px4; brew install avr-gcc@8; brew link --force avr-gcc@8; brew install dfu-programmer dfu-util gcc-arm-none-eabi avrdude qmk; brew cask install qmk-toolbox;`
1. `qmk clone alnguyen/qmk_firmware`
1. `qmk setup`
1. `make massdrop/alt:alnguyen`
1. Launch QMK Toolbox
1. Open your newly compiled `massdrop_alt_alnguyen.hex`
1. Click the `Flash` button


#### References

- https://beta.docs.qmk.fm/tutorial/newbs_flashing


## Base Layer

```
,-------------------------------------------------------------------------------------------.
|  ESC |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |  0  |  -  |  =  |  BS  | DEL |
|-------------------------------------------------------------------------------------------+
| Tab/L3 |  Q  |  W  |  E  |  R  |  T  |  Y  |  U  |  I  |  O  |  P  |  [  |  ]  | |\ | Hme |
|-------------------------------------------------------------------------------------------+
|  Caps  |  A  |  S  |   D  |  F  |  G  |  H  |  J  |  K  |  L  |  ;  |  '  | Enter  | PgUp |
|-------------------------------------------------------------------------------------------+
|   Shift  |  Z  |  X  |  C  |  V  |  B  |  N  |  M  |  ,  |  .  |  /  |  Sh  |  Up  | PgDn |
|-------------------------------------------------------------------------------------------+
| Ctrl | Cmd | Alt |               Space               |  Alt  |  Fn  |  |  L  |  Dn  |  R  |
`-------------------------------------------------------------------------------------------'
```