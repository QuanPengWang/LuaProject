cmake_minimum_required (VERSION 2.8.4)
Project(LuaProject)

include_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}/../Src
)

link_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}/../bin
  )

set(LuaCompiler_SRC 
  ../Src/luac.c
)

ADD_EXECUTABLE(Luac ${LuaCompiler_SRC})

target_link_libraries(Luac
  LuaLibary
)







