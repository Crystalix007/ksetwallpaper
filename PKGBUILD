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
source=("$pkgname::git+https://github.com/Crystalix007/ksetwallpaper.git")
noextract=()
validpgpkeys=()
sha256sums=('SKIP')

package() {
	cd "$pkgname"
	install -Dm775 -t "${pkgdir}/usr/bin" "ksetwallpaper.py"
}
