# LumiaExtend
PC screen extension app for Lumia Windows Phone devices
# Function
For PC
Use `LumiaExtend_Server_x64_v1.0.0_Release.exe` as the server application to ensure the Lumia WP device functions correctly.
For Lumia WP
Supports extending the PC screen to the Lumia WP device remotely.
Supports remote mouse input.
Supports remote keyboard input.

# Requirements
On PC
Installing `IddSampleDriver` is mandatory for proper operation; set it up as the second (2nd) display.
Download and run `LumiaExtend_Server_x64_v1.0.0_Release.exe` normally; no configuration is required.
On Lumia WP
Download `LumiaExtend_1.0.0_Release.zip`, extract the files, and transfer them to the Lumia WP device.
Install `LumiaExtend_1.0.0_arm.cer` followed by `LumiaExtend_1.0.0_arm.appxbundle`.

# Known Issues
Due to hardware limitations on some older Lumia WP devices, the frame rate may not exceed 30 FPS. The default resolution is 720p.
It only works with the second (2nd) display; it will not function with other displays (e.g., the 1st or 3rd).
If installation on the Lumia WP fails, try restarting the device, then install the components found in the "Dependencies" folder (matching your CPU architecture). Afterward, attempt to install the two main files mentioned above again.
There may be other undiscovered issues; please provide feedback via my Telegram link below.
Development time is very limited; work is mostly done during long holidays.
