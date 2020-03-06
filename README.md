# Images

Testing `EXIF Geolocation Data`

# Title

EXIF Geolocation Data Not Stripped From Uploaded Images

# What is EXIF:-
EXIF is short for Exchangeable Image File, a format that is a standard for storing interchange information in digital photography image files using JPEG compression. Almost all new digital cameras use the EXIF annotation, storing information on the image such as shutter speed, exposure compensation, F number, what metering system was used, if a flash was used, ISO number, date and time the image was taken, white balance, auxiliary lenses that were used and resolution. Some images may even store GPS information so you can easily see where the images were taken!

# Summary:
When a user uploads an image in samsara.com, the uploaded image’s EXIF Geolocation Data does not gets stripped. As a result, anyone can get sensitive information of example.com users like their Geolocation, their Device information like Device Name, Version, Software & Software version used etc.

# POC:-

Upload the below image Logo
https://raw.githubusercontent.com/Mad-robot/Images/master/rsz_dscn0021.jpg

The above image has EXIF data with latitude and logitude

And check the exif data at
http://exif.regex.info/exif.cgi
