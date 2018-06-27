## xfce4-appfinder

#### To add websearch script as "Custom Action" in xfce4-appfinder:

Add a new entry, and set options as follows:

(all without the double quotes)

Type:	"Prefix"

Pattern:	"google"

Command: "websearch 'google.web' %s"

Now close the windows

#### To test it:
Hit your keyboard-shortcut for xfce4-appfinder

(default: alt+F2)

Write: "google the eiffel tower" into the text box

(without double quotes)

Hit the enter-key or click launch.

Now you should see your default-browser opening up, and showing results for "the eiffel tower" in google.
