# Maintainer: Michael Kuc <michaelkuc6 at gmail dot com>
# Contributor: Pavel Zinin <PZinin at gmail dot com>
pkgname=ksetwallpaper-git
pkgver=0.1
pkgrel=1
epoch=
pkgdesc="KDE set wallpaper script"
arch=('any')
url=""
license=('GPL3')
groups=()
depends=("python3")
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("ksetwallpaper.py")
noextract=()
validpgpkeys=()
sha256sums=('SKIP')

package() {
	install -Dm775 -t "${pkgdir}/usr/bin" "$srcdir/ksetwallpaper.py"
}
