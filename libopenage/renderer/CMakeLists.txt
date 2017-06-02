add_sources(libopenage
  tests.cpp
  texture.cpp
  window.cpp
  text.cpp
  color.cpp
  geometry.cpp
  vertex_buffer.cpp
  buffer.cpp
  vertex_state.cpp
  renderer.h
  game_renderer.cpp
  terrain_renderer.cpp
  camera.cpp
)

pxdgen(
	tests.h
)

add_subdirectory(font/)
add_subdirectory(opengl/)
add_subdirectory(resources/)
#add_subdirectory(shaders/)
