# Font Fallbacks
This is a tutorial on how to change the terminal's default fallback fonts(s) on
variant systems. It was inspired by the gabrielelana/awesome-terminal-fonts
project.

When displaying a character, the terminal first tries to find its glyph in
current font, and if no glyph is found, it then tries to look up the glyph from
a list of fallback fonts. This process is called the "font fallback mechanism".

Through the use of fallback fonts, it's possible to provide different typefaces
for variant character collections. 

A typical example is: setting "Monaco" as the default font, and
"PingFangSC-Regular" as the fallback font for Simplified Chinese characters.
In this setup, latin characters can be rendered with the nice looking "Monaco"
typeface, while Simplified Chinese characters will be rendered with the
"PingFangSC-Regular" font, which is optimized for CJK characters.

In the example above, if "PingFangSC-Regular" was configured to be the default
font, latin characters will look odd, because they are rendered by the
"PingFangSC-Regular" font instead.

# Project Moved to GitLab
This project has been moved to [GitLab][1]

References
----------
* [zerustech/font-fallbacks-tutorial][1]

[1]:  https://gitlab.com/zerustech/font-fallbacks-tutorial "zerustech/font-fallbacks-tutorial"
