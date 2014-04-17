project(pio)

add_executable(pio pio.c)

install(TARGETS pio RUNTIME DESTINATION bin)
