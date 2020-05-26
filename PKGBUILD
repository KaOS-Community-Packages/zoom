pkgname=zoom
pkgver=5.0.413237.0524
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
sha512sums=('406bb2debfc70cc9e5b0cc2b1892d0a31a89e1f9bbea057fa6ca9a3c0a8539e59ff0c4738caa04645d219ed581251d0d609a419d6377681be3e9ad6d0aaa9cd0')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
