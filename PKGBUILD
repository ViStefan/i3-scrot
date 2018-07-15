# Maintainer: Bernhard Landauer <oberon@manjaro.org>
# Contributor: Foivos <gitlab.manjaro.org/zakkak>

pkgname=i3-scrot
pkgver=2.1
pkgrel=1
pkgdesc="simple screenshot script using scrot"
arch=('any')
url="https://classicforum.manjaro.org/index.php?topic=31977.msg261964#msg261964"
license=('GPL')
depends=('libnotify'
	'scrot'
	'xdg-user-dirs')
source=('i3-scrot')
md5sums=('38d327f007f6cbd9113fa02ca516e532')

package() {
  install -Dm755 "$srcdir/$pkgname" "$pkgdir/usr/bin/$pkgname"
}
