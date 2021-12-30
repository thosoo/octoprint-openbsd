COMMENT = Client for sentry

MODPY_EGG_VERSION = 		1.4.3
DISTNAME = 			sentry-sdk-${MODPY_EGG_VERSION}
PKGNAME =			py-${DISTNAME}
REVISION =			0

CATEGORIES =		devel
HOMEPAGE =		https://github.com/getsentry/sentry-python

MAINTAINER =		Thaison Nguyen <thieson08@me.com>

# BSD
PERMIT_PACKAGE =	Yes

MODULES =			lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =			Yes
MODPY_PYTEST =		Yes

RUN_DEPENDS =		devel/py-certifi${MODPY_FLAVOR} \
			www/py-urllib3${MODPY_FLAVOR}
					

FLAVORS =			python3
FLAVOR =			python3

.include <bsd.port.mk>
