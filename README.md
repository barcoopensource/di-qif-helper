# di-qif-helper
This repository bundles the dependencies which are needed to build the qt installer framework

## content
A release of this repositroy contains a build of:
- qt 6.6.0 static build (https://github.com/qt/qt5)
- bzip2 (https://github.com/libarchive/bzip2)
- zlib (https://github.com/madler/zlib)
- xz (https://github.com/tukaani-project/xz)

## usage

gh release download --repo "barcoopensource/di-qif-helper" *version* --pattern "static-qt-6.6.0.zip" --output "static-qt-6.6.0.zip"
