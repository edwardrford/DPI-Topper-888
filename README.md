# DPI Topper 888
 
## Software
### Add the following code to config.txt:
```
#Set GPIO pins to 24-Bit DPI Mode
gpio=0-1=a2,np
gpio=4-27=a2,np
#Set remaining GPIO pins to I2C Mode
gpio=2-3=a0,np
#Configure DPI signaling
framebuffer_width=800
framebuffer_height=480
enable_dpi_lcd=1
display_default_lcd=1
dpi_group=2
dpi_mode=87
dpi_output_format=503847
dpi_timings=800 0 40 48 88 480 0 13 3 32 0 0 0 60 0 32000000
```
