cmake_minimum_required(VERSION 2.8.3)

###########
## Build ##
###########

## Declare a cpp executable
add_executable(displayIpAddress DisplayIpAddress.cpp)

## Specify libraries to link a library or executable target against
target_link_libraries(displayIpAddress stdc++)

#############
## Install ##
#############

## Mark executables and/or libraries for installation
install(TARGETS displayIpAddress
  RUNTIME DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)

