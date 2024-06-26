project(resources-galaxy)

install(DIRECTORY
		data
	DESTINATION
		bin
	COMPONENT
		${RUNTIME_COMPONENT}
)