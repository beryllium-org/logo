# Maintainer: Bill Sideris <bill88t@feline.gr>

pkgname=beryllium-logo
pkgver=5.0
pkgrel=1
pkgdesc="Beryllium OS logo and icons"
arch=('any')
url="https://github.com/beryllium-org/Beryllium-Logo"
license=('GPL3')

replaces=('bredos-logo')
provides=('bredos-logo')
conflicts=('bredos-logo')

install=${pkgname}.install

source=('be.svg'
        'be.png'
        'be_black.svg'
        'be_clean.svg'
        'be_black_clean.svg'
        'be_mono.svg'
        'be_mono.png'
        'be_512x512.png'
        'be_256x256.png'
        'be_128x128.png'
        'be_64x64.png'
        'be_48x48.png'
        'be_32x32.png'
        'be_24x24.png'
        'be_16x16.png'
        'be_black_512x512.png'
        'be_black_256x256.png'
        'be_black_128x128.png'
        'be_black_64x64.png'
        'be_black_48x48.png'
        'be_black_32x32.png'
        'be_black_24x24.png'
        'be_black_16x16.png')
sha256sums=('fd230a66332f9b78ab5db2bc7793fae4041938d9d9d735e230fb9498a2a4748f'
            '35bb492b246ee05d4d714b61f86e81114b2e811d1091c38053ed67855cb5ffb1'
            '9df05c7770c7257cccc19b595fc6e4bb90fa2a15f0488b26d67f8a3bd2bc20e9'
            '1bac40f15f7f7e4857f08917fc3d2ec028a3bb9ab801e0d05fe6895a2c1365db'
            '1bac40f15f7f7e4857f08917fc3d2ec028a3bb9ab801e0d05fe6895a2c1365db'
            '21e48221bbc2fba5a2acae6d4050972215213cc2ebf2cca3d1d5046dfe7d9f6c'
            '3beeeba1297edb00a64e2c5945cb9b4af9dec689177a3be58b699ce472f8db17'
            'e932ec47d552d62f5cdf4047253edadc2dbf1bba1880734628fc9ca9b0c34ebb'
            'dae94ac87e5f52849b9ab35e5949a862c05c72e07d5a4374fc0c28a849b2bc20'
            '15a533d6058fb57765cc4aea8a29739b1c4affda9a21e6c0e17d107982043f88'
            '9361cb501dce6e6f37ccd4cc238806cf082f3bc20d90d34badcf1791f160fac5'
            '53244561819fa92c33f7e8196f2ba5858ac884cd9464e0a47bf08dbe154dda56'
            'a71a61606547e766938efda33292062ef532004459ea95b5898f303cc19643ac'
            'ccda2c684696cc050e828008666840db2e00958a1088b118c7f87d9a3a639efb'
            '663c4ee16d5bd555ba763f84f31b06e5f43aab37b86c0f78adca94bab55d89b4'
            '7d911e87715ba7bc63f3dc65fe290f37c63a5a7e23aea1ef77f7bcb0883df70e'
            '8766cbaf9ead1bc55207ca60e1f0b3743486f1ca3b0ac2dbe541a8a123036d27'
            '13e2ab04fa9e09b0c3e0a216c5cfca61f3883fd2fc1e58aad0d3f5f22d1035a3'
            '7abfa6e8ed83227a16c97981906aed6ba73e39c25509746457d9b58c2c250458'
            '591933c9d4cb6dc049adcb3b1c4887dd2c0e70f9921ca06b4017e3274bdf2c3c'
            'c3905bbf7d03f11644c6afdc8ec3cd48a2eb0a7a266f81dfd08c4bf93ae32f33'
            'c7519796d76369a16632991f8d9d36a9510a603cbb9b4efdbebb59304a486e90'
            'dfa9d70c4a5c7c53a37c356d46d6cfb8e3f96b7a0d8577e082d737523effc993')

package() {
    install -d \
        ${pkgdir}/usr/share/icons/hicolor/scalable/apps \
        ${pkgdir}/usr/share/icons/hicolor/16x16/apps \
        ${pkgdir}/usr/share/icons/hicolor/24x24/apps \
        ${pkgdir}/usr/share/icons/hicolor/32x32/apps \
        ${pkgdir}/usr/share/icons/hicolor/48x48/apps \
        ${pkgdir}/usr/share/icons/hicolor/64x64/apps \
        ${pkgdir}/usr/share/icons/hicolor/128x128/apps \
        ${pkgdir}/usr/share/icons/hicolor/256x256/apps \
        ${pkgdir}/usr/share/icons/hicolor/512x512/apps

    # Default white
    install -Dm644 ${srcdir}/be_16x16.png  ${pkgdir}/usr/share/icons/hicolor/16x16/apps/be.png
    install -Dm644 ${srcdir}/be_24x24.png  ${pkgdir}/usr/share/icons/hicolor/24x24/apps/be.png
    install -Dm644 ${srcdir}/be_32x32.png  ${pkgdir}/usr/share/icons/hicolor/32x32/apps/be.png
    install -Dm644 ${srcdir}/be_48x48.png  ${pkgdir}/usr/share/icons/hicolor/48x48/apps/be.png
    install -Dm644 ${srcdir}/be_64x64.png  ${pkgdir}/usr/share/icons/hicolor/64x64/apps/be.png
    install -Dm644 ${srcdir}/be_128x128.png ${pkgdir}/usr/share/icons/hicolor/128x128/apps/be.png
    install -Dm644 ${srcdir}/be_256x256.png ${pkgdir}/usr/share/icons/hicolor/256x256/apps/be.png
    install -Dm644 ${srcdir}/be_512x512.png ${pkgdir}/usr/share/icons/hicolor/512x512/apps/be.png

    # Default Black
    install -Dm644 ${srcdir}/be_black_16x16.png  ${pkgdir}/usr/share/icons/hicolor/16x16/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_24x24.png  ${pkgdir}/usr/share/icons/hicolor/24x24/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_32x32.png  ${pkgdir}/usr/share/icons/hicolor/32x32/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_48x48.png  ${pkgdir}/usr/share/icons/hicolor/48x48/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_64x64.png  ${pkgdir}/usr/share/icons/hicolor/64x64/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_128x128.png ${pkgdir}/usr/share/icons/hicolor/128x128/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_256x256.png ${pkgdir}/usr/share/icons/hicolor/256x256/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_512x512.png ${pkgdir}/usr/share/icons/hicolor/512x512/apps/be_black.png

    # Clean white
    install -Dm644 ${srcdir}/be_16x16.png  ${pkgdir}/usr/share/icons/hicolor/16x16/apps/be.png
    install -Dm644 ${srcdir}/be_24x24.png  ${pkgdir}/usr/share/icons/hicolor/24x24/apps/be.png
    install -Dm644 ${srcdir}/be_32x32.png  ${pkgdir}/usr/share/icons/hicolor/32x32/apps/be.png
    install -Dm644 ${srcdir}/be_48x48.png  ${pkgdir}/usr/share/icons/hicolor/48x48/apps/be.png
    install -Dm644 ${srcdir}/be_64x64.png  ${pkgdir}/usr/share/icons/hicolor/64x64/apps/be.png
    install -Dm644 ${srcdir}/be_128x128.png ${pkgdir}/usr/share/icons/hicolor/128x128/apps/be.png
    install -Dm644 ${srcdir}/be_256x256.png ${pkgdir}/usr/share/icons/hicolor/256x256/apps/be.png
    install -Dm644 ${srcdir}/be_512x512.png ${pkgdir}/usr/share/icons/hicolor/512x512/apps/be.png

    # Clean Black
    install -Dm644 ${srcdir}/be_black_16x16.png  ${pkgdir}/usr/share/icons/hicolor/16x16/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_24x24.png  ${pkgdir}/usr/share/icons/hicolor/24x24/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_32x32.png  ${pkgdir}/usr/share/icons/hicolor/32x32/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_48x48.png  ${pkgdir}/usr/share/icons/hicolor/48x48/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_64x64.png  ${pkgdir}/usr/share/icons/hicolor/64x64/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_128x128.png ${pkgdir}/usr/share/icons/hicolor/128x128/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_256x256.png ${pkgdir}/usr/share/icons/hicolor/256x256/apps/be_black.png
    install -Dm644 ${srcdir}/be_black_512x512.png ${pkgdir}/usr/share/icons/hicolor/512x512/apps/be_black.png

    # Defaults
    install -Dm644 ${srcdir}/be.png ${pkgdir}/usr/share/pixmaps/be.png

    # SVGs
    install -Dm644 ${srcdir}/be.svg ${pkgdir}/usr/share/icons/hicolor/scalable/apps/be.svg
    install -Dm644 ${srcdir}/be_mono.svg ${pkgdir}/usr/share/icons/hicolor/scalable/apps/be_mono.svg
    install -Dm644 ${srcdir}/be_black.svg ${pkgdir}/usr/share/icons/hicolor/scalable/apps/be_black.svg
    install -Dm644 ${srcdir}/be_clean.svg ${pkgdir}/usr/share/icons/hicolor/scalable/apps/be_clean.svg
    install -Dm644 ${srcdir}/be_black_clean.svg ${pkgdir}/usr/share/icons/hicolor/scalable/apps/be_black_clean.svg
}

