cmake_minimum_required(VERSION 3.5)
project(acceleration_firmware NONE)

find_package(ament_cmake REQUIRED)

install(
  FILES
    package.xml
  DESTINATION
    share/${PROJECT_NAME}
)

# kept so that other packages can depend on it
ament_package()
