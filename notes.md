## Starting with Prerequisites

To implement this project we use basic conect of python, tkinter, pytube library

- Tkinter is a standard GUI library and it is one of the easiest ways to build a GUI application.
- pytube used for downloading videos from youtube.

```pip install tkinter```
```pip install pytube```



### Codes

- Tk() used to initialize tkinter to create display window.
- geometry() used to set the window's width and height.
- resizable(0,0) set the fix size of window.
- title() used to give the title of window.


- Label() widget use to display text that users can't able to modify
- root is the name of the window
- text which we display the title of the label
- font in which our text is written.
- pack organized widget in block.

### Create Field to Enter link

- link is a string type variable that stores the youtube video link that the user enters.
- Entry() widget is used when we want to create an input text field.
- width sets the width of entry widget.
- textvariable used to retreive the value of current text variable to the entry widget.
- place() use to place the widget at a specific position.

## Create Function to Start Downloading.

Url variable gets the youtube link from the link variable by get() function and then str() will convert the link in string datatype

The video is download in the first present stream of that video by **stream.first()** method.

**Button()** widget used to display button on the window.

- text which we display on the label
- font in which the text is written.
- bg sets the background color.
- command is used to call the function

root.mainloop() is a method that executes when we want to run the program