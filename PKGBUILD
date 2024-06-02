pkgname="$projectname"
pkgver=4.4
pkgrel=1
pkgdesc="Simple calindare"
arch=("x86_64")
license=('GPL')
source=("")

build() {
    g++ $filename.cpp -o $filename
}

package() {
    install -m 744 $filename $pkgdir
}