set(SOURCES
  test6.cpp
)

add_executable(paltest_vfprintf_test6
  ${SOURCES}
)

add_dependencies(paltest_vfprintf_test6 coreclrpal)

target_link_libraries(paltest_vfprintf_test6
  ${COMMON_TEST_LIBRARIES}
)
