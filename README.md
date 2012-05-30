ePub-Boilerplate
================

http://javierarce.github.com/epub-boilerplate

ePub Boilerplate is a simple template that helps you build ePub-formatted books.

How to use it
================

1. Get the template:

        $ git clone git@github.com:javierarce/epub-boilerplate.git

2. Edit the contents of the book directory.

3. Run the publish script to generate and validate the book:

        $ ./publish book.epub

ePub validation
================

This project uses epubcheck to validate the generated ePubs. If the build.sh script complains when running epubcheck, make sure you have java installed and it's in your PATH.

If you need help running epubcheck read this step-by-step guide.

Use the check script to validate the book.
================

    $ ./check book.epub
