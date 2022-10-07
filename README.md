## Redmon64pdfscribe
Redmon 1.9 windows printer port monitor, with the following minor changes to support [PdfScribe](https://github.com/stchan/PdfScribe):
* Searches up to 4096 processes (up from 128) for the access token.
* Changed the 64-bit dll output filename to "redmon64pdfscribe.dll"
* Updated the make file (redmon.mak) to work with Visual Studio 2022 Community.

## Acknowledgements
* [Russell Lang](http://www.ghostgum.com.au/) created Redmon.
* Thanks to @mca0815, @tahoop, @zs-doron for investigating the bug, and making the fix for PdfScribe - details are in the [issue thread](https://github.com/stchan/PdfScribe/issues/17).

## License
Redmon64pdfscribe's license is GPLv3.

## Notes
* Redmon home page is [here](http://www.ghostgum.com.au/software/redmon.htm).
* There's a Github mirror of the original source [here](https://github.com/ARLM-Keller/redmon).
