cmake_minimum_required (VERSION 2.8.4)
Project(LuaLibary)

SET(LuaLibary_SRC 
  ../Src/lapi.c 
  ../Src/lcode.c 
  ../Src/lctype.c 
  ../Src/ldebug.c 
  ../Src/ldo.c 
  ../Src/ldump.c 
  ../Src/lfunc.c 
  ../Src/lgc.c 
  ../Src/llex.c 
  ../Src/lmem.c 
  ../Src/lobject.c 
  ../Src/lopcodes.c 
  ../Src/lparser.c 
  ../Src/lstate.c 
  ../Src/lstring.c 
  ../Src/ltable.c 
  ../Src/ltm.c 
  ../Src/lundump.c 
  ../Src/lvm.c 
  ../Src/lzio.c 
  ../Src/lauxlib.c 
  ../Src/lbaselib.c 
  ../Src/lbitlib.c 
  ../Src/lcorolib.c 
  ../Src/ldblib.c 
  ../Src/liolib.c 
  ../Src/lmathlib.c 
  ../Src/loslib.c 
  ../Src/lstrlib.c 
  ../Src/ltablib.c 
  ../Src/lutf8lib.c 
  ../Src/loadlib.c 
  ../Src/linit.c
)

ADD_LIBRARY(LuaLibary ${LuaLibary_SRC})







