#Specify the version being used aswell as the language
cmake_minimum_required(VERSION 3.11.1)
#Name your project here
project(Helloworld)

#export "CC=C:\TDM-GCC-32\bin\gcc"
#Sends the -std=c99 flag to the gcc compiler
#add_definitions(-std=c99)
#This tells CMake to fib.c and name it fibonacci
add_executable(Helloworld hello.c)