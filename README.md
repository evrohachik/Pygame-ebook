## Pygame-ebook

### Overview:

This is an ePub production of Al Sweigart's games programming book *Making Games with Python & Pygame* at (https://inventwithpython.com/pygame/), the only freely available ePub of the book to my knowledge. This isn't merely a copy of the source PDF and HTML, there are a few tweaks:

* New cover [PLANNED] - There's going to be a new cover that has the spirit of the original, but to my taste and at a larger resolution.
* Bonus chapter [POSSIBLE] - I might make a bonus chapter which shows how to make a Space Invaders-style game, in the spirit of Blitz Games' *Raspberry Invaders*.
* Licenses page - There's a new license page that clearly lays out the book's licenses, as standard in all my sample book productions.
* HTTPS links - All links direct to sites by using HTTPS unless the sites don't support it.
* Changed comment colour - Comments are red rather than grey.
* Better resolution XKCD comic - Used the original from the site and included a link back to XKCD and the tooltip caption. Also moved it below the chapter heading.
* New screenshots for operating systems in Chapter 1 - A lot has changed since 2012 and this e-book uses good resolution screenshots of the latest versions of Windows, macOS and Ubuntu. I may also include Raspbian with PIXEL too.
* Added instructions in Chapter 1 - I have added an alternate way to start IDLE using Spotlight and plan to add more instructions to make the book more useful, such as information on the Raspberry Pi.
* Changed subheading in Chapter 4 - From *Source Code to Slide Puzzle* to *Source Code for Slide Puzzle*.
* Replaced the lower-case letter (x) with the multiplication sign (×) when referring to dimensions. [ONGOING].
* Removed the links to the buggy programs at the top of Chapter 10 and replaced them with one contemporary link (https://inventwithpython.com/pygame/buggy/).
* Replaced link to (http://gamedevlessons.com/) with (http://www.hobbygamedev.com/) as it doesn't work anymore in Chapter 10.
* Added links to the glossary from chapters and internal links in the glossary.

Of course, you can suggest further tweaks. Go to the Issues tab and ask away. :-)

### E-book:

I have provided an ePub and the code needed to recreate it, feel free to use the code for your own projects as per the licenses stated below.

The e-book currently throws a few errors and warnings in [epubcheck 4.0.2](https://github.com/IDPF/epubcheck), though I am working to iron those out and end with the desired `No errors or warnings detected.` output. The ePub already ooks pretty good in Google Books, iBooks and Adobe Digital Editions.

#### Compiling:

A new ePub file can be made by using the provided `CreateE-book.py` via installing [Python 3](https://www.python.org/downloads/) and then ~~running the script on IDLE, [Thonny](http://thonny.org/) or~~ the `python3 CreateE-book.py` command on Bash (macOS and GNU/Linux Terminal). The script however **does not** work with Python 2 and I have no plans to backport.

XHTML, CSS and the `metadata.json` files can be edited using a text editor such as [Atom](https://atom.io/) and [Notepad++](https://notepad-plus-plus.org/).

The `toc.ncx` and `content.opf` are generated by the `CreateE-book.py` and shouldn't be edited as they would be overwritten.

If you need to check the e-book yourself run `java -jar epubcheck.jar MakingGames.epub` from on the Bash terminal (macOS and GNU/Linux) after moving to the folder that the ePub file is placed in.

### Licensing:

Book content such as text and images are licensed under the **Creative Commons Attribution-Noncommercial-Share Alike 3.0 United States**.

Book code such as the .xhtml, .css and .xml files are licensed under **Creative Commons Zero 1.0 Universal (CC0 1.0)**.

The IDPF's `epubcheck-4.0.2` tool is licensed under **Apache License 2.0**, **Mozilla Publice License** and **BSD 3-clause License**.

<img style="text-align: center;" width="300" height="450" src="https://github.com/inferno986return/Pygame-ebook/blob/master/e-book/OEBPS/images/cover.png" alt="Cover"/>
