# Maintainer:  Ahmed Aaish <aaish@parallel.solutions>

pkgname=dhivehi-fonts
pkgver=0.1
pkgrel=1
pkgdesc='Dhivehi Fonts for Arch Linux'
arch=('any')
url="https://github.com/iqzer0/dhivehifonts"
license=('OFL')
source=(
    "${url}/releases/download/${pkgver}/dhivehifonts-v${pkgver}.zip"
)

package() {
    mkdir -p "${pkgdir}/usr/share/fonts/dhivehifonts/"
    cd "${srcdir}"
    install -Dm644 otf/* "${pkgdir}/usr/share/fonts/dhivehifonts/"
    install -Dm644 ttf/* "${pkgdir}/usr/share/fonts/dhivehifonts/"
}

sha256sums=('5388053ae6e0781b0fab53dd3dba8781156f1ab34bde00d0861f1b05019b8fa2')
