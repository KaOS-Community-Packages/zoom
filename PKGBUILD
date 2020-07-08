pkgname=zoom
pkgver=5.1.422789.0705
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
sha512sums=('27bdde9d6abedbf2d725a292bc904cbc2c65240c71a1a8128cf5cd566afe63aeb0905a908d4c727120dc8a97ee6acbed129391ddd31adaecaf6207f0c0e0d30c')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
