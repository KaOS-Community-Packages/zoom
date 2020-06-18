pkgname=zoom
pkgver=5.1.412382.0614
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
sha512sums=('c83a5eae76933d2280e3e054654b09743ad138094322562a5198f3f1dd9d8a85bc758fe574a13adc62d162d3268dc5231416f6752ce25792757b8e60b7ae7da0')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
