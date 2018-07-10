# PDF Nano

[DMG Version here][1]

PDF Nano could dramatically reduce the size of PDF, while keeping the images and texts clear enough for screen readers.

Actually, PDF Nano is an Automator workflow, therefore it works on macOS only, as a service on the context menu.

## Prerequisites

You will need Ghostscript, a famous interpreter for the PostScript language and for PDF.

To install [Ghostscript][2], you can:
*  follow [the official guide][3]
*  or use [Homebrew][4]:`brew install ghostscript `
*  or download and open [this install package][5]

## Install PDF Nano

Open `PDF Nano.workflow` and install the service.

## Usage

Right-click the PDF and select `PDF Nano` service on the context menu, and just wait for the magic.

## Notes

* The magic may come slowly if the PDF is large. For example, it may take 40s to compress a PDF from 40MB to 2MB. Yeah, I know it’s a bit slow.
* Maybe not just a bit.
* File stream is not supported yet.

## License

MIT

[1]:	http://ovdx9zp24.bkt.clouddn.com/PDF%20Nano.dmg
[2]:	https://ghostscript.com/index.html
[3]:	https://ghostscript.com/doc/9.23/Install.htm#Install_Unix
[4]:	https://brew.sh/
[5]:	http://pages.uoregon.edu/koch/
