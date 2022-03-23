# Get-device-screen-size
Get device screen size
Display display = ((WindowManager) getSystemService(WINDOW_SERVICE)).getDefaultDisplay(); 
int width = display.getWidth(); 
int height = display.getHeight(); 
int ori = display.getOrientation();
