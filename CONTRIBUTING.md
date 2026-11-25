# Contributing to Uninstall Here

Compile [`uninstall-here.wh.cpp`](uninstall-here.wh.cpp) as a local Windhawk mod on Windows 11. The [README](README.md) explains the Start menu flow.

## Review a change

- Use disposable desktop apps or a Windows test VM. Check that the Start menu opens the uninstaller for the selected app and that cancelling leaves the app installed.
- Check an unsupported item or one without an applicable uninstaller. For matching changes, try similar names, paths with spaces, and the app types documented in the README.
- For context-menu changes, verify the command appears in the expected position and can be used after reopening Start.

Include the Windows build, Windhawk version, app type, and the exact menu action. State whether you verified the dialog or completed a test uninstall.
