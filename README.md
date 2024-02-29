# APEXOS

## Getting Started

### Instructions
1. Run the following commands to sync source

```
repo init -u https://github.com/ApexOS/ApexOS.git -b 14.0 --git-lfs
```
2. To sync source, enter

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

3. Once the source is downloaded/synced, prepare your device trees, dependencies and start the build by the following commands

```
. build/envsetup.sh
```
```
lunch apex_<devicecodename>-user
```
```
make bacon -j$(nproc --all)
```

## Credits

 * [**LineageOS**](https://github.com/LineageOS)
 * [**CodeAurora Forum**](https://source.codeaurora.org/quic/la)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**ProtonAOSP**](https://github.com/ProtonAOSP)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC-ROM**](https://github.com/ezio84)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Syberia Project**](https://github.com/syberia-project)
 * [**Yet another AOSP project**](https://github.com/Yaap)
