# Maintainer: Niels Cautaerts <niels.cautaerts@dataminded.be>

pkgname=datafy-cli
pkgver=1.4.2
pkgrel=1
pkgdesc="The CLI for datafy"
arch=('x86_64')
url="https://www.datafy.cloud/"
license=('unknown')
depends=('docker')
source=("https://datafy-cp-artifacts.s3-eu-west-1.amazonaws.com/cli/1.4.2/datafy_linux_amd64.tar.gz")
sha256sums=("3a0c7d38a4eda0e5fa08498dfbfc0040d10b31d0bf9a27c7eefd0aa352eeeaf2")

package() {
	install -Dm755 bin/linux/amd64/datafy "${pkgdir}/usr/bin/datafy"
}
