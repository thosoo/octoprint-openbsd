# $OpenBSD: Makefile.template,v 1.71 2014/07/10 12:33:17 sthen Exp $

COMMENT =		web based 3d printing application

#https://github.com/OctoPrint/OctoPrint/releases
#GH_PROJECT =		OctoPrint
#GH_ACCOUNT =		OctoPrint
#GH_TAGNAME =		1.7.2

#DISTNAME =		${GH_PROJECT:L}-${GH_TAGNAME}

MODPY_EGG_VERSION = 1.7.2
DISTNAME = 			OctoPrint-${MODPY_EGG_VERSION}
PKGNAME =			py-${DISTNAME}
REVISION =			0

CATEGORIES =		print www

HOMEPAGE =			http://octoprint.org/

MAINTAINER =		Aaron Bieber <abieber@openbsd.org>

# AGPLv3
PERMIT_PACKAGE =	Yes

MODULES =			lang/python

MODPY_SETUPTOOLS =	Yes
MODPY_PI =			Yes

BUILD_DEPENDS =				textproc/py-markdown${MODPY_FLAVOR}\
					devel/py-pip${MODPY_FLAVOR}

RUN_DEPENDS =				print/py-octoprint-filecheck${MODPY_FLAVOR} \
					print/py-octoprint-firmwarecheck${MODPY_FLAVOR} \
					print/py-octoprint-pisupport${MODPY_FLAVOR} \
					textproc/py-markdown${MODPY_FLAVOR} \
					textproc/py-MarkupSafe${MODPY_FLAVOR} \
					devel/py-regex${MODPY_FLAVOR} \
					devel/py-wrapt${MODPY_FLAVOR} \
					www/py-flask${MODPY_FLAVOR} \
					www/py-jinja2${MODPY_FLAVOR} \
					www/py-flask-login${MODPY_FLAVOR} \
					devel/py-flask-babel${MODPY_FLAVOR} \
					www/py-flask-assets${MODPY_FLAVOR} \
					www/py-werkzeug${MODPY_FLAVOR} \
					www/py-itsdangerous${MODPY_FLAVOR} \
					www/py-cachelib${MODPY_FLAVOR} \
					textproc/py-yaml${MODPY_FLAVOR} \
					devel/py-serial${MODPY_FLAVOR} \
					net/py-netaddr${MODPY_FLAVOR} \
					devel/py-watchdog${MODPY_FLAVOR} \
					devel/py-sarge${MODPY_FLAVOR} \
					net/py-netifaces${MODPY_FLAVOR} \
					devel/py-pylru${MODPY_FLAVOR} \
					sysutils/py-pkginfo${MODPY_FLAVOR} \
					www/py-requests${MODPY_FLAVOR} \
					devel/py-semantic-version${MODPY_FLAVOR} \
					sysutils/py-psutil${MODPY_FLAVOR} \
					devel/py-click${MODPY_FLAVOR} \
					devel/py-future${MODPY_FLAVOR} \
					net/py-websocket-client${MODPY_FLAVOR} \
					textproc/py-emoji${MODPY_FLAVOR} \
					devel/py-sentry-sdk${MODPY_FLAVOR} \
					devel/py-filetype${MODPY_FLAVOR} \
					www/py-zipstream-new${MODPY_FLAVOR} \
					devel/py-blinker${MODPY_FLAVOR} \
					textproc/py-feedparser${MODPY_FLAVOR} \
					www/py-tornado${MODPY_FLAVOR} \
					net/py-zeroconf${MODPY_FLAVOR} \
					devel/py-immutabledict${MODPY_FLAVOR}\
					devel/py-pathvalidate${MODPY_FLAVOR}\
					devel/py-colorlog${MODPY_FLAVOR} \
					textproc/py-unidecode${MODPY_FLAVOR}
			
			
FLAVORS =			python3
FLAVOR =			python3
			
#			www/py-tornado \
#			www/py-sockjs-tornado \
#			devel/py-pylru \
#			devel/py-sarge \
#			textproc/py-yaml \
#			sysutils/py-watchdog \
#			www/py-requests \
#			www/py-flask \
#			www/py-flask-assets \
#			www/py-flask-babel \
#			www/py-flask-login \
#			www/py-flask-principal \
#			devel/py-semantic_version \
#			www/py-flask-assets \
#			www/py-flask-babel \
#			www/py-awesome-slugify \
#			security/py-rsa \
#			devel/py-serial \
#			net/py-netaddr \
#			net/py-netifaces \
#			www/py-requests \
#			sysutils/py-pkginfo \
#			www/py-webassets \
#			sysutils/py-psutil

.include <bsd.port.mk>
