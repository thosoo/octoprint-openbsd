COMMENT = Python API library to monitor file system events

MODPY_EGG_VERSION = 2.1.6
DISTNAME = 			watchdog-${MODPY_EGG_VERSION}
PKGNAME =			py-${DISTNAME}
REVISION =			0

CATEGORIES =		devel
HOMEPAGE =			https://github.com/gorakhargosh/watchdog

MAINTAINER =		Thaison Nguyen <thieson08@me.com>

# Apache2
PERMIT_PACKAGE =	Yes

MODULES =			lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =			Yes
MODPY_PYTEST =		Yes

RUN_DEPENDS =		textproc/py-yaml${MODPY_FLAVOR}
TEST_DEPENDS =		devel/py-pytest${MODPY_FLAVOR} \
			devel/py-flaky${MODPY_FLAVOR}
					

FLAVORS =			python3
FLAVOR =			python3

.include <bsd.port.mk>
