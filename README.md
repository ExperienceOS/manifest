# ExperienceOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/ExperienceOS/manifest -b eleven

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```


Credits:
=======
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**RevengeOS**](https://github.com/RevengeOS)
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**ABC**](https://github.com/ezio84?tab=repositories)
 * [**Project-Awaken**](https://github.com/Project-Awaken)
 * [**PixelExtended**](https://github.com/PixelExtended)
 * [**WaveOS**](https://github.com/Wave-Project)
 * [**HyconOS**](https://github.com/HyconOS)
