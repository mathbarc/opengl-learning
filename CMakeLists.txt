project("OpenGL Course")


add_executable(start start.cpp)
target_link_libraries(start glfw GLEW GL)

add_executable(example main.cpp)
target_link_libraries(example glfw GLEW GL)

