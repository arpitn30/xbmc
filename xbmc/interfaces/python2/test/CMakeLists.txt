if(PYTHON2_FOUND)
  set(SOURCES TestSwig.cpp)

  core_add_test_library(python2_test)
endif()
