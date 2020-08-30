pkgname=ezzram
depends=("python-psutil")
provides=("$pkgname")
pkgver=1
pkgrel=1
arch=("x86_64")

source=('git://github.com/jturnerusa/ezzram.git')

package()
{
	install -Dm755 "$srcdir/$pkgname.py" "$pkgdir/usr/bin/$pkgname"
	install -Dm644 "$srcdir/$pkgname.service" "$pkgdir/usr/lib/systemd/system/$pkgname.service"
	install -Dm644 "$srcdir/$pkgname.conf" "$pkgdir/etc/$pkgname.conf"
}
