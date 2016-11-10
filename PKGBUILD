pkgname=grub-theme-breeze
_pkgname=breeze
pkgver=b969dc5
pkgrel=1
pkgdesc="A minimalistic GRUB theme inspired by Breeze"
url="https://github.com/gustawho/grub2-theme-breeze"
arch=('x86_64')
license=('CCPL:by-sa')
depends=('grub')
install=${pkgname}.install
source=("git+https://github.com/gustawho/grub2-theme-breeze.git")
sha1sums=('SKIP')
 
package() {
   cd "${srcdir}/grub2-theme-breeze/"

   install -dm755 "$pkgdir/usr/share/grub/themes"
   cp -dpr --no-preserve=ownership "${_pkgname}" "${pkgdir}/usr/share/grub/themes"
}
