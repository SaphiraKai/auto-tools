# Maintainer: Saphira Kai <kai.saphira@gmail.com>
pkgname='auto-tools'
pkgver=1.2
pkgrel=1
epoch=
pkgdesc=''
arch=('any')
url='http://nova.l5.ca'
license=('GPLv3')
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
sha256sums=('9e797f6beb36a9aa3a6ced14252608ca5c81546bd53e9ddba743b7efe29af24b')
validpgpkeys=()

#prepare() {}

#build() {}

#check() {}

package() {
    mkdir -p "$pkgdir/usr/bin/"
    cp 'auto' "$pkgdir/usr/bin"
}
