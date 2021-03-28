# Write now has an official script that does something similar to this repo.
See https://github.com/styluslabs/templates/blob/master/pdf2write.sh


# PDF converter for Styluslabs 'Write' - Windows Version
## This readme is OLD - run convertWin.py in IDLE and follow the instructions.

The best piece of software I have found for taking notes on a computer with an active 
stylus (such as a Lenovo Yoga, Surface Pro etc.) is [Styluslabs Write](http://www.styluslabs.com/)
The biggest downside about it is that it does not have the ability to import PDF documents.
Thankfully it uses HTML and SVG to store it's docments. As a result, by converting a PDF into a
series of images, a solution was botched together.

# Requirements:
At this stage it is a system that works, but it isn't elegent or extensible. It is a script not a program.
As a result, to use it you have to edit two lines in the program:

 - The file path
 - The number of pages in the PDF
 
As of writing they are lines 21 and 22.

The script is currently **linux only**, and you need the following programs installed:

 - Python3
 - imagemagick
 
# Future development:
Development goals, for if I keep on developing this

- Cross-platform. I guess I'll have to see if imagemagick is can be run in a Windows/mac environment
- Add a UI or CLI so you don't have to edit the script to set the file name. I'll probably use TK
- Auto-detect page count of the PDF
- Generate thumbnail
- Open at the top of the document the first time you open a document

But honestly, I doubt I'll get arround to developing this further as it works fine for me at the moment.If other people want
to contribute, please do.
