project(resources-galaxy)
set(INSTALL_PATH "." CACHE STRING "destination directory for the resources")
install(DIRECTORY
		data
	DESTINATION
		${INSTALL_PATH}
	COMPONENT
		${RUNTIME_COMPONENT}
)