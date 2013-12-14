# Maintainer: Hiroaki Yamamoto <admin at sign hysoftware.net>
pkgname='vpp-highlightling-kate'
pkgver=1.0.1
pkgrel=1
pkgdesc='Kate Syntax Highlighting File for VDM++ (Vienna Development Method)'
url='http://hysoftware.net'
arch=('x86_64')
license=('GPL')
depends=('kdebase-katepart')
source=('vpp.xml')

package(){
    KDE_PREFIX="$(kde4-config --prefix)"
    install -d "${pkgdir}${KDE_PREFIX}/share/apps/katepart/syntax"
    install -Dm644 'vpp.xml' "${pkgdir}${KDE_PREFIX}/share/apps/katepart/syntax/"
}
sha256sums=('c19ba74ca76c935aabeaf6507bb28bcab48ff39c6f155eea7e8cf1c339d9eb97')
