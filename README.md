Pass-gen
=========

Pass-gen is a light password generator. Having multiple passwords or even a password per service is usually a secure practice but it can get quite annoying to invent every time a new one. 

Every option from pass-gen defines character sets. Pass-gen will ensure that the password generated contains at least one character from each 'character set' provided. For example, the option -ac specifies two characters sets: 'abcdefghijklmnopqrstuvwxyz' and 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'.

Note: When using the -s option, you can define character sets by separating strings with a space. For example: pass-gen -s "abcdef 12345".

This tool comes with different options:

 - -l _NUMBER_ : specify the length of the password. It is possible to use a range like N1-N2.
 - -s _STRING_ : specify the string that pass-gen should use to generate the password. In short, it is all the characters possible in the password. This option will always be override by the usage of -a, -ac, -sp, -nu.
 - -n _NUMBER_ : The number of password pass-gen will generate.
 - -a : Use only alphabetical characters.
 - -ac : Use only alphanumeric characters.
 - -sp : Use only alphanumeric and a few special characters.
 - -nu : Use only numeric characters.

This tool was written by [faltad](http://faltad.sbrk.org/) - Jean-Baptiste Poupon
