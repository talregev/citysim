file(GLOB files "*.glsl")

install(FILES ${files} DESTINATION ${CMAKE_INSTALL_PREFIX}/share/citysim-${CITYSIM_MAJOR_VERSION}/media/materials/programs)

install(FILES ${files} 
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/citysim-${CITYSIM_MAJOR_VERSION}/media/materials/programs
  )
