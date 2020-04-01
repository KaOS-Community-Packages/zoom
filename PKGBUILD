pkgname=zoom
pkgver=3.5.374815.0324
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
sha512sums=('e6065e20dfdf1bac97dcb9e6570ae6612cae796220466bca4711fe96e7b33420b62ed9dd66e3821f753be2fb25e0992c53c640930b9ad09161fc3a206c11c5e8')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
