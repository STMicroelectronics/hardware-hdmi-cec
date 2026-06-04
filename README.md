# hardware-hdmi_cec #

This module contains the STMicroelectronics android.hardware.tv.hdmi.cec 
and the android.hardware.tv.hdmi.connection source code.
It is part of the STMicroelectronics delivery for Android.

## Description ##

This module implements android.hardware.tv.hdmi.cec AIDL version 1 and
android.hardware.tv.hdmi.connection AIDL version 1.
Please see the Android delivery release notes for more details.

## Documentation ##

* The [release notes][] provide information on the release.
[release notes]: https://wiki.st.com/stm32mpu/wiki/STM32_MPU_OpenSTDroid_release_note_-_v6.2.0

## Dependencies ##

This module can't be used alone. It is part of the STMicroelectronics delivery for Android.

```
PRODUCT_PACKAGES += \
    android.hardware.tv.hdmi.connection-service.stm32mpu \
    android.hardware.tv.hdmi.cec-service.stm32mpu
```

## Contents ##

This directory contains the sources and associated Android build files to generate the HDMI CEC and HDMI connection service binaries.

## License ##

This module is distributed under the Apache License, Version 2.0 found in the [LICENSE](./LICENSE) file.
