# Examples:
___
## xfce4-appfinder :
These are added on the Custom Actions tab, in the xfce4-appfinder's preferences dialog.

**Note:**
If your default-browser isn't running, a search  should start it, to show your results. If it is already running, then it will either do the search in a new tab, a new window, or something else depending on settings.
___
### Google web-search:
___
  Add a new entry, and set options as follows:
  
  Type:	`Prefix`
  
  Pattern:	`google`
  
  Command: `websearch 'google.web' %s`

Then close the xfce4-appfinder windows.

#### To test it:
Hit your keyboard-shortcut for xfce4-appfinder. (alt+F2)

type: `google the eiffel tower` into the text box

Hit the enter-key (or click launch).

This should show results for a search on `the eiffel tower` in Google. 

___
### Google image-search for svg files only:
____
Add entry,set options as follows:
  
  Type:	`Prefix`
  
  Pattern:	`vector`
  
  Command: `websearch 'google.images.filetype.vector' %s`

Then close the xfce4-appfinder windows.

#### To test it:
Hit your keyboard-shortcut for xfce4-appfinder. (alt+F2)

type: `vector eiffel tower` into the text box

Hit the enter-key (or click launch).

Now you should get the results of a Google Image search for svg-images on `eiffel tower`.
