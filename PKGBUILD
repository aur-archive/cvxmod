# Contributor: Dmitriy Morozov <archlinux@foxcub.org> 
pkgname=cvxmod
pkgver=0.4.6
pkgrel=1 
pkgdesc="Convex optimization modelling in Python"
url="http://cvxmod.net"
arch=('i686' 'x86_64')
license="GPL" 
depends=('python2' 'cvxopt')
source=(http://cvxmod.net/dist/$pkgname-$pkgver.tar.gz)

build() { 
 cd $startdir/src/$pkgname-$pkgver
 python2 setup.py install --root=$startdir/pkg
}
md5sums=('e5d859659853809e5c7fc2e2970be88e')
