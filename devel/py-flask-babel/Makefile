COMMENT = Adds i18n/l10n support to Flask Applications

MODPY_EGG_VERSION = 2.0.0
DISTNAME = 		Flask-Babel-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME}
REVISION =		0

CATEGORIES =		devel
HOMEPAGE =  		https://github.com/python-babel/flask-babel

MAINTAINER =		Thaison Nguyen <thieson08@me.com>

# BSD3
PERMIT_PACKAGE =	Yes

MODULES =			lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =			Yes
MODPY_PYTEST =		Yes

RUN_DEPENDS =		devel/py-tz${MODPY_FLAVOR} \
			www/py-flask${MODPY_FLAVOR} \
			devel/py-babel${MODPY_FLAVOR} \
			www/py-jinja2${MODPY_FLAVOR}

FLAVORS =			python3
FLAVOR =			python3

.include <bsd.port.mk>
