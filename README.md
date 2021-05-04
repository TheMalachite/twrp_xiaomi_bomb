Device Tree for Redmi 10X Pro (bomb)
==========================================

The Redmi 10X Pro (codenamed _"bomb"_) is a high-end, mid-range smartphone from Xiaomi.
It was released in June 2020.

| Basic                   | Spec Sheet                                                                                                                     |
| -----------------------:|:------------------------------------------------------------------------------------------------------------------------------ |
| CPU                     | Octa-core                                                                                                                      |
| Chipset                 | Mediatek Dimensity 820 5G                                                                                                      |
| GPU                     | Mali-G57 MC5                                                                                                                   |
| Memory                  | 8 GB RAM                                                                                                                       |
| Shipped Android Version | 10.0                                                                                                                           |
| Storage                 | 128/256 GB                                                                                                                     |
| Battery                 | Non-removable Li-Po 4520 mAh battery                                                                                           |
| Display                 | 1080 x 2400 pixels, 20:9 ratio (~401 ppi density)                                                                              |
| Camera (Back)(Main)     | 48 MP, f/1.8, 26mm (wide), 1/2.0", 0.8µm, PDAF                                                                                 |
| Camera (Front)          | 20 MP, 26mm (wide)                                                                                                             |

## Device picture
![bomb](https://cdn-files.kimovil.com/default/0004/71/thumb_370807_default_big.jpeg)

## Build instructions

```
# Compiling
$ export ALLOW_MISSING_DEPENDENCIES=true
$ . build/envsetup.sh
$ lunch omni_bomb-eng
$ make -jx recoveryimage //replace x in -jx with number of cores you want to allot for compilation

```
## Kernel source

You can find the kernel source used in this tree at [MiCode/Xiaomi_Kernel_OpenSource](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/bomb-q-oss)

**Copyright 2021 The TWRP Open Source Project**
