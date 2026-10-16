cmake_minimum_required(VERSION 3.16)
project(gtk-theme)

# Standard Cutefish naming
install(DIRECTORY Cutefish DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Cutefish-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Cutefish-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Cutefish/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/cutefish)
install(DIRECTORY Cutefish-light/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/cutefish-light)
install(DIRECTORY Cutefish-dark/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/cutefish-dark)

# Aevis OS naming (both capitalized and lowercase)
install(DIRECTORY Cutefish/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/Aevis)
install(DIRECTORY Cutefish-light/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/Aevis-light)
install(DIRECTORY Cutefish-dark/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/Aevis-dark)
install(DIRECTORY Cutefish/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/aevis)
install(DIRECTORY Cutefish-light/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/aevis-light)
install(DIRECTORY Cutefish-dark/ DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes/aevis-dark)
