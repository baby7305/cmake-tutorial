SET(SRC_LIST hello.c)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/exe)

INCLUDE_DIRECTORIES(F:\\cmake-code\\libhello\\include\\hello)
LINK_DIRECTORIES("F:\\cmake-code\\libhello\\lib")

add_executable(hello ${SRC_LIST})

TARGET_LINK_LIBRARIES(hello libhello.a)