#
# MACHINE GENERATED FILE. DO NOT EDIT.
#
# CMake build file for lub
#
# This file has been generated by lut.Builder 1.2.1
#

cmake_minimum_required(VERSION 2.8)
# --------------------------------------------------------------
#  lub
# --------------------------------------------------------------
set(MODULE_NAME lub)

# Where to install Lua files
if(LUA_INSTALL_DIR)
  set(INSTALL_PATH ${LUA_INSTALL_DIR})
else(LUA_INSTALL_DIR)
  set(INSTALL_PATH "${CMAKE_BINARY_DIR}/lib" CACHE STRING "Install directory path")
endif(LUA_INSTALL_DIR)
message("INSTALL Lua    'lub' TO '${INSTALL_PATH}'")


# --------------------------------------------------------------
#  module
# --------------------------------------------------------------
add_custom_target(${MODULE_NAME} true)

# --------------------------------------------------------------
#  install                                     
# --------------------------------------------------------------
install(DIRECTORY ${MODULE_NAME}
  DESTINATION ${INSTALL_PATH}
)


