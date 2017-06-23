if(PYTHON3_FOUND)
  set(SOURCES TestSwig.cpp)

  core_add_test_library(python3_test)
endif()
