install(FILES colors metadata.desktop DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/damadamas/)

FILE(GLOB widgets widgets/*.svgz)
install( FILES ${widgets} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/damadamas/widgets/ )

FILE(GLOB dialogs dialogs/*.svgz)
install( FILES ${dialogs} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/damadamas/dialogs/ )

FILE(GLOB icons icons/*.svgz)
install( FILES ${icons} DESTINATION ${PLASMA_DATA_INSTALL_DIR}/desktoptheme/damadamas/icons/ )
