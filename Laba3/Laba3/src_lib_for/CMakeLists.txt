# CMakeList.txt: ������ CMake ��� Laba3; �������� �������� ��� � �����������,
# ������� ����� ������ ��� ����������� �������.
#
cmake_minimum_required (VERSION 3.8)

# �������� �������� � ����������� ���� ����� �������.
add_library(task1Laba3lib STATIC "func.c")
target_include_directories(task1Laba3lib PUBLIC "../Include")