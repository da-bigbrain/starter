
### Files in `src/` (short map)

- `main.cpp` — program entry point and high-level initialization
- `config.h` — compile-time configuration and flags
- `ads1220_driver.*` — ADS1220 ADC driver (low-level SPI interactions)
- `eeg_streamer.*` — packages data read from ADC into streams for BLE or serial
- `ble_manager.*` — BLE stack integration (advertising, services, characteristics)
- `command_handler.*` — incoming command parsing and dispatch
- `led_controller.*` — on-board LED helpers and statuses
- `led_controller.*` and other small helpers — utility code
