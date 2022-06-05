pkgname=fcitx5-table-dayi3
pkgver=5.0.10
pkgrel=1
pkgdesc="Dayi3 tables for Fcitx5"
arch=('any')
url="https://github.com/fcitx/fcitx5-table-dayi3"
license=('GPL')
depends=('fcitx5-chinese-addons')
makedepends=('extra-cmake-modules' 'boost')

source=("fcitx5-table-dayi3.tar.xz")

sha512sums=('SKIP')


build(){
  cd $pkgname

  cmake -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_INSTALL_LIBDIR=/usr/lib .
  make
}

package() {
  cd $pkgname
  make DESTDIR="$pkgdir" install
}

