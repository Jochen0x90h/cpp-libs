# add static lib target
ADD_FREEIMAGE_LIBRARY(png
	HEADERS
		png.h
		pngconf.h
		pnglibconf.h
	FILES
		png.c
		pngerror.c
		pngget.c
		pngmem.c
		pngpread.c
		pngread.c
		pngrio.c
		pngrtran.c
		pngrutil.c
		pngset.c
		pngtrans.c
		pngwio.c
		pngwrite.c
		pngwtran.c
		pngwutil.c
	EXPORT
		png
)
