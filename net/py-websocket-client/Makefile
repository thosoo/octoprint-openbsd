# $OpenBSD: Makefile,v 1.12 2021/09/09 14:37:25 kn Exp $

COMMENT =		WebSocket client for Python

MODPY_EGG_VERSION =	0.59.0
DISTNAME =		websocket-client-${MODPY_EGG_VERSION}
PKGNAME =		py-websocket-client-${MODPY_EGG_VERSION}
REVISION =		0

CATEGORIES =		net

HOMEPAGE =		https://github.com/liris/websocket-client

# LGPLv2.1+
PERMIT_PACKAGE =	Yes

MODPY_PI =		Yes
MODPY_PI_DIR =		w/websocket-client
MODPY_SETUPTOOLS =	Yes

MODULES =		lang/python
FLAVORS =		python3
FLAVOR =		python3

RUN_DEPENDS =		devel/py-six${MODPY_FLAVOR}

.include <bsd.port.mk>
