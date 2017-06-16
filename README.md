# LoadPictureType
Load a picture and specify the type of the returned handle; hBitmap, hIcon or hCursor.

Use the regular LoadPicture parameters, see https://autohotkey.com/docs/commands/LoadPicture.htm

The load sometimes fails if the "gdi+" options is specified.

If getting a icon or cursor handle, specify the background color of the bitmap, this color will be transparent.