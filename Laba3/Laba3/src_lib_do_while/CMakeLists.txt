# CMakeList.txt: ������ CMake ��� Laba3; �������� �������� ��� � �����������,
# ������� ����� ������ ��� ����������� �������.
#
cmake_minimum_required (VERSION 3.8)

# �������� �������� � ����������� ���� ����� �������.
add_library(task3Laba3lib STATIC "func.c")
target_include_directories(task3Laba3lib PUBLIC "../Include")