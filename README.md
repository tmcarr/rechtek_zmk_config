# rechtek_zmk_config

ZMK firmware config for a Boardsource Rechtek keyboard.

Forked from [boardsource/Rechtek_zmk_config](https://github.com/boardsource/Rechtek_zmk_config) — all credit for the original board and template goes to [Boardsource](https://boardsource.xyz).

## Changes from upstream

- `bs_lp_60` board migrated to Zephyr's hardware-model-v2 format, required to build against current ZMK `main`
- ZMK Studio support enabled
- USB/BLE output toggle key added
