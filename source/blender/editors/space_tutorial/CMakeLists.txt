set(INC
	../include
	../../blenkernel
	../../blenlib
	../../gpu
	../../makesdna
	../../makesrna
	../../windowmanager
	../../../../intern/guardedalloc
	../../../../intern/glew-mx
)
 
set(INC_SYS
	${GLEW_INCLUDE_PATH}
)
 
set(SRC
	space_tutorial.c
)
 
blender_add_lib(bf_editor_space_tutorial "${SRC}" "${INC}" "${INC_SYS}")