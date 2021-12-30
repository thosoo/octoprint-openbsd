# $OpenBSD: Makefile,v 1.7 2021/05/21 19:50:26 kmos Exp $

COMMENT =	compatibility layer between Python 2 and Python 3

MODPY_EGG_VERSION =	0.18.2
DISTNAME =	future-${MODPY_EGG_VERSION}
PKGNAME =	py-${DISTNAME}
REVISION =	0

CATEGORIES =	devel
HOMEPAGE =	http://python-future.org/

# MIT
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI =		Yes
MODPY_SETUPTOOLS =	Yes

FLAVORS =		python3
FLAVOR =		python3

post-install:
	for i in ${PREFIX}/bin/*; do \
		mv $${i} $${i}${MODPY_BIN_SUFFIX} ;\
	done

.include <bsd.port.mk>
