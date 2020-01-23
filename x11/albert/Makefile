# $FreeBSD$

PORTNAME=	albert
DISTVERSION=	v0.16.1
CATEGORIES=	x11

MAINTAINER=	jsm@freebsd.org
COMMENT=	Albert a desktop launcher

LICENSE=	GPLv3

LIB_DEPENDS=	libmuparser.so:math/muparser \
		libpython3.7m.so:lang/python37

USES=	cmake localbase xorg qt:5

USE_QT=	charts network sql x11extras gui core widgets concurrent dbus \
	declarative svg

USE_XORG=x11 xext sm ice
USE_LDCONFIG=	yes
COMPILER=	c++14-lang
USE_GITHUB=	yes
GH_TUPLE=	albertlauncher:albert:v0.16.1 \
		albertlauncher:plugins:029bd8ccb58c4452bd82ab42be8739f1639e42d4:albert/plugins

.include <bsd.port.mk>
