# Contributor: Eltigreasesino
pkgname=iscan-plugin-cx4400-fixed
pkgver=2.1.3
pkgrel=1
pkgdesc="iscan plugin for Epson Stylus CX4300/CX4400/CX4450/CX5500/CX5600/DX4400/DX4450 scanners."
arch=('i686')
url="http://download.ebz.epson.net/dsc/du/02/DriverDownloadInfo.do?LG2=ES&CN2=&DSCMI=15833&DSCCHK=39c8d6560988f8ddd55e9a11c6d11d6f60bc3c91"
license=('GPL' 'LGPL' 'EAPL')
depends=('iscan')
makedepends=('rpmextract')
source=("http://a1227.g.akamai.net/f/1227/40484/1d/download.ebz.epson.net/dsc/f/01/00/01/58/33/7194a67418bc9c58c6bbb8ae695e1d29cf4f3fee/iscan-plugin-cx4400-2.1.3-1.i386.rpm")
md5sums=('2925b88a5db05317c1c2d606ea997515')
install="iscan-plugin-cx4400.install"

build() {
  cd "$srcdir"
  mv usr "${pkgdir}"
}
