pkgname=zukitwo-theme-openbox
pkgver=20140604
pkgrel=1
pkgdesc="Openbox theme that match Zukitwo gtk theme."
arch=(i686 x86_64)
url="http://box-look.org/content/show.php/?content=146154"
license=('Creative Commons by-sa')
depends=('openbox')
source=("http://box-look.org/CONTENT/content-files/146154-Zukitwo-ob-140604.obt")
md5sums=('0d127eedbf058cfb307639acb7aaaa75')

__realname="Zukitwo-ob"
__dstname="Zukitwo"
__obtname="146154-Zukitwo-ob-140604.obt"

build() {
	cd $srcdir
	tar xf $__obtname
}

package() {
	install -d $pkgdir/usr/share/themes/$__dstname
	cp -r $srcdir/$__realname/openbox-3 $pkgdir/usr/share/themes/$__dstname
}
