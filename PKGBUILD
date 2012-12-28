# Maintainer: Robert Schwarz <mail@rschwarz.net>
pkgname="us_alive"
pkgver=1.0
pkgrel=1
pkgdesc="international keyboard layout without dead keys"
arch=("any")
url="https://github.com/leethargo/us_alive"
license=("MIT")
source=("us_alive")
noextract=("us_alive")
md5sums=('a043fe5e57fad58ee88d7670603af1a8')

package() {
  cd "$srcdir"
  install -Dm644 us_alive "$pkgdir/usr/share/X11/xkb/symbols/us_alive"
}
