# Building ZMK for the touchtype

## Standard Build

```
west build -p -d build/touchtype --board touchtype
```

## Flashing

`west` can be used to flash the board directly. Press the reset button once, and run:

```
west flash -d build/touchtype
```
