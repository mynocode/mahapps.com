Title: Release 1.4.2
Published: 1/30/2017
Category: Release
Author: punker76
---

# Changes / Fixes

- [#2814](https://github.com/MahApps/MahApps.Metro/pull/2814) Correct display of media buttons in `HotKeyBox` (thx @thoemmi)
- [7fcc6b7](https://github.com/MahApps/MahApps.Metro/commit/7fcc6b770c77f483eb038705b252cfa7624a343f) Fix breaking changes for obsolete properties `ButtonHelper.PreserveTextCase`, `ButtonHelper.CornerRadius` and `ControlsHelper.ButtonWidth`
- [a1d199d](https://github.com/MahApps/MahApps.Metro/commit/a1d199dd599fa9f46838d6449599b36c7035f76e) Fix binding to Content of HamburgerMenu
- [#2799](https://github.com/MahApps/MahApps.Metro/pull/2799) DateTimePicker SelectedDate issue (thx @xxMUROxx)
    + Fix issue where `SelectedDate` is set to the `DisplayDate` if the `SelectedDate` is `DateTime.MinValue`. This issue appears when binding to a property of DateTime and the date is `DateTime.MinValue`.
- Z-Order was wrong if `MetroWindow` is ignoring the Taskbar and maximized. This fix and the main Taskbar z-Order issue only happens with Windows 10 anniversary update 1607. Hopefully fixed in the future. [#2780](https://github.com/MahApps/MahApps.Metro/issues/2780)
- Use internal GetPhysicalCursorPos instead GetCursorPos (tested with remote desktop and different DPI) [#2748](https://github.com/MahApps/MahApps.Metro/issues/2748)

# Closed Issues

- [#2585](https://github.com/MahApps/MahApps.Metro/issues/2585) HotKeyBox gives wrong names to multimedia buttons
- [#2817](https://github.com/MahApps/MahApps.Metro/issues/2817) TransitioningContentControl's TransitionCompleted event fires twice
- [#2804](https://github.com/MahApps/MahApps.Metro/issues/2804) TransitionsEnabled=false NullpointerException
- [#2823](https://github.com/MahApps/MahApps.Metro/issues/2823) Issue with ClearTextButton on TextBox
- [#2815](https://github.com/MahApps/MahApps.Metro/issues/2815) Layout issue with TabControl, TabStripPlacement Left, TabControlHelper.IsUnderlined="True"
- [#2770](https://github.com/MahApps/MahApps.Metro/issues/2770) Increase Win10 ToggleSwitch Default Margins
- [#2780](https://github.com/MahApps/MahApps.Metro/issues/2780) External Dialogs not visible with MainWindow set to IgnoreTaskbarOnMaximize
- [#2748](https://github.com/MahApps/MahApps.Metro/issues/2748) Access Denied
- [#2591](https://github.com/MahApps/MahApps.Metro/issues/2591) Weird MetroProgressBar animation with IsIndeterminate=true
