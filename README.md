# ClangFormatCpp
Central Location to Store Formatting rules for my C++ projects

These are my current formatting rules that I use for all of my personal projects. Set it up in a central repo so I only ever have to edit one version, and so my automation tools can download and apply them to my projects.

Feel free to use, update, or comment however you like.

### Notes
-Currently only supports C++.
-Supports Precompiled Headers moved to the top of the include list, the current precompiled formats supported are Precompiled.(h/hpp) or [.\*]PCH.(h/hpp).

-Can be used in Unreal Engine 4, [\.*].generated.h files will be moved to the bottom of the include list.
