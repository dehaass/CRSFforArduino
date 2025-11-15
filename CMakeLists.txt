file(GLOB_RECURSE ARDUINOCRSF_SRCS "src/*.cpp")

idf_component_register(
    SRCS ${ARDUINOCRSF_SRCS}
    INCLUDE_DIRS "src"
    REQUIRES arduino
)
