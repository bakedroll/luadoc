begin_project(luadocTest EXECUTABLE OPTIONAL)

require_library(Qt6 MODULES Core)
require_library(GTest)
require_library(Lua)
require_library(LuaBridge)

require_project(luadoc)

add_source_directory(test)
