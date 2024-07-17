# MRE for https://github.com/material-components/material-components-android/issues/4228

Bottom sheet's position will be incorrect when initially opened. Dragging the sheet will fix its postion, but clicking the sheet will call `requestLayout()` and position will become incorrect again.

Sheet's height was tested with Pixel 8 emulator, it might need to be changed for other devices
