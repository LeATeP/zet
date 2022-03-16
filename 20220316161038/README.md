# go runes

strings in go encoded using UTF-8 and they represented by sequence of runes
strings is a slice of runes
and range is iterate over string's runes 

runes represent int32 or 4 bytes, that represent characters in UTF-8

to decrale rune type, put character in a single quotes
rune := 'a'
it will give `type int32`, and number representing this character in UTF-8 code

to print character represented by UTF-8, use `%c` in building string

To print the Unicode code point represented by the rune, use the `%U` == `U+00BF`


