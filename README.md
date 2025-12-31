windows-dvorak-for-devs
=======================

Contains a MS Keyboard Layout Creator source file of a keyboard layout based on Programmer Dvorak (as found on [http://www.kaufmann.no/roland/dvorak/](http://www.kaufmann.no/roland/dvorak/)).

How is this different than the Windows driver provided on that site?

1. I use Microsoft's Keyboard Layout Creator to make a native solution. This means that the 10-key number pad layout will be preserved, rather than taking on the same key assignments as the number row.
2. The source file will be included. This means you will be able to customize and recompile the source to suit your needs. Note: compiling from source will require the [Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) from Microsoft. With the Layout Creator, you will then be able to redistribute your modifications via installer. Pretty slick.

For MacOS, see this sister project: <https://github.com/jayliu50/macos-dvorak-for-devs>

### Guides and resources

- http://www.fieldlinguiststoolbox.org/Creating_a_Keyboard_Using_MSKLC.pdf?i=1