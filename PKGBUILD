# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Daniel Kuecker <daniel.kuecker@gmail.com>
pkgname=kjvpurebiblesearch
pkgver=2.0.0
pkgrel=1
epoch=
pkgdesc="Study and analyze the Fingerprint of God in the mathematical structure, known as the King James Code, of the King James text of the Holy Bible. Allows instant real-time searches, with an autocompleter droplist to assist with words which come next. Jump to specific words, verses, or chapters by number, and see all possible count statistics of phrases within the text."
arch=(x86_64)
url="http://www.purebiblesearch.com/"
license=('GPL')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://github.com/kuedan/kjvpurebiblesearch/raw/master/kjvpurebiblesearch.tar.gz")
noextract=()
md5sums=(75eb1fef1df9812f6e851e5450dfc2e7) #generate with 'makepkg -g'

package() {
	#cd "$srcdir/$pkgname-$pkgver"

	
	msg "creating path and copying files..."
	mkdir -p /opt/$pkgname
	cp -R raw/opt/kjvpurebiblesearch/* /opt/$pkgname/
	install -Dm 644 raw/usr/share/applications/kjvpurebiblesearch.desktop /usr/share/applications/
	cp -r raw/usr/share/* /usr/share
}
