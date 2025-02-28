# Radxa_A5E_Firmware
This repository collects **UNOFFICIAL** firmware created by the community for the [Radxa Cubie A5E](http://radxa.com/products/cubie/a5e) . For official firmware, please visit [RADXA](http://radxa.com/products/cubie/a5e).

**Kindly note that some of the content in this repository has been sourced from online collections.**
**I do not provide any guarantees regarding the security or reliability of these materials. Any consequences arising from the use of the firmware shall be solely borne by the user.**

**NOTE** \
If the download file is in compressed format,you need decompression first. \
This image requires Allwinner’s Image tool for installation **if not advised otherwise**; commands similar to ‘dd’ cannot burn this image.
- Please use [PhoenixCard](https://dl.radxa.com/tools/windows/PhoenixCard_V4.3.1.zip) to flash the image to the SD card.
- Please use [PhoenixSuit](https://dl.radxa.com/tools/windows/PhoenixSuit_V2.0.4.zip) to flash the image to the eMMC or SPI FLASH. 


## 1. Debian11
- Lite: Console version, without desktop environment.
- XFCE: Desktop version, using the XFCE4 desktop environment.
- LXDE: Desktop version, using the LXDE desktop environment.
- GNOME: Desktop version, using the GNOME desktop environment.


| CPU | Version | Type | Download Link | Author | Known bugs | SHA256 | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A527 | XFCE(Tina5.0) | SD card | [MEGA](https://mega.nz/file/MLt3WKbC#d_hHfRL6DeKzfrb1PwtSLdyzuPiqq4S9vMAspfnPXpU) | [@Misaka-Nnnnq](https://github.com/Misaka-Nnnnq) | N/A | e40b622aee0d367a539a29e68ba63467b333e0119dd9a677ee2d63518e193c8e radxa_a5e_a527_debian11_xfce_unofficial_sdcard_rev4.7z | [Tina](https://linux-sunxi.org/Radxa_Cubie_A5E) |
| A527 | Lite(Tina5.0) | SD card | [MEGA](https://mega.nz/file/ZTMTjApZ#_R1njEa6qoQHu5YteaePQr1nvnpuT22m3m3TZhdN7Aw) | [@Misaka-Nnnnq](https://github.com/Misaka-Nnnnq) | N/A | 144552c73e6175e4bda1e7abd59bce2530295b267130f0ea118c66621a2b8390 radxa_a5e_a527_debian11_lite_unofficial_sdcard_rev4.7z | [Tina](https://linux-sunxi.org/Radxa_Cubie_A5E) |


## 2. Tina Kernel + OpenWRT rootfs
**WARNING**: The images generated using this method may have potential compatibility issues. Users are advised to conduct their own testing.

| CPU | Version | Type | Download Link | Author | Known bugs | SHA256 | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A527 | kwrt202502(Tina5.0) | SD card | [MEGA](https://mega.nz/file/AeElnYxa#iM91UcXNBDcPB92AZw2sM2G_uKq95woO6XfV5IrqLoY) | [@Misaka-Nnnnq](https://github.com/Misaka-Nnnnq) | NO WIFI | 20c8689c88cfc1cfdb9923c83c3dceab8ce8f53797e5fa04d1a4b1e31c324923 radxa_a5e_a527_kwrt_unofficial_sdcard_rev4.7z | [Tina kernel](https://linux-sunxi.org/Radxa_Cubie_A5E) + [kwrt rootfs](https://openwrt.ai/) |
| A527 | openwrt23.05(Tina5.0) | SD card | [MEGA](https://mega.nz/file/4aUylSDJ#xpkGDii4rAiL9aO6aBqFn1DXpt40eEGspsxhFMnL8v0) | [@Misaka-Nnnnq](https://github.com/Misaka-Nnnnq) | NO WIFI | a3fdd27336e2f75fd1c4bd529899f71d9c7df55e7e27169ea7a087df3b1c758d radxa_a5e_a527_openwrt_unofficial_sdcard_rev4.7z | [Tina kernel](https://linux-sunxi.org/Radxa_Cubie_A5E) + [openwrt rootfs](https://github.com/Misaka-Nnnnq/openwrt/tree/23.05-cubie-a5e) |

## 3. OpenWRT
| CPU | Version | Type | Download Link | Author | Known bugs | SHA256 | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A527 | openwrt23.05 | SD card | [MEGA](https://mega.nz/file/tbsDHKqS#OdIRNIA9_BI6GwKAd4x6ZGXZs1A9X-GobfMVbL0KjBg) | [@Misaka-Nnnnq](https://github.com/Misaka-Nnnnq) | N/A | 04cde37c9d86d5d7e0b0e3a055bed7ac81536fcfe4b8a1103cbe7f1595db3187 radxa_a5e_a527_openwrt23.05_opkernel_unofficial_sdcard_rev4.7z | [Github](https://github.com/Misaka-Nnnnq/openwrt/tree/23.05-cubie-a5e) |

## 4. MiniArch (legacy firmware, DO **NOT** use PhoenixCard/PhoenixSuit)
| CPU | Version | Type | Download Link | Author | Known bugs | SHA256 | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A527 | v20250206 | SD card | [Github](https://github.com/warpme/miniarch/releases/download/v20250206/MiniArch-20240715-6.12.12-board-a527.cubie_a5e-SD-Image.img.xz) | [Piotr Oniszczuk](https://github.com/warpme) | N/A | 47179db386ffa7f482f765e77b631518875f24343106c767c6235f411fa35d43 MiniArch-20240715-6.12.12-board-a527.cubie_a5e-SD-Image.img.xz | [Github](https://github.com/warpme/miniarch) |

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="
      https://api.star-history.com/svg?repos=Misaka-Nnnnq/Radxa_A5E_Firmware&type=Date&theme=dark
    "
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="
      https://api.star-history.com/svg?repos=Misaka-Nnnnq/Radxa_A5E_Firmware&type=Date
    "
  />
  <img
    alt="Star History Chart"
    src="https://api.star-history.com/svg?repos=Misaka-Nnnnq/Radxa_A5E_Firmware&type=Date"
  />
</picture>
