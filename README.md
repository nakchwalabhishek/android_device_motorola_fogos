Device tree for the Motorola moto g34 5G / moto g45 5G (fogos)

AOSPA (Paranoid Android) device configuration for the Qualcomm SM6375
(Snapdragon 695 / "holi") platform.

Ported from the LineageOS device tree. The proprietary vendor blobs, kernel and
hardware support are preserved from the LineageOS baseline; only the ROM/build
integration has been adapted for AOSPA `calcite` (Android 17 / CLO).

Build:

    source build/envsetup.sh
    lunch aospa_fogos-user
    mka bacon
