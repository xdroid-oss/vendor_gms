# Google Mobile Services
This repository provides extracted Google Mobile Services (GMS) files from Google Pixel devices.

## Usage
To integrate GMS into your build, inherit the provided configuration file in your makefile by adding the following line:
```
$(call inherit-product-if-exists, vendor/gms/config.mk)
```

## Informations
```
Extracted from: google/komodo/komodo:16/BP2A.250605.031.A2/13578606:user/release-keys