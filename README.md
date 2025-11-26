# hardware-hdmi-cec #

This module contains the STMicroelectronics android.hardware.hdmi.cec binary source code.

It is part of the STMicroelectronics delivery for Android.

## Description ##

This module implements android.hardware.tv.cec HIDL version 1.
Please see the Android delivery release notes for more details.

## Documentation ##

* The [release notes][] provide information on the release.
[release notes]: https://wiki.st.com/stm32mpu-ecosystem-v5/wiki/STM32_MPU_OpenSTDroid_release_note_-_v5.1.0

## Dependencies ##

This module can not be used alone. It is part of the STMicroelectronics delivery for Android.

```
PRODUCT_PACKAGES += \
    android.hardware.tv.cec@1.0-service.stm32mpu
```

## Containing ##

This directory contains the sources and associated Android makefile to generate the HDMI CEC binary.

## License ##

This module is distributed under the Apache License, Version 2.0 found in the [LICENSE](./LICENSE) file.
