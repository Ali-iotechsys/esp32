# ESP32 Examples
### Board Info:
ESP32 WROOM-32 USB-Type C Development Board Dual Core WiFi Bluetooth: [spec](./doc/specification.txt).

```shell
$ espflash board-info
[2024-04-11T15:03:46Z INFO ] Serial port: '/dev/ttyUSB0'
[2024-04-11T15:03:46Z INFO ] Connecting...
[2024-04-11T15:03:46Z INFO ] Using flash stub
Chip type:         esp32 (revision v3.1)
Crystal frequency: 40 MHz
Flash size:        4MB
Features:          WiFi, BT, Dual Core, 240MHz, Coding Scheme None
MAC address:       ec:64:c9:86:89:c8
```

### ESP32 examples in Rust:
- [Hello World](./hello/src/main.rs)
- [Blink LED](./blinky/src/main.rs)

### ESP32 DevKit_C Layout: ![link](./esp32-wroom32.png)

### Espressif Book:
- [Link 1](https://docs.esp-rs.org/book/introduction.html)
- [Link 2](https://docs.esp-rs.org/book/writing-your-own-application/nostd.html)

### Troubleshooting:
- `dev/ttyUSB0` device disconnect: [link](https://askubuntu.com/questions/1454633/dev-ttyusb0-device-connects-then-is-forced-to-disconnect-by-another-device/1454639#1454639)


