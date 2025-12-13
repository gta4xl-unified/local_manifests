# 🐉 Local Manifests for gta4xl [SM-P615]

![Android Version](https://img.shields.io/badge/Android-16%20%2F%20LineageOS%2023-green?style=for-the-badge&logo=android)
![Device](https://img.shields.io/badge/Device-gta4xl-blue?style=for-the-badge&logo=samsung)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## ⚜️ Overview

It contains the local manifest XMLs required to sync all necessary repositories (Device tree, Kernel, Vendor blobs, and Hardware HALs) for building custom ROMs for the **Samsung Galaxy Tab S6 Lite LTE (Exynos 9611) [SM-P615]**.

## 🚀 Clone the Local Manifests
```bash
git clone https://github.com/gta4xl-unified/local_manifests .repo/local_manifests
```
## ⚡ Sync up
```bash
repo sync -c -j$(nproc) --force-sync --no-clone-bundle --no-tags
```
## 🤝 Credits
- LineageOS - For the base platform.
- Linux4 - For initial device bring-up and maintenance.
