ePub-Boilerplate
================

http://javierarce.github.com/epub-boilerplate

ePub Boilerplate is a simple template that helps you build ePub-formatted books.

## How to use it

1. Get the template:

        $ git clone git@github.com:javierarce/epub-boilerplate.git

2. Edit the contents of the **book** directory.

3. Run the publish script to generate and validate the book:

        $ ./publish book.epub

## ePub validation

This project uses epubcheck to validate the generated ePubs. If the build.sh script complains when running epubcheck, make sure you have java installed and it's in your PATH.

If you need help running epubcheck read this step-by-step guide.

## Use the check script to validate the book.

    $ ./check book.epub
    
## Useful resources
      
* <a href="http://idpf.org/epub/30">EPUB 3.0 spec</a></li>
* <a href="http://wiki.mobileread.com/wiki/Device_Compatibility">Device compatibilty chart</a></li>
* <a href="https://github.com/mattharrison/epub-css-starter-kit">ePub CSS Starter Kit</a></li>
* <a href="http://code.google.com/p/epubcheck">ePub Validator</a></li>
* <a href="http://www.famkruithof.net/uuid/uuidgen">UUID generator</a></li>
* <a href="http://www.bisg.org/what-we-do-0-136-bisac-subject-headings-list-major-subjects.php">BISAC Subject Headings List</a></li>
* <a href="http://blog.threepress.org/2009/11/27/practical-epub-metadata-authorship/">Practical ePub metadata: Authorship</a></li>
* <a href="http://www.loc.gov/marc/relators">MARC Code List for Relators</a></li>

