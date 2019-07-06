pkgname=jak-social-gab
pkgver=1.0
pkgrel=1
pkgdesc="Gab Free Speech Social Network"
arch=('x86_64')
url="https://gab.com"
license=('GPL')
depends=('jade-application-kit-git')
source=("git+https://github.com/realKennyStrawn93/triggerbox-gab#branch=master")

package() {
  cd $srcdir
  mkdir -p $pkgdir/usr/bin
  mkdir -p $pkgdir/usr/share/applications
  cp $srcdir/$pkgname/gab.desktop $pkgdir/usr/share/applications
  cp $srcdir/$pkgname/gab $pkgdir/usr/bin
  cp $srcdir/$pkgname/gab-wrapper $pkgdir/usr/bin
}
