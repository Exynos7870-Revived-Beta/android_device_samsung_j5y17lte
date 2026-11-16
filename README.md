# TWRP for the Samsung Galaxy J5 2017

TWRP device tree for Samsung Galaxy J5 2017 (`j5y17lte`), based on the TWRP AOSP 12.1 manifest.

## Build
```bash
source build/envsetup.sh
lunch twrp_j5y17lte-eng
mka recoveryimage
```
The recovery image is `out/target/product/j5y17lte/recovery.img`.
