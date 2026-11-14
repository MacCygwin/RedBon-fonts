pkgname=redbon-font
pkgver=2026.09.15
pkgrel=1
pkgdesc="Fetches the fonts necessary for Redbon Desktop"
arch=('any')
license=('GPL-3.0-or-later')
depends=('fontconfig' 'ttf-fira-code' 'inter-font' 'ttf-nunito' 'ttf-material-symbols-variable' 'ttf-nerd-fonts-symbols' 'noto-fonts-emoji')
options=('!strip')

package() {
  # Install global Fontconfig configuration
  install -Dm644 "${startdir}/99-redbon-fonts.conf" \
    "${pkgdir}/etc/fontconfig/conf.d/99-redbon-fonts.conf"
}
