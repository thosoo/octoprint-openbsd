COMMENT = Query metadatdata from sdists / bdists / installed packages

MODPY_EGG_VERSION = 1.8.2
DISTNAME = 			pkginfo-${MODPY_EGG_VERSION}
PKGNAME =			py-${DISTNAME}
REVISION =			0

CATEGORIES =		sysutils
HOMEPAGE =			https://code.launchpad.net/~tseaver/pkginfo/trunk

MAINTAINER =		Thaison Nguyen <thieson08@me.com>

# MIT
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =		Yes
MODPY_PYTEST =		Yes

TEST_DEPENDS=		devel/py-nose${MODPY_FLAVOR} \
			devel/py-coverage${MODPY_FLAVOR}					
					

FLAVORS =			python3
FLAVOR =			python3

.include <bsd.port.mk>
