# add static lib target
ADD_FREEIMAGE_LIBRARY(OpenJPEG
	FILES
		bio.c
		cio.c
		dwt.c
		event.c
		function_list.c
		image.c
		invert.c
		j2k.c
		jp2.c
		mct.c
		mqc.c
		openjpeg.c
		opj_clock.c
		pi.c
		raw.c
		t1.c
		t2.c
		tcd.c
		tgt.c
	HEADERS
		openjpeg.h
	EXPORT
		FreeImage
)

# set preprocessor definitions
add_definitions(-DOPJ_STATIC)
