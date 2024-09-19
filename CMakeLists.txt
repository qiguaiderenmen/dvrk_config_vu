cmake_minimum_required (VERSION 3.10)
project (dvrk_config_vu VERSION 2.3.0)

find_package (ament_cmake QUIET)
if (ament_cmake_FOUND)
  ament_package ()
endif ()

install (
  DIRECTORY vu-dVRK
  DESTINATION share
  )
