pkgname=zoom
pkgver=5.11.0.3540
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
md5sums=('7e3d06d0837698718f037d189f292c75')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
