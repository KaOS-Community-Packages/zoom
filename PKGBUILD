pkgname=zoom
pkgver=5.6.13632.0328
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
sha512sums=('cf79705f0cfecda89fcca48e78aeb5a796ab00b880f6d1934f25085e1f30f406a2087950a6288177d4bfe8f6ede2f7334615210f460afedb20d1600bf97cb681')

package() {
 cp -dpr --no-preserve=ownership opt usr "${pkgdir}"
}
