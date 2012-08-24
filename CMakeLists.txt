# Copyright (C) 2007-2012 LuaDist.
# Created by Peter Drahoš
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

project ( sputnik NONE )
cmake_minimum_required ( VERSION 2.8 )
include ( cmake/dist.cmake )
include ( lua )

install ( DIRECTORY lua/sputnik DESTINATION ${INSTALL_LMOD} COMPONENT Runtime )
install_lua_executable ( sputnik bin/sputnik.lua )
install_data (LICENSE.txt LICENSE_CRYSTAL_ICONS.txt LICENSE_JQUERY.txt LICENSE_YUI.txt )
