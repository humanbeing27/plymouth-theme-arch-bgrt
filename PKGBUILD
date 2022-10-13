pkgname=plymouth-theme-arch-spinner
pkgver=1
pkgdesc="A theme that showcases a simple spinner and Arch logo"
arch=(any)
url="https://github.com/humanbeing27/plymouth-theme-arch-spinner"
depends=(plymouth)
source=($url/archive/refs/heads/main.zip)
sha512sums=("SKIP")
package() {
mv $srcdir/$pkgname/usr $pkgdir
chown -R root $pkgdir/*
chgrp -R root $pkgdir/*
}
