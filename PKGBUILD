# Maintainer: Stefan Zipproth <s.zipproth@ditana.org>

pkgname=ditana-mirrorlist
pkgver=1.12
pkgrel=1
pkgdesc="Ditana mirrorlist for pacman"
arch=(any)
url="https://ditana.org"
license=('AGPL-3.0-or-later')
conflicts=()
depends=()
makedepends=()
source=("file://${PWD}/ditana-mirrorlist")
sha256sums=('SKIP')

package() {
    install -D -m644 $srcdir/ditana-mirrorlist $pkgdir/etc/pacman.d/ditana-mirrorlist
}
