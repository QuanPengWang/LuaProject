cmake_minimum_required (VERSION 2.8.4)
Project(LuaInterpreter)

include_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}/../Src
)

link_directories(
  ${CMAKE_CURRENT_SOURCE_DIR}/../bin
  )

set(LuaInterpreter_SRC 
  ../Src/lua.c
)

ADD_EXECUTABLE(LuaInterpreter ${LuaInterpreter_SRC})

target_link_libraries(LuaInterpreter 
  LuaLibary
)
