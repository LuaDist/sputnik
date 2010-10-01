# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(sputnik NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
INCLUDE(dist.cmake)

INSTALL (DIRECTORY lua/sputnik DESTINATION ${INSTALL_LMOD})
INSTALL (PROGRAMS bin/sputnik.lua DESTINATION ${INSTALL_BIN})
INSTALL (FILES LICENSE.txt LICENSE_CRYSTAL_ICONS.txt LICENSE_JQUERY.txt LICENSE_YUI.txt DESTINATION ${INSTALL_DATA})
