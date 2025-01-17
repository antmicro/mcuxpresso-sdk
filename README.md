
# MCUXpresso-SDK

This repository is auto-generated from the files from [NXP SDK code](https://github.com/nxp-mcuxpresso/mcux-sdk).
The purpose of this repository is to be used as a module for [Pigweed](https://pigweed.dev) applications targeting the NXP RT595 MCUs.
The repository includes bazel rules allowing seamless integration into Pigweed's build system.

## Used Revisions

| Name | Revision | Source |
| ---- | -------- | ------ |
| mcuxpresso-sdk | [`6f3fd257cdcf978a4d26e7d6e9eed9240037422b`](https://github.com/nxp-mcuxpresso/mcux-sdk/tree/6f3fd257cdcf978a4d26e7d6e9eed9240037422b) | https://github.com/nxp-mcuxpresso/mcux-sdk |
| mcux-sdk-examples | [`8ebfdb8c37c30b3c8e312d32ba7b0967f01c0bec`](https://github.com/nxp-mcuxpresso/mcux-sdk-examples/tree/8ebfdb8c37c30b3c8e312d32ba7b0967f01c0bec) | https://github.com/nxp-mcuxpresso/mcux-sdk-examples |
| FreeRTOS-Kernel | [`4fe54c5f639770ce271dd3693a5cd5475969ae67`](https://github.com/nxp-mcuxpresso/FreeRTOS-Kernel/tree/4fe54c5f639770ce271dd3693a5cd5475969ae67) | https://github.com/nxp-mcuxpresso/FreeRTOS-Kernel |
| mcux-sdk-middleware-sdmmc | [`40283d30576ff0c8870f83a2b3c9c052740884c8`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-sdmmc/tree/40283d30576ff0c8870f83a2b3c9c052740884c8) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-sdmmc |
| mcux-sdk-middleware-multicore | [`0b7708aff16c1282db3c44eda6704c07e68dbbac`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-multicore/tree/0b7708aff16c1282db3c44eda6704c07e68dbbac) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-multicore |
| rpmsg-lite | [`72cb08881910b9956a283b0db903153d63be32be`](https://github.com/nxp-mcuxpresso/rpmsg-lite/tree/72cb08881910b9956a283b0db903153d63be32be) | https://github.com/nxp-mcuxpresso/rpmsg-lite |
| erpc | [`90ae2314d9f495ad2a3678a2fb82ac327ea2f134`](https://github.com/EmbeddedRPC/erpc/tree/90ae2314d9f495ad2a3678a2fb82ac327ea2f134) | https://github.com/EmbeddedRPC/erpc |
| mcux-soc-svd | [`e93e0b0067b9297de056de4cef6425c9c999fda4`](https://github.com/nxp-mcuxpresso/mcux-soc-svd/tree/e93e0b0067b9297de056de4cef6425c9c999fda4) | https://github.com/nxp-mcuxpresso/mcux-soc-svd |
| fatfs | [`e60fdc5242db843f242b4f8d4016932cafd2e45f`](https://github.com/nxp-mcuxpresso/fatfs/tree/e60fdc5242db843f242b4f8d4016932cafd2e45f) | https://github.com/nxp-mcuxpresso/fatfs |
| mcux-sdk-middleware-eiq | [`0bbdcac476d72d6c391ac4b0243df23ae89766a3`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-eiq/tree/0bbdcac476d72d6c391ac4b0243df23ae89766a3) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-eiq |
| mcux-sdk-middleware-deepviewrt | [`f05edd77ad66e40e1853a77f62357f73ac9ddfea`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-deepviewrt/tree/f05edd77ad66e40e1853a77f62357f73ac9ddfea) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-deepviewrt |
| mcux-sdk-middleware-glow | [`3c25ad52dfb6e8deff100c721e0f493b73207b6a`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-glow/tree/3c25ad52dfb6e8deff100c721e0f493b73207b6a) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-glow |
| mcux-sdk-middleware-tensorflow | [`994f6d0261337c2cd48c692161f3ff4783b72daa`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-tensorflow/tree/994f6d0261337c2cd48c692161f3ff4783b72daa) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-tensorflow |
| mcux-sdk-middleware-usb | [`ed235e3e785993459080a36fb07049da21449ae3`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-usb/tree/ed235e3e785993459080a36fb07049da21449ae3) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-usb |
| mcux-sdk-middleware-edgefast-bluetooth | [`d0e1a2a419370f69569898191b161d8f2beac272`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-edgefast-bluetooth/tree/d0e1a2a419370f69569898191b161d8f2beac272) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-edgefast-bluetooth |
| mcux-sdk-middleware-ethermind | [`96fee6b419b34cb2be652d3b79b37e7cd4e4fafe`](https://github.com/NXP/mcux-sdk-middleware-ethermind/tree/96fee6b419b34cb2be652d3b79b37e7cd4e4fafe) | https://github.com/NXP/mcux-sdk-middleware-ethermind |
| azure-rtos | [`7348f5d379ea0adaf363a3d6ab234ebcf84eb7f0`](https://github.com/NXP/azure-rtos/tree/7348f5d379ea0adaf363a3d6ab234ebcf84eb7f0) | https://github.com/NXP/azure-rtos |
| threadx | [`20cc14c1e39db4e4a92cee6eea5f6ad4eb904219`](https://github.com/NXP/threadx/tree/20cc14c1e39db4e4a92cee6eea5f6ad4eb904219) | https://github.com/NXP/threadx |
| filex | [`72b1d883d6e61b090b7148aead305ed23a17dd13`](https://github.com/NXP/filex/tree/72b1d883d6e61b090b7148aead305ed23a17dd13) | https://github.com/NXP/filex |
| levelx | [`e79d22d5a6213313de83412c81e00b95a90d424a`](https://github.com/NXP/levelx/tree/e79d22d5a6213313de83412c81e00b95a90d424a) | https://github.com/NXP/levelx |
| netxduo | [`f3b1d978453a08f1e9de1e14b17f07801776d1c2`](https://github.com/NXP/netxduo/tree/f3b1d978453a08f1e9de1e14b17f07801776d1c2) | https://github.com/NXP/netxduo |
| usbx | [`c2e2c213f8dbf4dd13dcaf3ffa9ee9b29c6ef04f`](https://github.com/NXP/usbx/tree/c2e2c213f8dbf4dd13dcaf3ffa9ee9b29c6ef04f) | https://github.com/NXP/usbx |
| guix | [`a4ad6823bae292f0ab012eb3076093b7b1e03c26`](https://github.com/NXP/guix/tree/a4ad6823bae292f0ab012eb3076093b7b1e03c26) | https://github.com/NXP/guix |
| mbedtls | [`f51f6ace3f156c43c54b56dd90c2e92e9413c074`](https://github.com/nxp-mcuxpresso/mbedtls/tree/f51f6ace3f156c43c54b56dd90c2e92e9413c074) | https://github.com/nxp-mcuxpresso/mbedtls |
| wifi_nxp | [`738269c3ec6d4638df97932638f635359b1f8596`](https://github.com/NXP/wifi_nxp/tree/738269c3ec6d4638df97932638f635359b1f8596) | https://github.com/NXP/wifi_nxp |
| lwip | [`8bcc5523446e1d807d3a98e920e52b28581ba25d`](https://github.com/nxp-mcuxpresso/lwip/tree/8bcc5523446e1d807d3a98e920e52b28581ba25d) | https://github.com/nxp-mcuxpresso/lwip |
| littlefs | [`37158b252a0d5da7bdd5a1d1278f56b20d469717`](https://github.com/nxp-mcuxpresso/littlefs/tree/37158b252a0d5da7bdd5a1d1278f56b20d469717) | https://github.com/nxp-mcuxpresso/littlefs |
| maestro | [`88b02a991199f99fffa19ea3238d21617b917f16`](https://github.com/nxp-mcuxpresso/maestro/tree/88b02a991199f99fffa19ea3238d21617b917f16) | https://github.com/nxp-mcuxpresso/maestro |
| mcuboot | [`20b45dca47c66397592842ac54fdf54ad5cd1426`](https://github.com/nxp-zephyr/mcuboot/tree/20b45dca47c66397592842ac54fdf54ad5cd1426) | https://github.com/nxp-zephyr/mcuboot |
| CMSIS_5 | [`ace291fb56654b2a62b4a80cbba8a75abb36aa18`](https://github.com/nxp-mcuxpresso/CMSIS_5/tree/ace291fb56654b2a62b4a80cbba8a75abb36aa18) | https://github.com/nxp-mcuxpresso/CMSIS_5 |
| EAP | [`9a84b5c99c87d60b817e44b80a2f5db66f7a688c`](https://github.com/nxp-mcuxpresso/EAP/tree/9a84b5c99c87d60b817e44b80a2f5db66f7a688c) | https://github.com/nxp-mcuxpresso/EAP |
| VIT | [`d23d588bf6cec259e3654a0efcde35cf3f4b1cb0`](https://github.com/nxp-mcuxpresso/VIT/tree/d23d588bf6cec259e3654a0efcde35cf3f4b1cb0) | https://github.com/nxp-mcuxpresso/VIT |
| VoiceSeeker | [`056d650e60482db5f8a8455050bd3af1ac9bb0ea`](https://github.com/nxp-mcuxpresso/VoiceSeeker/tree/056d650e60482db5f8a8455050bd3af1ac9bb0ea) | https://github.com/nxp-mcuxpresso/VoiceSeeker |
| NatureDSP | [`f66bf675f628a12d06a0b6f55957785989037e3d`](https://github.com/nxp-mcuxpresso/NatureDSP/tree/f66bf675f628a12d06a0b6f55957785989037e3d) | https://github.com/nxp-mcuxpresso/NatureDSP |
| wpa_supplicant-rtos | [`e7ea6740f896a7ef7348e95bb5d4ebe770c29e8b`](https://github.com/nxp-mcuxpresso/wpa_supplicant-rtos/tree/e7ea6740f896a7ef7348e95bb5d4ebe770c29e8b) | https://github.com/nxp-mcuxpresso/wpa_supplicant-rtos |
| mcux-sdk-middleware-connectivity-framework | [`e8ea202c296f3191a15d48da259f5e70ccc60fa8`](https://github.com/NXP/mcux-sdk-middleware-connectivity-framework/tree/e8ea202c296f3191a15d48da259f5e70ccc60fa8) | https://github.com/NXP/mcux-sdk-middleware-connectivity-framework |
| mcux-sdk-middleware-bluetooth-controller | [`f75dee7b2bcbfa8965e4641540ee27f0336c969b`](https://github.com/NXP/mcux-sdk-middleware-bluetooth-controller/tree/f75dee7b2bcbfa8965e4641540ee27f0336c969b) | https://github.com/NXP/mcux-sdk-middleware-bluetooth-controller |
| mcux-sdk-middleware-bluetooth-host | [`e05fc5e06a47eaf3dc574591fb5fc6bedcada746`](https://github.com/NXP/mcux-sdk-middleware-bluetooth-host/tree/e05fc5e06a47eaf3dc574591fb5fc6bedcada746) | https://github.com/NXP/mcux-sdk-middleware-bluetooth-host |
| mcux-sdk-middleware-ieee_802.15.4 | [`9e9405b9ff612aec12c243a3cb2c97e80e11ac06`](https://github.com/NXP/mcux-sdk-middleware-ieee_802.15.4/tree/9e9405b9ff612aec12c243a3cb2c97e80e11ac06) | https://github.com/NXP/mcux-sdk-middleware-ieee_802.15.4 |
| mcux-sdk-middleware-zigbee | [`3ca9a32c1d631e92fb2d6c56c4ce6930914580e9`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-zigbee/tree/3ca9a32c1d631e92fb2d6c56c4ce6930914580e9) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-zigbee |
| mcux-secure-subsystem | [`24e5dcd941fcc21456b2fdfabe828ee22d642bad`](https://github.com/nxp-mcuxpresso/mcux-secure-subsystem/tree/24e5dcd941fcc21456b2fdfabe828ee22d642bad) | https://github.com/nxp-mcuxpresso/mcux-secure-subsystem |
| mcux-sdk-middleware-xcvr | [`98bd94fd88b02ecba495d0783b4ce71e2229bdbc`](https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-xcvr/tree/98bd94fd88b02ecba495d0783b4ce71e2229bdbc) | https://github.com/nxp-mcuxpresso/mcux-sdk-middleware-xcvr |

## Running generation script locally

The script used to generate this repository is part of [Pigweed](https://pigweed.dev).
To generate this repository locally, you will have to [setup Pigweed](https://pigweed.dev/docs/get_started)
on your machine. After that, you can run this command to generate this repository.

```sh
bazelisk run //pw_build_mcuxpresso/py:mcuxpresso_builder -- EVK-MIMXRT595_manifest_v3_14.xml \
  --mcuxpresso-repo=https://github.com/nxp-mcuxpresso/mcux-sdk \
  --mcuxpresso-rev=MCUX_2.16.000 \
  --device-core=cm33_MIMXRT595S \
  --output-path=bazel-out/k8-fastbuild/bin/mcuxpresso-sdk \
  --clean \
  --include \
  project_template.evkmimxrt595.MIMXRT595S \
  component.serial_manager_uart.MIMXRT595S \
  platform.drivers.flexcomm_i2c.MIMXRT595S \
  platform.drivers.i3c.MIMXRT595S \
  platform.drivers.flexcomm_spi.MIMXRT595S \
  platform.drivers.flexcomm_usart_dma.MIMXRT595S \
  platform.drivers.flexcomm_usart_freertos.MIMXRT595S \
  platform.drivers.flexio_spi.MIMXRT595S \
  platform.drivers.inputmux.MIMXRT595S \
  platform.drivers.lpc_dma.MIMXRT595S \
  platform.drivers.lpc_gpio.MIMXRT595S \
  platform.drivers.mu.MIMXRT595S \
  platform.drivers.pint.MIMXRT595S \
  platform.drivers.power.MIMXRT595S \
  component.serial_manager.MIMXRT595S \
  platform.utilities.assert.MIMXRT595S \
  utility.debug_console.MIMXRT595S \
  --exclude \
  device.MIMXRT595S_startup.MIMXRT595S \
  middleware.freertos-kernel.MIMXRT595S
```

## License
Files taken from the NXP SDK repository are licensed under the BSD-3-Clause license.
