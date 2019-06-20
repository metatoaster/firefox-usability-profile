# Usability fixes for Firefox

For some dumb reason the developers couldn't provide an option to easily
configure the quit shortcut nor allow scrolling on the tab bar, but
fortunately they provide a low level way to customise this stuff.   Put
the contents of the `chrome` directory into the root of a Firefox
profile dir and the following features should be provided:

- Disable the quit Firefox keyboard shortcut.
- Allow usage of the mouse wheel to scroll through the tab bar.
