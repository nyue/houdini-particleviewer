CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

PROJECT ( ParticleViewer )

FIND_PACKAGE ( HDK REQUIRED )
FIND_PACKAGE ( OpenGL REQUIRED )

HDK_ADD_LIBRARY ( particleviewer
  src/DisplayObject.cc
  src/GR_particleviewer.cc
  src/plugin.cc
  src/Renderer.cc
  )
