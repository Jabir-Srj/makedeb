# Maintainer: Hunter Wittenborn <git@hunterwittenborn.me>

pkgname=makedeb
pkgver=1.0.4
pkgrel=1
pkgdesc="Make PKGBUILDs work on Debian-based distros"
arch=('any')
license=('GPL3')
url="https://github.com/hwittenborn/makedeb"

source=("https://github.com/hwittenborn/makedeb/archive/v${pkgver}.zip")
sha256sums=('SKIP')

package() {
  mkdir -p "${pkgdir}/usr/bin/"
  cp "${srcdir}/makedeb-${pkgver}/makedeb" "${pkgdir}/usr/bin/"
}