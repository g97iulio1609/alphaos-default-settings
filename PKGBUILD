# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=alphaos-default-settings
pkgver=20140908
pkgrel=1
pkgdesc="This provides to Alpha OS UX."
arch=('i686' 'x86_64')
url="https://github.com/g97iulio1609/alphaos-default-settings"
license=('LGPLv2+')
depends=('gnome-shell')
makedepends=('git')
replaces=('gnome-shell')
_repanthalver=0.3.1
provides=('alphaos-default-settings')
source=("git+https://github.com/g97iulio1609/alphaos-default-settings.git")
md5sums=('SKIP')
install=schemas.install

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/glib-2.0/schemas
    cp -R  /home/alpha/pkg/alphaos-default-settings/alphaos-default-settings/10_oneos-default-settings.gschema.override "${pkgdir}"/usr/share/glib-2.0/schemas

}
