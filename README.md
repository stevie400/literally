# literally

A confusingly named library for turning go values into their literal representations. This is meant to be used for generating tests and code in failure tolerant settings where speed is not a huge concern. Don't let me catch this in a vital code path.

There are some glaring holes in the library when it comes to certain types -- functions, unsafe pointers, various pointers to various type -- and nil is used as the value for these.