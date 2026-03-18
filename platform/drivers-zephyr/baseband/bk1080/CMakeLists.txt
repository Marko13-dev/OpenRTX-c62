
if(CONFIG_BK1080)
  zephyr_library()
  zephyr_library_sources(bk1080.c)
  zephyr_library_sources(bk1080.h)
  zephyr_library_include_directories(.)
endif()