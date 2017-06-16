# LoadPictureType
Load a picture and specify the type of the returned handle; �hBitmap, hIcon or hCursor.�

Use the regular LoadPicture parameters, see https://autohotkey.com/docs/commands/LoadPicture.htm

The parameter ImageType specifies the type of the returned handle, �IMAGE_BITMAP:=0, IMAGE_ICON:=1, IMAGE_CURSOR:=2�

The load sometimes fails if the �"gdi+"� options is specified.

If getting an icon or cursor handle, specify the background color (RGB) of the bitmap, via the �bkColor� parameter, this color will be transparent.

For cursors, you may specify the hotspot coordinates, via the �xHotspot� and �yHotspot� parameters.