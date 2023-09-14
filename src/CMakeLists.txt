# Check minimum required cmake version
cmake_minimum_required(VERSION 3.16.0)

# Just project name
project(Cooll)

# Add executable cooll from main.c file
add_executable(cooll main.c)

# Install cooll to bin (/usr/local/bin in mac/linux)
install(TARGETS cooll DESTINATION bin)