pkgname=zoom
pkgver=5.0.408598.0517
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
sha512sums=('5fee6a73e84cef1dfc8f6f7f212c698c701763fbc42681a163ba7dd4e9b0684a950b2236ebd793e19989a82cbd26bb61a647912836489112f19ae4219419e815')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
