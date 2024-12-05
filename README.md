# Downloading sources and build tools 

```bash
mkdir oplus-kernel_manifest && cd oplus-kernel_manifest
```

```bash
repo init -u https://github.com/schqiushui/kernel_manifest.git -b oplus_sm7675_v -m ace3v_v.xml
```

```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```

# How to build
```bash
./kernel_platform/oplus/build/oplus_build_kernel.sh pineapple gki
```

