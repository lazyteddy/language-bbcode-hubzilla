# Hubzilla BBCode support for the BBCode packe for Atom
I Was looking for a convenient way to write long [Hubzilla](https://zotlabs.org) posts offline, so I needed a way to include BBCode. I found [this](https://github.com/xKeiro/language-bbcode-and-syntax-highlight), and it worked, but I decided to do a little Hubzilla specific tailoring. For one thing, in Hubzilla the BBCode tags need to be lower case, otherwise they don't get rendered. Also, Hubzilla has lots of specific tags, and I thought it would be extremely convenient if I could start typing, say, `baseurl` and it would get automatically converted to `[oberserver.baseurl]`

# Original ReadMe below
## BBCode package for Atom
This package was made because I couldn't find any BBCode note taking pogram, so I decided to implement BBCodes to Atom, and with a note taking package you'll be able to make BBCode notes

## How to use tips
1. If you want to use the BBCode language as a default for a note use one these extensions: **.bb .bbcode**
2. To enable general spellchecking in BBCode documents add **source.bbcode** to the spell-check package's grammar settings
3. If you want a great note taking package download *![atom-notes](https://atom.io/packages/atom-notes)* and in it's extension settings add **.bb** (make that the first extension if you want to create bbcode notes by default)

## List of autofills
Bold = **bold**

Italic = **italic**

Underline = **underline**

Color = **color**

Size = **size**

Code = **code**

Image = **img**

Link = **url**

Align Left = **left**

Align Center = **Center**

Align Right = **right**

Quote = **quote**

Ordered List = **1** or **list_or**

Unordered List = **list**
