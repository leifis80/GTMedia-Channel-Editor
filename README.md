# GTMedia Channel Editor

GTMedia Channel Editor is a free, independent Windows utility for viewing and editing GTMedia XML channel-list exports. The first public beta is **v0.4.0-beta.3**.

**Tested:** GTMedia GTX Combo 8K with original firmware. The GTX Combo 4K, other GTMedia receivers, Mars firmware, and other XML formats have not been tested. Compatibility cannot be guaranteed. This project is not affiliated with or endorsed by GTMedia.

## Download

Download the Windows ZIP from [GitHub Releases](https://github.com/leifis80/GTMedia-Channel-Editor/releases). Extract it and run `GTMediaChannelEditor_Beta.exe`. The ZIP also contains a user guide. The program's **Help → Quick guide…** menu provides short instructions.

## Current features

- Browse TV and radio channels, satellites, transponders and other lists.
- Search, sort and filter channels by satellite or TV/radio type.
- Rename a channel. Existing `xxx` prefixes are hidden in the table and retained in the saved XML.
- Move one channel to a new position. Channels between the old and new positions shift, with separate TV and radio numbering.
- Undo a name change or the latest move and save a separate XML copy. The original export is not overwritten.
- See an activity indicator while the XML copy is saved.

Satellite and transponder editing, channel deletion, adding entries, custom favorite lists and planned batch moves are not available in this beta.

## Use and known behavior

1. Export a fresh channel list from the receiver and keep a backup.
2. Open the XML export, make a small edit and save an XML copy.
3. Import the copy into the receiver and check the result before making extensive changes.

For several moves, check the current positions before each one. An earlier move can shift the position needed for a later move. In a larger test, a channel initially placed at position 600 ended at 598 after subsequent moves. Working from higher target positions to lower ones helped in that test, but results depend on the moves. Review the final list on the receiver.

The **Receiver no. (estimated)** column counts TV and radio channels without gaps; **XML order** shows the stored value. The tested receiver displayed consecutive numbers even where the export had a gap in the stored order.

## Feedback

Please use [Issues](https://github.com/leifis80/GTMedia-Channel-Editor/issues) for reproducible bugs, compatibility reports and suggestions. Include the exact receiver model and firmware version. Review XML exports for private information before sharing them.

Additional languages may be supported in a later version. The software is free to download and use.

Developed by **Leif-Inge Stenseth**.
