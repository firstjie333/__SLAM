# cmake_minimum_required(VERSION 2.6)
# project(cerestutorials1)

# set( CMAKE_BUILD_TYPE "Release" )
# set( CMAKE_CXX_FLAGS "-std=c++11 -O3" )

# # 添加cmake模块以使用ceres库
# list( APPEND CMAKE_MODULE_PATH ${PROJECT_SOURCE_DIR}/cmake_modules )

# # 寻找Ceres库并添加它的头文件
# find_package( Ceres REQUIRED )
# include_directories( ${CERES_INCLUDE_DIRS} )


# add_executable(cerestutorials1 main.cpp)

# # 与Ceres和OpenCV链接
# target_link_libraries( cerestutorials1 ${CERES_LIBRARIES} )

# install(TARGETS cerestutorials1 RUNTIME DESTINATION bin)

