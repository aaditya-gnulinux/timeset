# Maintainer: aaditya  aaditya_gnulinux@zoho.com

pkgname=timeset
pkgver=1.3
pkgrel=1
pkgdesc="A script for managing system date and time."
url="http://git.manjaro.org/aadityabagga/timeset/"
arch=('any')
license=('GPL')
depends=('bash' 'sudo')
optdepends=('ntp')
source=("http://git.manjaro.org/aadityabagga/timeset/repository/archive")
sha1sums=('SKIP')

package() {
  cd "${srcdir}"
  install -Dm755 "${pkgname}" "${pkgdir}/usr/bin/${pkgname}"
}

# vim:set ts=2 sw=2 et:

