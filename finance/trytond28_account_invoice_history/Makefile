# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD$

PORTNAME=	trytond28_account_invoice_history
PORTVERSION=	2.8.0
PORTREVISION=	2
CATEGORIES=	finance python
MASTER_SITES=	https://pypi.python.org/packages/source/t/trytond_account_invoice_history/ \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_account_invoice_history-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Account Invoice History Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_account_invoice>=2.8.2:finance/trytond28_account_invoice

CONFLICTS=	trytond_account_invoice_history-2.[46].*

USES=		python:2.7
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
