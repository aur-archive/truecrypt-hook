# Contributor: jim945 [at] mail . r [u]
pkgname=truecrypt-hook
pkgver=4.1
pkgrel=1
pkgdesc="Extensive hook for operations on a truecrypt encrypted root device"
url="http://www.truecrypt.org"
arch=(any)
license=('GPL')
install=${pkgname}.install
depends=(mkinitcpio truecrypt)
source=(truecrypt_hook truecrypt_install)

package() {
    install -o root -g root -D ${srcdir}/truecrypt_hook ${pkgdir}/usr/lib/initcpio/hooks/truecrypt
    install -o root -g root -D ${srcdir}/truecrypt_install ${pkgdir}/usr/lib/initcpio/install/truecrypt
}

sha512sums=('d15bcdb8a12b8ea7d41427512aeaae99e59eba9eac584a02d1a29d114cf4b56d293afbc4e30cce1b0b198bbab46b64123fbb4b971400f5d40a9bc9b9b139d5f2'
            'b4a03b22b4c0175a3b7e1d7d9364d859c5c108e7c2b9dffae4de057b53b7bd55ef4f72782e8e0e161ee8d44935392f1b1d2782d8833bc3af374d9612594e296d')
