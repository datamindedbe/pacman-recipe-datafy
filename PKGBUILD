# Maintainer: Niels Cautaerts <niels.cautaerts@dataminded.be>

pkgname=datafy-cli
pkgver=0.59.3
pkgrel=1
pkgdesc="The CLI for datafy"
arch=('x86_64')
url="https://www.datafy.cloud/"
license=('unknown')
depends=('docker')
source=("https://datafy-cp-artifacts.s3-eu-west-1.amazonaws.com/cli/0.59.3/datafy_linux_amd64.tar.gz")
sha256sums=("55efd38aa9fbd5608061da59b11e09f6d5430145b1133b7cd633195c4d4e26b8")

package() {
	install -Dm755 bin/linux/amd64/datafy "${pkgdir}/usr/bin/datafy"
}
