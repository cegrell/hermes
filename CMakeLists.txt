# CMakeList.txt : CMake project for trading-manager, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("trading-manager")

#find_package()

include_directories("include")

# Add source to this project's executable.
add_executable (trading-manager "trading-manager.cpp" "trading-manager.h" "src/order_book.cpp")

# TODO: Add tests and install targets if needed.
