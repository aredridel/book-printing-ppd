Book Printing Postscript Printer Definition (PPD)
====================

Macintosh computers in particular won't generate a PDF without a printer configured for the correct size of paper. If you have no printer installed that can print, say, a US Trade Paperback (6 x 9 inches), MacOS will refuse to format a PDF that way.

This printer PPD can be used to configure a dummy printer using the Generic Postscript driver that has the correct page sizes.

Currently supported sizes
-------------------------

* 8.5 x 11 (US Letter)
* 8.5 x 9
* 8.5 x 8.5
* 8.268 x 11.693 (A4)
* 8.25 x 11
* 8 x 10.88
* 8 x 10
* 8 x 8
* 7 x 10
* 7.5 x 9.25
* 7.44 x 9.69
* 6.69 x 9.61
* 6.625 x 10.25
* 6.14 x 9.21
* 6 x 9 (US Trade Paperback)
* 5.83 x 8.27
* 5.5 x 8.5
* 5.25 x 8
* 5.06 x 7.81
* 5 x 7
* 4.72 x 7.48
* 4.37 x 7 (US Mass Market Paperback)

How to use this PPD
-------------------

- Download the [Book.ppd](Book.ppd) file
- Add a printer to your mac
    - Select IP
    - Select IPP protocol
    - Enter 127.0.0.1 as the IP address
    - Call the printer "Dummy Book Printer"
    - For the printer type, select "Other" and choose the "Book.ppd" file
- Print, choose the Dummy Book Printer, then choose PDF
    
