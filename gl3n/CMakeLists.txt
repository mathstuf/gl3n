add_library(gl3n
    aabb.d
    frustum.d
    interpolate.d
    linalg.d
    math.d
    plane.d
    util.d
    ext/hsv.d
    ext/matrixstack.d)

install(
    TARGETS             gl3n
    ARCHIVE DESTINATION lib
    LIBRARY DESTINATION lib
    RUNTIME DESTINATION bin)
