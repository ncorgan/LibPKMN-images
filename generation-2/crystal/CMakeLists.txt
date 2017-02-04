#
# Copyright (c) 2013 Nicholas Corgan (n.corgan@gmail.com)
#
# Distributed under the MIT License (MIT) (See accompanying file LICENSE.txt
# or copy at http://opensource.org/licenses/MIT)
#
FILE(GLOB images RELATIVE ${CMAKE_CURRENT_SOURCE_DIR} "*.png")
INSTALL(FILES ${images} DESTINATION ${IMAGES_DIR}/generation-2/crystal COMPONENT Images)

ADD_SUBDIRECTORY(shiny)
