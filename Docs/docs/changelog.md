# Change Log

Version history / release notes for each release. 

## Version 1.0.1 (Hotfix)

Changes/Fixes:

* Fixed incorrect automation track value when starting the song exactly on a vertex that is alone in a pattern
* Fixed crash using "select all" in a Sequence automation
* Fixed crash pasting curves then using undo/redo
* Fixed crash loading some soundfonts
* Fixed crash right-clicking (or long pressing on mobile) past the end of the song on the timeline
* Fixed crash trying to bind "Enter" as a keyboard shortcut
* Fixed crash unloading projects with missing soundfont presets
* Fixed crash when exporting to a full disks, read-only folders, etc.
* Fixed crash playing after deleting an instrument
* Fixed crash when changing channel instrument when automation tracks are present
* Fixed note parameter curves disapearing when saving in some situations
* Fixed project explorer not refreshing the channel list when deleting from sequencer, could lead to crash
* Fixed wavetable loop/release points not saving
* Fixed missing note sample colors on C notes when on top of viewport
* Fixed first item of context menus not being highlighting immediately after opening
* Fixed Cmd+Q tooltip being displayed on MacOS, will display Ctrl+Q now
* Fixed FDS modulation table changes not being detected sometimes
* Fixed wavetable playing at wrong frequency after a changing the table size
* Fixed incorrect envelope delay on custom curves
* Fixed window being not-resizable on MacOS, or having the wrong size when maximized
* Greyed out the preset min/max when not using a preset (i.e. Custom)
* Changed the min/max frequencies for the EQ so that all frequencies are accessible
* Allowed Project Explorer to be almost 40% smaller.
* Changed default follow mode position to 50%
* Added a shake to the sound font notifiction so it draws more attention
* Added French and Chinese translations (thanks Lancel0t and FREirc!)

Breaking/Behavior changes:

* The file format has changed, meaning file saved with version 1.0.1 will not open in 1.0.0. This usually never happens in a hotfix, but we are in the early days of the app and I will need to make a few exceptions.

## Version 1.0.0

Initial release.
