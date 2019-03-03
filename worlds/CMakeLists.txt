file(GLOB files "*.world")

install(FILES ${files} DESTINATION ${CMAKE_INSTALL_PREFIX}/share/citysim-${CITYSIM_MAJOR_VERSION}/worlds/)

install(FILES ${files} 
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}/worlds
  )
