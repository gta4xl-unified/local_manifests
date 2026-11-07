### 📥 Clone the manifest

```bash
git clone https://github.com/gta4xl-unified/local_manifests.git -b lineage-24.0 .repo/local_manifests
```

### ⚡ Sync the sources

```bash
repo sync -c -j"$(nproc --all)" --no-clone-bundle --no-tags
```
