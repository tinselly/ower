
# CMakeLists.txt

cmake_minimum_required ( VERSION 3.17.0 )

set ( CMAKE_CXX_STANDARD 17 )
set ( CMAKE_CXX_STANDARD_REQUIRED ON )
set ( CMAKE_CXX_EXTENSIONS OFF )

set ( OWER_INCLUDE_DIR "${CMAKE_SOURCE_DIR}/include" )

project (
  ower

    VERSION
      0.0.0

    DESCRIPTION
      ""

    HOMEPAGE_URL
      "https://github.com/tinselly/ower"

    LANGUAGES
      CXX
)


add_subdirectory ( src )
