# Maintainer: Niels Cautaerts <niels.cautaerts@dataminded.be>

pkgname=datafy-cli
pkgver=1.2.0
pkgrel=1
pkgdesc="The CLI for datafy"
arch=('x86_64')
url="https://www.datafy.cloud/"
license=('unknown')
depends=('docker')
source=("https://datafy-cp-artifacts.s3-eu-west-1.amazonaws.com/cli/1.2.0/datafy_linux_amd64.tar.gz")
sha256sums=("05c309bf4a5b2f4accfc0533e120a50398eb0aacbc0e2a540f577fb021ab9190")

package() {
	install -Dm755 bin/linux/amd64/datafy "${pkgdir}/usr/bin/datafy"
}
