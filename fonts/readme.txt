                    Readme file for JSL Ancient fonts
                             19 August 1997

The "JSL Ancient" and "JSL Ancient Italic"  fonts  are  based  upon  two
nearly  identical  typefaces  of  seventeenth-century  English printers.
The first source used was "A compendious view  of  the  late  tumults  &
troubles  in  this  kingdom  by way of annals for seven years", by James
Wright, printed by Edward Jones in 1685; the second was  "Ars  Pictoria,
or  an  Academy  treating of Drawing, Painting, Limning and Etching", by
Alexander Browne, printed by J. Redmayne in 1668.

The two source typefaces are nearly identical, and the most  interesting
features,  such  as  the  descender on the italic capital N, are present
in both.  I used Redmayne's typeface primarily to fill  in  the  missing
letters  from  Jones'.  Both typefaces had several different versions of
certain italic capitals; I chose the more interesting ones.  One feature
of  Redmayne's  italic  typeface  that  was  lacking  in  Jones' was the
peculiar extensions of horizontal strokes, used to reduce the amount  of
whitespace used when justifying shorter lines of text. (I may eventually
produce  a  "JSL  Ancient  Italic  Bold"  which  includes these extended
letters.)

I used Fontographer 3.5.2 to produce  these  fonts.   Because  they  use
ANSI  encoding,  the glyph mapping will be somewhat different under OS/2
and the Macintosh.  For some reason, the TrueType version does not  work
under  OS/2,  so  I have generated both TrueType and Adobe Type I fonts.
Unfortunately, most of the cool ligatures are not used  by  the  default
OS/2  codepage (which all of the applications seem to use, regardless of
the config.sys setting), so they're pretty much inaccessible.

The ISO Latin-1 characters (32-127, 160-255) are all  present;  many  of
the  extended Windows characters (128-159) are present as well, but some
have been replaced in order to provide  certain  ligatures  and  archaic
characters:


Character                     JSL Ancient
  Code      JSL Ancient       Italic            Arial
-----------------------------------------------------------------
   0129                       Alternate 'v'     unused
   0130                       'sl' ligature     bottom single quote
   0131     Long 's'          Long 's'          florin (script f)
   0132                       'll' ligature     bottom double quote
   0134     'st' ligature     'st' ligature     dagger
   0135     'sh' ligature     'sh' ligature     double dagger
   0142     'ff' ligature     'ff' ligature     unused
   0143                       'is' ligature     unused
   0157     'ss' ligature     'ss' ligature     unused
   0158     'ct' ligature     'ct' ligature     unused

(A blank entry in JSL Ancient indicates that the code refers to the same
character as in Arial.)

Under OS/2, the only special character available is the long 's',  which
can be accessed as Alt-159.

Certain Windows 3.1 printer drivers do not output characters  which  are
"unused"  by the base Windows character sets (such as the 'ct' ligature)
unless the "Output TrueType fonts as graphics" box  is  checked  in  the
printer driver.  This problem may or may not occur under Windows 95, but
I can't say for certain.

JSL Ancient and JSL Ancient Italic are copyright (c) 1997 by Jeffrey  S.
Lee.   Permission  is  granted  to freely distribute them, provided that
they are distributed unaltered, both the roman and italic  versions  are
distributed  together, and they are accompanied by this text file.  They
may not be included in any commercial package without  prior  permission
from  the  author.   These  fonts  are "emailware"; if you like them and
decide to use them, please send me email at the address listed below.  I
will  not  charge  you  any  money  or send you annoying email spam; I'm
simply interested in who's using it, and I'd be  happy  to  receive  any
comments you might have about the fonts.

                                           Jeff Lee
                                           http://www.gate.net/~shipbrk/
                                           shipbrk@gate.net
