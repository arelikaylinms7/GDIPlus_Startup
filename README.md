# GDIPlus_Startup
$hGui = GUICreate(StringTrimRight(@ScriptName, 4), $iWidth, $iHeight, 0, 0) EnvSet("SDL_WINDOWID", $hGui) _SDL_Init($_SDL_INIT_VIDEO) _GDIPlus_Startup() $hScreenSurface = _SDL_SetVideoMode($iWidth, $iHeight, 32, $_SDL_SWSURFACE)
