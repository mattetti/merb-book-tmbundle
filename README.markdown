# Text Mate Bundle for the Merb Book

Merb book preview: http://book.merbist.com
Merb book source : http://github.comn/mattetti/merb-book

## installation process:

    $ mkdir -p /Library/Application\ Support/TextMate/Bundles
    $ cd !$
    $ git clone git://github.com/mattetti/merb-book-tmbundle.git merb-book.tmbundle
    $ osascript -e 'tell app "TextMate" to reload bundles'

## Usage

* create a notes div

 Select some the text you want to put in a notes div and press ctrl + Z (or press ctrl + z and add some text)
 
* add a reference

 Sype ``ref`` and then press tab, enter the reference code you want to use, then press tab again, type the reference text, press tab again, delete the comment and move the reference text line to the bottom of the page.
 
* ruby code syntax

  type ``ruby`` and press tab
  
* shell syntax

  type ``shell`` and press tab
  
* add an abbreviation

  type ``abb`` and press tab
  
* add a page table of contents

  type ``toc`` and press tab