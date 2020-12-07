# Maintainer: Sven-Hendrik Haase <sh@lutzhaase.com>
# Contributor: Alexander Monakov <amonakov@gmail.com>

pkgname=primus
pkgver=20201207
pkgrel=1
pkgdesc="Compat wrapper around NVIDIA GLVND drivers"
arch=('any')
url="https://github.com/amonakov/primus"
license=('custom:ISC')
depends=('bash' 'nvidia-utils>=435.17' 'xorg-server>=1.20.6')
source=("primusrun" "primusrun.1")
sha1sums=('fe45885230959a147ef7d637bd01be445ee23f39'
          'aabed52ab6366fbb7cc91fe21818910709c00e84')

package() {
  install -D primusrun "$pkgdir/usr/bin/primusrun"
  install -D primusrun.1 "$pkgdir/usr/share/man/man1/primusrun.1"
}
