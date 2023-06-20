# ESP-32 tm1637-driven LCD library

## Introduction

This is an library of control TM1637 LCD 7-segment display using ESP-32 IDF toolchain [ESP-IDF](https://github.com/espressif/esp-idf).

## Features

### Display

- Display numbers
- Display raw segment data
- Display floating point numbers

### Buttons

- Scan button press

### Settings

- Set brightness
 
## Important notes

This library uses `ets_delay_us()` function to generate i2c-like control sequences. Please note - while using within FreeRTOS task will be blocked while data is transmitted. 

## Example

The example is available at: [./examples](examples/default_example)

## Source Code

The source is available from [GitHub hayschan/esp-tm1638](https://github.com/hayschan/esp-tm1638).

## License

The code in this project is licensed under the MIT license - see LICENSE for details.

## Reference

- [petrows/esp-32-tm1637: ESP-32 IDF library for control TM1637 LCD 7-Segment display](https://github.com/petrows/esp-32-tm1637)
- [etdds/esp-idf-lvgl-displays: An ESP IDF component for various development boards, running LVGL](https://github.com/etdds/esp-idf-lvgl-displays)

## Contacts

 * Email: hayschan@haysc.tech
