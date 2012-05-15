#!/bin/bash
rm -f $1
cd book
zip -q0X "../$1" mimetype
zip -qXr9D "../$1" * -x "*.svn*" -x "*~" -x "*.hg*" -x "*.swp" -x ".DS_Store"
java -jar ../bin/epubcheck-3.0b5.jar ../$1
