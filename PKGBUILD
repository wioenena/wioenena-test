# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Barış Köprülü <wioenena@gmail.com>
pkgname=wioenena-test
pkgver=1.2
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
sha256sums=("f2077fa22065ad825b14b289bace138e010b8554171b96d54467d4b9e859a8a4")
validpgpkeys=()


package() {
  cd "$srcdir"
  install -Dm755 "$srcdir/wioenena-test" "$pkgdir/usr/bin/wioenena-test"
}
