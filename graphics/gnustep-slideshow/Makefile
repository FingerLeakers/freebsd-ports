# $FreeBSD$

PORTNAME=	slideshow
PORTVERSION=	0.3.5
PORTREVISION=	7
CATEGORIES=	graphics gnustep
MASTER_SITES=	http://download.gna.org/gsimageapps/
PKGNAMEPREFIX=	gnustep-
DISTNAME=	SlideShow-${PORTVERSION}

MAINTAINER=	theraven@FreeBSD.org
COMMENT=	SlideShow Viewer

LICENSE=	GPLv2

DEPRECATED=	depends on expiring graphics/gnustep-slideshowkit
EXPIRATION_DATE=	2018-08-15

USES=		tar:bzip2 gnustep
USE_GNUSTEP=	back build
LIB_DEPENDS=	libSlideShow.so:graphics/gnustep-slideshowkit

OBJCFLAGS+=	-Dsel_eq=sel_isEqual

.include <bsd.port.mk>
