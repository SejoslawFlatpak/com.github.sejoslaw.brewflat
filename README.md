# com.github.sejoslaw.brewflat

## Building and installing
```
flatpak-builder --user --install --force-clean build-dir com.github.sejoslaw.brewflat.yaml
flatpak run com.github.sejoslaw.brewflat
```

## Install
```
curl -L -o /tmp/com.github.sejoslaw.brewflat.flatpak https://github.com/SejoslawFlatpak/com.github.sejoslaw.brewflat/releases/latest/download/com.github.sejoslaw.brewflat.flatpak
flatpak install --user /tmp/com.github.sejoslaw.brewflat.flatpak
rm /tmp/com.github.sejoslaw.brewflat.flatpak
```
