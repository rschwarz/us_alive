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
md5sums=("90672d72952453b53af35704e7e2f64f")

package() {
  cd "$srcdir"
  install -Dm644 us_alive "$pkgdir/usr/share/X11/xkb/symbols/us_alive"
}
