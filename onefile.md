# Detailed steps for downloading individual .csv or .Rmd files from Github

Below, we provide detailed steps for downloading such files ...

1. using the [Safari browser on a Mac](#using-safari-on-a-mac)
2. using [Google Chrome on a Mac](#using-a-mac-with-google-chrome)
3. using [Google Chrome on a PC](#using-a-pc-with-google-chrome)
4. using [Microsoft Edge on a PC](#using-microsoft-edge-on-a-pc)

## Using Safari on a Mac

Suppose you've identified a single .Rmd (R markdown) file you want to download onto your PC from Github using Safari as your browser.

1. Click on the file name in Github to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Now, you want to download that page as a .Rmd file (you will need to remove the .txt extension that your browser will attempt to append) and save it somewhere useful. To do this on a Mac, I would do the following:
    1. Select Command-S or File ... Save Page As... which will bring up a download window.
    2. At the bottom of the window, you'll see a Format: box which will be set to Web Archive. Change that to Page Source and hit Save.
    3. This will bring up a note asking if you want to append .txt to the name. Select Don't append.

The resulting .Rmd file should open properly in RStudio.

Suppose you've identified a .csv (data) file you want to download onto your PC from Github using Safari as your browser.

1. Click on the file name in Github to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Now, you want to download that page as a .csv file and save it somewhere useful. To do this on a Mac, I would do the following:
    1. Select Command-S or File ... Save Page As... which will bring up a download window.
    2. At the bottom of the window, you'll see a Format: box which should be set to Page Source
    3. If you are asked whether you want to append .txt, select Don't Append, then hit Save.

The resulting .csv file should work for you in RStudio.

## Using a Mac, with Google Chrome

Suppose you've identified a single .Rmd (R markdown) file you want to download onto your Mac from Github using Google Chrome as your browser.

1. Click on the file name in Github to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Now, you want to download that page as a .Rmd file (you will need to remove the .txt extension that your browser will attempt to append) and save it somewhere useful. To do this on a Mac, I would do the following:
    1. Select Command-S or File ... Save Page As... which will bring up a download window.
    2. At the bottom of the window, you'll see a Format: box which will be set to text. Change that from text to all files.
    3. Now, at the top of the window, look for the filename where it says Save As: and delete the .txt at the end of the file name.
    4. Then hit Save.
The resulting .Rmd file should open properly in RStudio.

Suppose you've identified a .csv (data) file you want to download onto your Mac from Github using Google Chrome as your browser.

1. Click on the file name in Github to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Now, you want to download that page as a .csv file and save it somewhere useful. To do this on a Mac, I would do the following:
    1. Select Command-S or File ... Save Page As... which will bring up a download window.
    2. At the bottom of the window, you'll see a Format: box which should be set to comma-separated values. 
    3. At the top of the window, look for the filename where it says Save As: and if there is a `.txt` at the end of the file name, delete the `.txt`.
    4. Then hit Save.
The resulting .csv file should work for you in RStudio.

## Using a PC, with Google Chrome

Suppose you've identified a .Rmd (R markdown) or .csv (comma-separated version data) file you want to download onto your PC from Github.

1. Click on the file (either .Rmd or .csv) to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Download that page by selecting Ctrl-S (or by right-clicking and selecting Save as.)
4. Where you see Save as type: at the bottom of the download window select all files instead of text and then remove the `.txt` extension that your browser will attempt to append.
5. Save the file somewhere useful. 
The resulting file should open properly in R Studio.

## Using Microsoft Edge on a PC

Suppose you've identified a .Rmd (R markdown)  file you want to download onto your PC from Github using Microsoft's Edge browser.

1. Click on the file to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Download that page by selecting Ctrl-S (or by right-clicking and selecting Save as.)
4. Where you see Save as type: at the bottom of the download window select all files instead of text and
then remove the .txt extension that your browser will attempt to append, before you save the file somewhere useful. 
5. The resulting file should open properly in R Studio.

Suppose you've identified a .csv (data)  file you want to download onto your PC from Github using Microsoft's Edge browser.

1. Click on the file to view its contents.
2. On the top right of the document viewer window, click the `Raw` button. This will take you to a page that displays the text in the file.
3. Download that page by selecting Ctrl-S (or by right-clicking and selecting Save as.)
4. Where you see Save as type: at the bottom of the download window be sure it says Microsoft Excel Comma Separated Values File `(*.csv)`.
5. Save the file somewhere useful. The resulting data file should work properly in R Studio.
