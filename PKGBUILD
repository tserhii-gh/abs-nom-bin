# Maintainer: Serhii Tsynailo <serhii.tsynailo@gmail.com>
#
# shellcheck disable=all
pkgname=nom-bin
pkgver=2.0.5
pkgrel=1
pkgdesc="RSS reader for the terminal"
arch=(x86_64)
url="https://github.com/guyfedwards/nom"
license=('GPL')
source=('https://github.com/guyfedwards/nom/releases/download/v2.0.5/nom_2.0.5_linux_amd64.tar.gz')
sha256sums=('f48e0151ccdb2074e15fc6f9fccc601e0c2d73a7b809c4590d8168981c36f4b0')

package() {
	cd "$srcdir/"
	install -Dm0755 -t "$pkgdir/usr/local/bin" "nom"
}
