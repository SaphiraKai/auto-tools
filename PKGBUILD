# Maintainer: Saphira Kai <kai.saphira@gmail.com>
pkgname='auto-tools'
pkgver=1.2
pkgrel=1
epoch=
pkgdesc='an all-in-one collection of useful automated tools for developers'
arch=('any')
url='http://nova.ro.lt'
license=('GPLv2')
groups=()
depends=(bash)
makedepends=()
checkdepends=()
optdepends=('make: using makefiles'
            'gcc: compiling with gcc'
            'cargo: managing rust projects')
provides=(auto)
conflicts=(auto)
replaces=()
backup=()
options=()
install=
changelog=
source=('auto')
noextract=()
sha256sums=('SKIP')
validpgpkeys=('2916041854F0C0C2786846345B407F5B67CAAA85')

#prepare() {}

#build() {}

#check() {}

package() {
    mkdir -p "$pkgdir/usr/bin/"
    cp 'auto' "$pkgdir/usr/bin"
}
