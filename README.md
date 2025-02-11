# M5 StampS3 で mruby/c を動作させる

## 取得方法

```console
$ git clone https://github.com/uist1idrju3i/M5StampS3_mrubyc.git
$ pio run -t upload
$ pio device monitor
```

## 動作確認環境

- M5 StampS3 (Espressif ESP32-S3)
- PlatformIO Core, version 6.1.16

```console
% pio pkg list
Resolving m5stack-stamps3 dependencies...
Platform espressif32 @ 6.10.0 (required: espressif32 @ 6.10.0)
├── framework-arduinoespressif32 @ 3.20017.241212+sha.dcc1105b (required: platformio/framework-arduinoespressif32 @ ~3.20017.0)
├── framework-espidf @ 3.50400.0 (required: platformio/framework-espidf @ ~3.50400.0)
├── tool-cmake @ 3.16.4 (required: platformio/tool-cmake @ ~3.16.0)
├── tool-esptoolpy @ 1.40501.0 (required: platformio/tool-esptoolpy @ ~1.40501.0)
├── tool-mkfatfs @ 2.0.1 (required: platformio/tool-mkfatfs @ ~2.0.0)
├── tool-mklittlefs @ 1.203.210628 (required: platformio/tool-mklittlefs @ ~1.203.0)
├── tool-mkspiffs @ 2.230.0 (required: platformio/tool-mkspiffs @ ~2.230.0)
├── tool-ninja @ 1.9.0 (required: platformio/tool-ninja @ ^1.7.0)
├── tool-openocd-esp32 @ 2.1100.20220706 (required: platformio/tool-openocd-esp32 @ ~2.1100.0)
├── tool-riscv32-esp-elf-gdb @ 12.1.0+20221002 (required: espressif/tool-riscv32-esp-elf-gdb @ ~12.1.0)
├── tool-xtensa-esp-elf-gdb @ 12.1.0+20221002 (required: espressif/tool-xtensa-esp-elf-gdb @ ~12.1.0)
├── toolchain-esp32ulp @ 1.23800.240113 (required: platformio/toolchain-esp32ulp @ ~1.23800.0)
├── toolchain-riscv32-esp @ 14.2.0+20241119 (required: platformio/toolchain-riscv32-esp @ 14.2.0+20241119)
└── toolchain-xtensa-esp-elf @ 14.2.0+20241119 (required: platformio/toolchain-xtensa-esp-elf @ 14.2.0+20241119)

Libraries
└── mrubyc @ 0.0.0+20250211225825.sha.4e2be54 (required: git+https://github.com/mrubyc/mrubyc.git#release3.3.1)
```
