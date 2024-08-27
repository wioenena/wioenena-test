# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Barış Köprülü <wioenena@gmail.com>
pkgname=wioenena-test
pkgver=1.4
pkgrel=1
epoch=
pkgdesc="This package for testing!"
arch=('x86_64')
url="https://wioenena.com"
license=('GPL')
groups=()
depends=()
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
source=("wioenena-test")
noextract=()
sha256sums=("992e80a48e18c065997a4bfd871f79fd6cea5d83fbeb7ecce96159c2bcc89f30")
validpgpkeys=()


package() {
  cd "$srcdir"
  install -Dm755 "$srcdir/wioenena-test" "$pkgdir/usr/bin/wioenena-test"
}
