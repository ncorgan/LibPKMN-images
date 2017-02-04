#
# Copyright (c) 2017 Nicholas Corgan (n.corgan@gmail.com)
#
# Distributed under the MIT License (MIT) (See accompanying file LICENSE.txt
# or copy at http://opensource.org/licenses/MIT)
#
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)

IF(${CMAKE_SOURCE_DIR} STREQUAL ${CMAKE_CURRENT_SOURCE_DIR})
    MESSAGE(FATAL_ERROR "This repository is not meant to be used stand-alone.")
ENDIF(${CMAKE_SOURCE_DIR} STREQUAL ${CMAKE_CURRENT_SOURCE_DIR})

SET(IMAGES_DIR "share/pkmn/images")

ADD_SUBDIRECTORY(generation-1)
ADD_SUBDIRECTORY(generation-2)
ADD_SUBDIRECTORY(generation-3)
ADD_SUBDIRECTORY(generation-4)
ADD_SUBDIRECTORY(generation-5)
ADD_SUBDIRECTORY(misc)
ADD_SUBDIRECTORY(pokemon-icons)
