# Maintainer: Niels Cautaerts <niels.cautaerts@dataminded.be>

pkgname=datafy-cli
pkgver=1.1.0
pkgrel=1
pkgdesc="The CLI for datafy"
arch=('x86_64')
url="https://www.datafy.cloud/"
license=('unknown')
depends=('docker')
source=("https://datafy-cp-artifacts.s3-eu-west-1.amazonaws.com/cli/1.1.0/datafy_linux_amd64.tar.gz")
sha256sums=("c862c9694f407a9fc80d1fc938c7000eff883c6be836a789284b437bd5507060")

package() {
	install -Dm755 bin/linux/amd64/datafy "${pkgdir}/usr/bin/datafy"
}
