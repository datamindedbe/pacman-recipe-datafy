# Maintainer: Niels Cautaerts <niels.cautaerts@dataminded.be>

pkgname=datafy-cli
pkgver=1.1.3
pkgrel=1
pkgdesc="The CLI for datafy"
arch=('x86_64')
url="https://www.datafy.cloud/"
license=('unknown')
depends=('docker')
source=("https://datafy-cp-artifacts.s3-eu-west-1.amazonaws.com/cli/1.1.3/datafy_linux_amd64.tar.gz")
sha256sums=("ec3cdf75914ca296a4f9824235ea442836ae1c972aa09c9c69e18353abe2c7c3")

package() {
	install -Dm755 bin/linux/amd64/datafy "${pkgdir}/usr/bin/datafy"
}
