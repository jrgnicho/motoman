cmake_minimum_required(VERSION 3.5)

project(motoman_mh50_support)

find_package(ament_cmake REQUIRED)


#############
## Install ##
#############
install(DIRECTORY
  launch
  meshes
  urdf
  config
  DESTINATION share/${PROJECT_NAME}/
)

ament_package()

