# http://ros.org/doc/groovy/api/catkin/html/user_guide/supposed.html
cmake_minimum_required(VERSION 3.5)
project(robotiq_3f_gripper_visualization)
find_package(ament_cmake REQUIRED)
find_package(urdf REQUIRED)

install(
  DIRECTORY cfg meshes launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
