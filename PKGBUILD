pkgname=zoom
pkgver=3.5.385850.0413
pkgrel=1
pkgdesc="Video Conferencing and Web Conferencing Service"
arch=('x86_64')
license=('custom')
url="https://zoom.us/"
depends=('fontconfig' 'glib2' 'pulseaudio' 'libsm' 'libx11' 'libxcb' 'libxcomposite' 'libxfixes' 'libxi'
 'libxrandr' 'libxrender' 'libxshmfence' 'libxslt' 'mesa' 'nss' 'pulseaudio-alsa' 'xcb-util-image' 'xcb-util-keysyms'
 'qt5-svg' 'qtwebengine' 'qt5-quickcontrols2')
options=(!strip)
source=("${pkgname}-${pkgver}_orig_x86_64.pkg.tar.xz"::"https://zoom.us/client/${pkgver}/zoom_x86_64.pkg.tar.xz")
sha512sums=('6ecc53a1662ae5c6fd3b2b44f16a43c355f81d17635bbe97fdf60496fa45da6f050563df561035f810ebc7bafc3114449c2bbf4d9debe58c29855c7543db1eaf')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
