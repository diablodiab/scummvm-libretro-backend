# libretro-scummvm-backend
Libretro backend for ScummVM which can be added to backends/platform folder of ScummVM base to build a Libretro core of ScummVM. The intention is be able to apply the backend without adjusting any of base ScummVM.

## How to use
1. Clone official ScummVM base
2. Go to subfolder scummvm/backends/platform
3. Clone libretro-scummvm-backend to folder "libretro"
4. Go to folder scummvm/backends/platform/libretro/build
5. Compile libretro-scummvm core

## Updating
When updating ScummVM, it's important to rebuild [scummvm.zip](aux-data/scummvm.zip) so that any auxiliary data is bundled in. The compile the new scummvm.zip, run the following command:

```
cd backends/platform/libretro/aux-data
./bundle_aux_data.bash
```
