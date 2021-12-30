COMMENT = Asset management for Flask

MODPY_EGG_VERSION = 2.0
DISTNAME = Flask-Assets-${MODPY_EGG_VERSION}
PKGNAME =			py-${DISTNAME}
REVISION =			0

CATEGORIES =		www
HOMEPAGE =			https://github.com/miracle2k/flask-assets

MAINTAINER =		Thaison Nguyen <thieson08@me.com>

# BSD2CLAUSE
PERMIT_PACKAGE =	Yes

MODULES =			lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =			Yes
MODPY_PYTEST =		Yes

RUN_DEPENDS =		www/py-flask${MODPY_FLAVOR} \
			www/py-webassets${MODPY_FLAVOR} 
					

FLAVORS =			python3
FLAVOR =			python3

.include <bsd.port.mk>
