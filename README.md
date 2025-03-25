# di-qif-helper
This repository bundles the dependencies which are needed to build the qt installer framework

## content
A release of this repositroy contains a build of:
- qt 6.6.0 static build (https://github.com/qt/qt5)
- bzip2 (https://github.com/libarchive/bzip2)
- zlib (https://github.com/madler/zlib)
- xz (https://github.com/tukaani-project/xz)

## usage

Download the static qt 6.6.0 build

`gh release download --repo "barcoopensource/di-qif-helper" {version} --pattern "static-qt-660.zip" --output "static-qt-660.zip"`

Download the static bzip2 build

`gh release download --repo "barcoopensource/di-qif-helper" {version} --pattern "bzip2.zip" --output "bzip2.zip"`

Download the static zlib build

`gh release download --repo "barcoopensource/di-qif-helper" {version} --pattern "zlib.zip" --output "zlib.zip"`

Download the static xy build

`gh release download --repo "barcoopensource/di-qif-helper" {version} --pattern "xy.zip" --output "xy.zip"`

{version} represents the release version of this repository you want to download from.
