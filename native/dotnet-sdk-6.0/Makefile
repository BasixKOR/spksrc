PKG_NAME = dotnet-sdk-6.0
# Version 6.0.36, SDK 6.0.428 (final version, EOL since November 12, 2024)
# https://dotnet.microsoft.com/download/dotnet/6.0
PKG_VERS = 6.0.428
PKG_EXT = tar.gz
PKG_DIST_NAME = dotnet-sdk-$(PKG_VERS)-linux-x64.$(PKG_EXT)
PKG_DIST_SITE = https://builds.dotnet.microsoft.com/dotnet/Sdk/${PKG_VERS}

HOMEPAGE = https://dotnet.microsoft.com/
COMMENT  = A developer platform for building apps.
LICENSE  = MIT

# just extract and create folder for nuget packages
INSTALL_TARGET = dotnet_native_install

NUGET_PACKAGES_DIR = $(DISTRIB_DIR)/nuget/packages

include ../../mk/spksrc.native-install.mk

.PHONY: dotnet_native_install
dotnet_native_install:
	mkdir -p $(NUGET_PACKAGES_DIR)
