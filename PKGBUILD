# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-chelyabinsk
pkgver=58
pkgrel=1
pkgdesc="Map of Chelyabinsk for 2GIS, June 2012"
arch=('i686' 'x86_64')
url="http://chelyabinsk.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.6.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Chelyabinsk-58.orig.zip")
md5sums=('ec5451133aadfefc47dfe94a9626caca')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Chelyabinsk.dgdat "${startdir}/pkg/opt/2gis/chelyabinsk.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Chelyabinsk.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Chelyabinsk.dglf" || return 1
     
}

