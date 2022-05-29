begin_project(luadoc LIBRARY)

enable_autorcc()

require_library(Qt MODULES Core)
require_library(Lua)
require_library(LuaBridge)

add_source_directory(src)
add_source_directory(include)

add_qrc_files(luadoc_resources.qrc)

add_include_directory(include)
