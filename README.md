# OOoLilyPond

OOoLilyPond (OLy) is a LibreOffice/OpenOffice extension to include LilyPond music fragments in text documents.

## Installation

Being a [LibreOffice]/[OpenOffice] extension, you need a version of LibreOffice / OpenOffice installed on your computer, first. And the music engraving software [LilyPond] must be installed on your system. Then just download the latest OLy release from the [download] page. The extension can be installed either by opening it with LibreOffice or by following these steps in the menu:

*Extras > Extension Manager… > Add…*

and then choosing the downloaded extension file (.oxt).

Your toolbars in Writer, Impress and Draw should now have a new "OLy" button which launches the extension.

## Usage

[LilyPond] is powerful musical typesetting software that compiles given source code into graphical output, just like LaTeX does with mathematical formulas. 

OOoLilyPond enables you to enter LilyPond code from within your Office document. Both the resulting image and its source code will be embedded within the document. 
No need to keep any additional files other than the Writer/Draw/Impress document itself.

To create a new OLy object, just click the "OLy" button and an editor window will open. Enter some LilyPond code and click the "LilyPond" button. After successful compiling, the editor window will close and the resulting image will be visible in your document. 

To edit an existing object, select it first and then click the "OLy" button. In the editor window you will have access to your code again.

If you want to get to know LilyPond, a good place to start is the [introduction] into LilyPond.

### Compatibility 

OOoLilyPond (OLy) works with recent versions of LibreOffice (5.3.0.3) and OpenOffice (4.1.3). Older versions should work as well. It has even been tested with OpenOffice 2.4 without issues. 

Any content (LilyPond code, templatex, OLy configuration files) created with/for OLy 0.4.x will work with OLy 0.5.x - and vice versa. (Fully compatible, forward and backward.)
Older snippets created with OLy 0.3.x will also work with 0.4.x and 0.5.x, but not (necessarily) vice versa.


[LibreOffice]: http://libreoffice.org/
[OpenOffice]: http://www.openoffice.org/
[LilyPond]: http://lilypond.org
[download]: https://github.com/openlilylib/LO-ly/wiki/Downloads
[introduction]: http://lilypond.org/introduction.html

## Authors

Copyright © 2005 Geoffroy Piroux  
Copyright © 2009 Samuel Hartmann  
Copyright © 2017 Klaus Blum

## License

This program is free software. It is licensed under the [GPL3].

[GPL3]: https://www.gnu.org/licenses/gpl.html "GPL3"
