# Wine App
## Building
> **_NOTE:_**  With org.wine.Sdk installed.
```console
flatpak run org.flatpak.Builder build-dir --repo=repo --force-clean org.wine.App.yml
```
---=
## Installing
```console
flatpak install --user ./repo org.wine.App
```
---
## Removing
```console
flatpak remove org.wine.App
```