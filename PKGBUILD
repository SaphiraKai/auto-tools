# Maintainer: Saphira Kai <kai.saphira@gmail.com>
pkgname='auto-tools'
pkgver=r7.648513d
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

pkgver() {
	mkdir -p "$pkgdir/usr/bin/"
	cd "$pkgdir"
	(
		set -o pipefail
		git describe --long 2>/dev/null | sed 's/\([^-]*-g\)/r\1/;s/-/./g' ||
		printf "r%s.%s" "$(git rev-list --count HEAD)" "$(git rev-parse --short HEAD)"
	)
}

#prepare() {}

#build() {}

#check() {}

package() {
    install -Dm 755 'auto' "$pkgdir/usr/bin/auto"
}

