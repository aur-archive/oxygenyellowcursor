# Maintainer: Daniel Wallace <daniel.wallace at gatech dot edu> 
pkgname=oxygenyellowcursor
pkgver=20120419
pkgrel=2
pkgdesc="Oxygen_Yellow cursor from kdebase-workspace"
arch=("any")
url="http://kde-look.org/index.php?xcontentmode=36"
license=('unknown')
conflicts=("kdebase-workspace")
source=(https://dl.dropbox.com/u/10567/$pkgname.tar.xz)

package() {
  cd "$srcdir/"
  install -d "$pkgdir/usr/share/icons/"
  cp -dpr --no-preserve=ownership Oxygen_Yellow $pkgdir/usr/share/icons/Oxygen_Yellow
}

# vim:set ts=2 sw=2 et:
md5sums=('da117b6baa5ff516894e61b63737cdfc')
