# Hybrid MCC

This board contains the board support for Carleton University InSpace's hybrid control system's input control box. It is
called MCC for "Mission Control Center".

The board support is largely based off that for the W5500-EVB Pico, since that is the MCU being used.

## Usage

Clone this repository in the same directory as your `nuttx-apps` and `nuttx` directories. You will also need the Pico
SDK. Follow the [NuttX docs](https://nuttx.apache.org/docs/latest/platforms/arm/rp2040/index.html) for instructions.

```console
$ cd nuttx
$ ./tools/configure.sh ../hybrid-mcc/configs/<selected config>
$ make -j
```
