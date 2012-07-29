# VMPK layouts

This is an unofficial repository for user-contributed keyboard layouts for [Virtual MIDI Piano Keyboard](http://vmpk.sourceforge.net/) (VMPK). These are additional layouts, besides the ones included with VMPK.

## To use these layouts
0. Download the layouts, e.g. by `git clone`ing this repository.
0. In VMPK, open Edit → Preferences.
0. Under "Keyboard Map" or "Raw Keyboard Map" (according to the type of keymap you want to load), click "Load...". Browse to the location you downloaded the layout files to and select your desired layout.
0. Press Open, OK. Start playing.

NOTE: As of this writing, [the mainline VMPK has a bug that causes it to choke on XML comments in the input](http://sourceforge.net/tracker/?func=detail&aid=3549819&group_id=236429&atid=1100307), so to use these layouts, use a version with [the fix](https://github.com/mechanical-snail/vmpk/tree/fix_xml_parsing) applied.

## OS and keyboard support
VMPK raw keyboards are currently specific to OS, and non-raw layouts are specific to the current keyboard layout selected in the OS. If you get one of these layouts working on another OS/keyboard, it will be appreciated if you submit it here as a new file.

## To contribute a fix or a new layout
Branch and send a pull request.

## Links
* [VMPK development](http://sourceforge.net/projects/vmpk/)
* Some other [shared keymaps and instruments](http://sourceforge.net/tracker/?group_id=236429&atid=1210216)