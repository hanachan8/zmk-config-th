Branches
- [Cannonball-LL](https://github.com/Taro-Hayashi/zmk-config-th/tree/Cannonball-LL)
- [Armors](https://github.com/Taro-Hayashi/zmk-config-th/tree/Armors)
- [Shotgun](https://github.com/Taro-Hayashi/zmk-config-th/tree/Shotgun)

## 2% Milk

The default configuration builds the `two_percent_milk` shield for the
`adafruit_kb2040` board. Its two keys are initially assigned to `X` and `Z`.

### Edit the keymap

1. Open [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/).
2. Choose GitHub and authorize the repository.
3. Select `config/two_percent_milk.keymap`.
4. Edit the bindings and save. The editor commits the updated keymap to GitHub,
   which triggers the firmware build workflow.

The editable keymap stays in `config/`. `config/info.json` supplies the visual
two-key layout, while `build.yaml` defines the matching board and shield used by
GitHub Actions.
