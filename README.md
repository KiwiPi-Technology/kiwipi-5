# KiwiPi 5

Official documentation, downloads and developer resources for KiwiPi 5, a Rockchip RK3588S single-board computer in the RK3588 family.

[KiwiPi website](https://kiwipi.com/) · [Product page](https://kiwipi.com/product/kiwi-pi-5/) · [Documentation center](https://kiwipi.com/document-center/) · [Contact KiwiPi](https://kiwipi.com/contact-us/)

[![KiwiPi 5 board](https://kiwipi.com/wp-content/uploads/2026/01/Kiwipi-5-4.webp)](https://kiwipi.com/product/kiwi-pi-5/)

## Technical configuration

| Component | Configuration |
| --- | --- |
| SoC | Rockchip RK3588S (RK3588 family), 8 nm |
| CPU | 4 × Cortex-A76 at 2.2 GHz + 4 × Cortex-A55 at 1.8 GHz |
| GPU | Arm Mali-G610 MC4 |
| NPU | 6 TOPS |
| RAM | 8 GB; optional 4 / 16 / 32 GB configurations |
| Onboard storage | 64 GB; optional 128 / 256 / 512 GB configurations |
| Storage expansion | microSD and PCIe 2.0 expansion |
| Display interfaces | HDMI 2.1, USB-C DisplayPort Alt Mode, 4-lane MIPI-DSI |
| Camera interfaces | 2 × 4-lane MIPI-CSI |
| USB | USB-C OTG, 1 × USB 3.0 host, 2 × USB 2.0 host |
| Networking | Gigabit Ethernet, Wi-Fi 6, Bluetooth 5.4 |
| Audio | 3.5 mm headset jack and onboard microphone |
| Power input | USB-C PD; follow the hardware manual for your board revision |
| Official OS downloads | Android 15, Ubuntu 24.04, Debian 12 |

Configuration options are listed on the [official product page](https://kiwipi.com/product/kiwi-pi-5/); availability depends on the ordered variant. Hardware revisions may differ. Refer to the matching hardware manual for connector pinouts and electrical limits.

## Board layout

[![KiwiPi 5 ports and expansion interfaces](https://kiwipi.com/wp-content/uploads/2026/01/kiwipi-5-rk3588s-ports-interface.webp)](https://kiwipi.com/product/kiwi-pi-5/)

Images: [official KiwiPi 5 product page](https://kiwipi.com/product/kiwi-pi-5/). Check the hardware manual for connector details applicable to your board revision.

## Start here

1. Identify your board model and hardware revision. KiwiPi 5, KiwiPi 5B and KiwiPi 5 Pro have separate resources.
2. Read the [hardware and user manuals](https://kiwipi.com/document-center/?dc_tab=5305.1).
3. Choose an operating system from [Downloads](docs/downloads.md).
4. Follow the firmware upgrade guide for the selected image and storage device.

Use the designated power input and data connector described in the manual for your board revision. Back up existing storage before flashing firmware.

## Operating systems

The official documentation center lists Android 15, Ubuntu 24.04 and Debian 12 for KiwiPi 5. Images remain in the official download storage; this repository does not contain OS binaries.

## Documentation

- [Downloads and developer resources](docs/downloads.md)
- [Documentation guide](docs/documentation.md)
- [Official product specifications](https://kiwipi.com/product/kiwi-pi-5/)

## Support

For product inquiries and help identifying the correct resources for your board, [contact KiwiPi](https://kiwipi.com/contact-us/).

Third-party tools and Rockchip materials retain their respective authors' terms. Links to source archives do not imply that every component has the same license.
