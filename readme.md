# Sidebar Tools

![Travis Status](https://travis-ci.com/braver/SideBarTools.svg?branch=master)

<img src="https://raw.githubusercontent.com/braver/SideBarTools/master/screenshot.png" width="502">

Some useful tools to add to your sidebar context menu:

- Copy Filename
- Copy Relative Path
- Copy Absolute Path
- Duplicate
- Move

They're all also available via the command palette, in addition to:

- Reveal In Sidebar

To open a file in its default application, consider installing the [Open in Default Application][2] package.

If you're looking for "Reveal in Finder/Explorer" for directories, [Open in Default Application][2] does that too.

This package offers fewer commands than e.g. [SidebarEnhancements][1], striking a balance somewhere between the bare minimum 
and going overboard. This has benefits:

- The default context menu isn't replaced, this package just adds some useful 
  new commands.
- It's tiny, light-weight and reliable.
- We won't [track][3] [you][5]. Ever.


## Credits

We used [SidebarEnhancements][1] as a starting point, but completely re-implemented everything we wanted to keep. Now it comes in at just over 200 lines of super clean Python with zero legacy. Special thanks go out to [@rwols][6] and [@mandx][7] to make this happen.


[1]: https://packagecontrol.io/packages/SideBarEnhancements
[2]: https://packagecontrol.io/packages/Open%20in%20Default%20Application
[3]: https://github.com/SideBarEnhancements-org/SideBarEnhancements/blob/d1c7fa4bac6a1f31ba177bc41ddd0ca902e43609/Stats.py
[5]: https://forum.sublimetext.com/t/rfc-default-package-control-channel-and-package-telemetry/30157
[6]: https://github.com/braver/SideBarTools/pull/2
[7]: https://github.com/braver/SideBarTools/pulls?q=is%3Apr+author%3Amandx
