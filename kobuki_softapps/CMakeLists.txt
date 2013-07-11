cmake_minimum_required(VERSION 2.8.3)
project(kobuki_softapps)

find_package(catkin REQUIRED)

catkin_package()


install(DIRECTORY param 
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)


install(DIRECTORY launch
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)


install(DIRECTORY rviz
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

