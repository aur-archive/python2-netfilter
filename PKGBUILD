# Maintainer: Joseph Hall <perlhoser«at»gmail.com> 
# Contributor: Joseph Hall <perlhoser«at»gmail.com> 
pkgname=python2-netfilter
pkgver=0.5.9
pkgrel=2
pkgdesc="python2-netfilter is a set of modules for the Python programming language which allows you to manipulate netfilter rules."
arch=('i686' 'x86_64')
url="http://opensource.bolloretelecom.eu/projects/python-netfilter/"
license=('GPLv3')
depends=('python2')
source=(http://opensource.bolloretelecom.eu/files/python-netfilter-$pkgver.tar.gz)
md5sums=('037e557f9288beee76db4ac0ff4d28bc')

build() {
  cd $srcdir/python-netfilter-$pkgver
  python2 setup.py install --root=$pkgdir || return 1
}
