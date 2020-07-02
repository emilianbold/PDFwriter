# Export difficult PDFs with this macOS printer driver

This in an macOS compatible print driver that enables you to “print” your documents directly to a PDF file.

[![](https://raw.githubusercontent.com/rodyager/RWTS-PDFwriter/master/sources/PDFwriter.iconset/icon_256x256.png "Click to download installer pkg")
Click to download the installer pkg](https://github.com/emilianbold/RWTS-PDFwriter/releases/tag/v1.0.2)


# Have you ever seen this in Preview?

> Please wait...

> If this message is not eventually replaced by the proper contents of the document, your PDF viewer may not be able to display this type of document.

> You can upgrade to the latest version of Adobe Reader for Windows®, Mac, or Linux® by visiting

This happens for PDFs containing XFA Forms which only Adobe Reader can read and print.

If you want to **export** such a PDF into a normal PDF that even Preview can open then install this printer driver and get Adobe Reader to print to it. That's all there is.


## Installation and Usage Instructions
Download the installer package by clicking on the printer icon above and install as usual. After installation, your new printer will be ready for use.

### Usage

Simply print your documents using **PDFwriter** as your printer. 

![Print to PDFwriter](print-to-pdfprinter.png)

The “printed” PDF files produced will be stored in the directory 

`   /Users/Shared/PDFwriter/<your user name>   `

![PDFwriter folder](shared-folder.png)

For convenient access to this folder, simply drag it to the right hand end of your dock.

## Removal instructions
If you want to uninstall **PDFwriter**, open Terminal.app, type 

`   /Library/Printers/RWTS/PDFwriter/uninstall.sh   `

and press Return. You will be asked for your admin password. After hitting Return, **PDFwriter** will be entirely removed from your system. 

