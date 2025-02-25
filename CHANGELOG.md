# Change log

## Release 0.7.0
* New: Allow copying items between tabs. ([#318](https://github.com/ksnip/kImageAnnotator/issues/318))
* New: CTRL + A does not select all text typed. ([#198](https://github.com/ksnip/kImageAnnotator/issues/198))
* New: Open text edit mode when double-click on textbox figure in Text tool. ([#180](https://github.com/ksnip/kImageAnnotator/issues/180))
* New: Add reflowing capability to the text tool. ([#129](https://github.com/ksnip/kImageAnnotator/issues/129))
* New: Editing text, no mouse cursor edit functions. ([#297](https://github.com/ksnip/kImageAnnotator/issues/297))
* New: Mouse click within a text box for setting specific editing position and selecting text. ([#273](https://github.com/ksnip/kImageAnnotator/issues/273))
* Fixed: Text isn't reflowed the next line within the box and text overlaps when resizing box. ([#271](https://github.com/ksnip/kImageAnnotator/issues/271))
* Fixed: Can't wrap long text line when I resize Text box area. ([#211](https://github.com/ksnip/kImageAnnotator/issues/211))
* Fixed: Key press operations affect items across different tabs. ([#319](https://github.com/ksnip/kImageAnnotator/issues/319))
* Fixed: Clipboard cleared when new tab added. ([#321](https://github.com/ksnip/kImageAnnotator/issues/321))

## Release 0.6.1
* Fixed: Fix for unnecessary scrollbars when a screenshot has a smaller size than the previous one. ([#303](https://github.com/ksnip/kImageAnnotator/issues/303))
* Fixed: Add KDE support for scale factor. ([#302](https://github.com/ksnip/kImageAnnotator/issues/302))
* Fixed: Show tab tooltips on initial tabs.
* Fixed: Sticker resizing is broken when bounding rect flipped. ([#306](https://github.com/ksnip/kImageAnnotator/issues/306))

## Release 0.6.0
* New: Add optional undo, redo, crop, scale and modify canvas buttons to dock widgets. ([#263](https://github.com/ksnip/kImageAnnotator/issues/263))
* New: Cut out vertical or horizontal slice of an image. ([#236](https://github.com/ksnip/kImageAnnotator/issues/236))
* New: Middle-click on tab header closes tab. ([#280](https://github.com/ksnip/kImageAnnotator/issues/280))
* New: Add button to fit image into current view. ([#281](https://github.com/ksnip/kImageAnnotator/issues/281))
* New: Allow changing item opacity. ([#110](https://github.com/ksnip/kImageAnnotator/issues/110))
* New: Add support for RGBA colors with transparency. ([#119](https://github.com/ksnip/kImageAnnotator/issues/119))
* New: Add mouse cursor sticker. ([#290](https://github.com/ksnip/kImageAnnotator/issues/290))
* New: Allow scaling stickers per setting. ([#285](https://github.com/ksnip/kImageAnnotator/issues/285))
* New: Respect original aspect ratio of stickers. ([#291](https://github.com/ksnip/kImageAnnotator/issues/291))
* New: Respect original size of stickers. ([#295](https://github.com/ksnip/kImageAnnotator/issues/295))
* Fixed: Adding image effect does not send image change notification. ([#283](https://github.com/ksnip/kImageAnnotator/issues/283))
* Fixed: Blur / Pixelate break when going past image edge once. ([#267](https://github.com/ksnip/kImageAnnotator/issues/267))
* Fixed: Item opacity not applied when item shadow disabled. ([#284](https://github.com/ksnip/kImageAnnotator/issues/284))
* Changed: Max font size changed to 100pt. 

## Release 0.5.3
* Fixed: Crash while typing text on wayland. ([#256](https://github.com/ksnip/kImageAnnotator/issues/256))
* Changed: Show scrollbar when not all tools visible. ([#258](https://github.com/ksnip/kImageAnnotator/issues/258))

## Release 0.5.2
* Fixed: Memory leaks caught by ASAN. ([#243](https://github.com/ksnip/kImageAnnotator/issues/243))
* Changed: Use system font provided by QGuiApplication as default for text tool. ([#247](https://github.com/ksnip/kImageAnnotator/issues/247))

## Release 0.5.1
* Fixed: Crashes on destruction. ([#242](https://github.com/ksnip/kImageAnnotator/issues/242))

## Release 0.5.0
* New: Add function for loading translations. ([#173](https://github.com/ksnip/kImageAnnotator/issues/173))
* New: Add a new tool for creating resizable movable duplicates of regions. ([#131](https://github.com/ksnip/kImageAnnotator/issues/131))
* New: Add support for hiding annotation settings panel. ([#182](https://github.com/ksnip/kImageAnnotator/issues/182))
* New: Add config option for numbering tool to only set next number. ([#42](https://github.com/ksnip/kImageAnnotator/issues/42))
* New: Allow manually changing canvas size. ([#92](https://github.com/ksnip/kImageAnnotator/issues/92))
* New: Canvas background color configurable. ([#91](https://github.com/ksnip/kImageAnnotator/issues/91))
* New: Zoom in and out with keyboard shortcuts. ([#192](https://github.com/ksnip/kImageAnnotator/issues/192))
* New: Zoom in and out via buttons from UI. ([#197](https://github.com/ksnip/kImageAnnotator/issues/197))
* New: Add reset zoom keyboard shortcut with tooltip. ([#209](https://github.com/ksnip/kImageAnnotator/issues/209))
* New: Add keyboard shortcut support for text tool. ([#183](https://github.com/ksnip/kImageAnnotator/issues/183))
* New: Allow rotating background image. ([#199](https://github.com/ksnip/kImageAnnotator/issues/199))
* New: Allow flipping background image horizontally and vertically. ([#221](https://github.com/ksnip/kImageAnnotator/issues/221))
* New: Configurable UI with dockable settings widgets. ([#102](https://github.com/ksnip/kImageAnnotator/issues/102))
* New: Add invert color image effect. ([#228](https://github.com/ksnip/kImageAnnotator/issues/228))
* New: Allow disabling item shadow per item from UI. ([#223](https://github.com/ksnip/kImageAnnotator/issues/223))
* New: Add a font selection to UI. ([#130](https://github.com/ksnip/kImageAnnotator/issues/130))
* New: Add zoom in/out capability to crop view. ([#212](https://github.com/ksnip/kImageAnnotator/issues/212))
* New: Allow to zoom in modify canvas view. ([#229](https://github.com/ksnip/kImageAnnotator/issues/229))
* New: Select item after drawing it and allow changing settings. ([#230](https://github.com/ksnip/kImageAnnotator/issues/230))
* Changed: Change drop shadow to cover all sites. ([#202](https://github.com/ksnip/kImageAnnotator/issues/202))
* Fixed: Deleting item outside image doesn't decrease canvas size. ([#164](https://github.com/ksnip/kImageAnnotator/issues/164))
* Fixed: Duplicate region of grayscale image has color. ([#214](https://github.com/ksnip/kImageAnnotator/issues/214))
* Fixed: Marker shows fill and width config when modifying existing item. ([#225](https://github.com/ksnip/kImageAnnotator/issues/225))
* Fixed: Highlighter/Marker washed out color and overlapping. ([#227](https://github.com/ksnip/kImageAnnotator/issues/227))
* Fixed: Popup menus shown outside screen. ([#226](https://github.com/ksnip/kImageAnnotator/issues/226))
* Fixed: Not possible to enter value in the width tool. ([#233](https://github.com/ksnip/kImageAnnotator/issues/233))
* Fixed: Obfuscation tool shows fonts settings when switching from tool with font. ([#231](https://github.com/ksnip/kImageAnnotator/issues/231))
* Fixed: Annotation tools are not displayed if application starts with docks hidden. ([#237](https://github.com/ksnip/kImageAnnotator/issues/237))
* Fixed: Vertical scrollbar missing after using Paste embedded and moving the image. ([#232](https://github.com/ksnip/kImageAnnotator/issues/232))
* Fixed: Not possible to disable tool automatically deselected after drawn. ([#238](https://github.com/ksnip/kImageAnnotator/issues/238))
* Fixed: Annotation tool shortcuts do not work if the panel is hidden. ([#239](https://github.com/ksnip/kImageAnnotator/issues/239))

## Release 0.4.2
* Fixed: Fetching image from annotator with HiDPI enabled pixelates image. ([#218](https://github.com/ksnip/kImageAnnotator/issues/218))
* Fixed: Keep aspect ratio only work when pressing CTRL before moving resize handle. ([#219](https://github.com/ksnip/kImageAnnotator/issues/219))

## Release 0.4.1
* Changed: Horizontally align text inside spin box. ([#203](https://github.com/ksnip/kImageAnnotator/issues/203))
* Changed: Change zoom with mouse wheel to CTRL+Wheel. ([#210](https://github.com/ksnip/kImageAnnotator/issues/210))
* Fixed: Brazilian Portuguese translation not loaded. ([#176](https://github.com/ksnip/kImageAnnotator/issues/176))
* Fixed: error: control reaches end of non-void function. ([#177](https://github.com/ksnip/kImageAnnotator/issues/177))
* Fixed: Cursor in Text tool have too bad visibility. ([#184](https://github.com/ksnip/kImageAnnotator/issues/184))
* Fixed: bumped SONAME without name change. ([#185](https://github.com/ksnip/kImageAnnotator/issues/185))
* Fixed: Entering multiple characters at once moves the text cursor only for one character. ([#186](https://github.com/ksnip/kImageAnnotator/issues/186))
* Fixed: Activating context menu while drawing item leaves item in error state. ([#196](https://github.com/ksnip/kImageAnnotator/issues/196))
* Fixed: Icons not scaled on gnome with hdpi enabled. ([#201](https://github.com/ksnip/kImageAnnotator/issues/201))
* Fixed: Text/Number Pointer and Text/Number Arrow don't inherit Text/Number Font in Settings. ([#208](https://github.com/ksnip/kImageAnnotator/issues/208))

## Release 0.4.0
* New: Add Pixelate image area tool. ([#140](https://github.com/ksnip/kImageAnnotator/issues/140))
* New: Zoom in and out. ([#123](https://github.com/ksnip/kImageAnnotator/issues/123))
* New: Add interface for adding custom tab context menu actions. ([#96](https://github.com/ksnip/kImageAnnotator/issues/96))
* New: Add drop shadow to captured images. ([#133](https://github.com/ksnip/kImageAnnotator/issues/133))
* New: Add grayscale image effect. ([#151](https://github.com/ksnip/kImageAnnotator/issues/151))
* New: Add numeric pointer with arrow annotation item. ([#152](https://github.com/ksnip/kImageAnnotator/issues/152))
* New: Add text pointer annotation item. ([#154](https://github.com/ksnip/kImageAnnotator/issues/154))
* New: Add text pointer with arrow annotation item. ([#153](https://github.com/ksnip/kImageAnnotator/issues/153))
* New: Add option to automatically switching to select tool after drawing item. ([#161](https://github.com/ksnip/kImageAnnotator/issues/161))
* New: Edit Text box with double click. ([#60](https://github.com/ksnip/kImageAnnotator/issues/60))
* New: Resize elements while keeping aspect ratio. ([#170](https://github.com/ksnip/kImageAnnotator/issues/170))
* Changed: Draw point when clicking and releasing without moving cursor. ([#136](https://github.com/ksnip/kImageAnnotator/issues/136))
* Changed: Zoom out less than 100%. ([#150](https://github.com/ksnip/kImageAnnotator/issues/150))
* Changed: Change to select tool after adding new annotation item. ([#155](https://github.com/ksnip/kImageAnnotator/issues/155))
* Changed: Move current zoom text to left side config panel. ([#157](https://github.com/ksnip/kImageAnnotator/issues/157))
* Fixed: Blur radius not updated when changing current items settings. ([#142](https://github.com/ksnip/kImageAnnotator/issues/142))
* Fixed: Text tool opens many unix sockets. ([#144](https://github.com/ksnip/kImageAnnotator/issues/144))
* Fixed: Text No Border and No Fill shows shadow beneath text. ([#148](https://github.com/ksnip/kImageAnnotator/issues/148))
* Fixed: Item properties remain displayed after item is removed or deselected. ([#168](https://github.com/ksnip/kImageAnnotator/issues/168))
* Fixed: Changing text box through editing text doesn't update resize handles. ([#171](https://github.com/ksnip/kImageAnnotator/issues/171))
* Fixed kColorPicker: Border around colors is not centered. ([#6](https://github.com/ksnip/kColorPicker/issues/6))

## Release 0.3.2
* Fixed: Tests fail to build with shared library. ([#128](https://github.com/ksnip/kImageAnnotator/issues/128))

## Release 0.3.1
* Fixed: Crashes after undoing a number annotation. ([#114](https://github.com/ksnip/kImageAnnotator/issues/114))
* Fixed: Text overlapping when resizing text box. ([#53](https://github.com/ksnip/kImageAnnotator/issues/53))
* Fixed: Snap lines to degrees not working when CTRL pressed before clicking annotation area. ([#113](https://github.com/ksnip/kImageAnnotator/issues/113))
* Fixed: "Border and Fill" submenu cutting off text under windows. ([#117](https://github.com/ksnip/kImageAnnotator/issues/117))
* Fixed: Undo removes several or all items. ([#121](https://github.com/ksnip/kImageAnnotator/issues/121))
* Fixed: Marker Rect and Ellipse draw only border but no fill. ([#126](https://github.com/ksnip/kImageAnnotator/issues/126))

## Release 0.3.0
* New: Tabs for images. ([#48](https://github.com/ksnip/kImageAnnotator/issues/48))
* New: Add option to translate UI. ([#54](https://github.com/ksnip/kImageAnnotator/issues/54))
* New: Saved image expand to include annotations out of border. ([#90](https://github.com/ksnip/kImageAnnotator/issues/90))
* New: Add support for stickers. ([#74](https://github.com/ksnip/kImageAnnotator/issues/74))
* New: Add tab context menu for close all tabs and close other tabs. ([#93](https://github.com/ksnip/kImageAnnotator/issues/93))
* New: Add Number with Arrow/pointer tool. ([#79](https://github.com/ksnip/kImageAnnotator/issues/79))
* Changed: Make dropdown buttons show popup on click. ([#89](https://github.com/ksnip/kImageAnnotator/issues/89))
* Changed: Hide unavailable setting widgets. ([#101](https://github.com/ksnip/kImageAnnotator/issues/101))
* Changed: Make arrow size decrease with stroke size. ([#84](https://github.com/ksnip/kImageAnnotator/issues/84))
* Fixed: Using select tool marks image as changed. ([#97](https://github.com/ksnip/kImageAnnotator/issues/97))
* Fixed: Emoticon selector shows a half of current emoticon. ([#104](https://github.com/ksnip/kImageAnnotator/issues/104))
* Fixed: FillPicker text or icon sometimes not visible. ([#105](https://github.com/ksnip/kImageAnnotator/issues/105))
* Fixed: Wrong image scaling on hdpi screen. ([#81](https://github.com/ksnip/kImageAnnotator/issues/81))
* Fixed: Copy area size differs from last capture. ([#107](https://github.com/ksnip/kImageAnnotator/issues/107))
* Fixed: Number Tool not reset when switching between tabs. ([#106](https://github.com/ksnip/kImageAnnotator/issues/106))

## Release 0.2.1
* Fixed: Edit border around text box doesn't disappear when done with editing. ([#71](https://github.com/ksnip/kImageAnnotator/issues/71))
* Fixed: Edit border not shown under Windows when NoFillNoBorder selected for Text Tool. ([#72](https://github.com/ksnip/kImageAnnotator/issues/72))
* Fixed: When adding text with background under Windows a filled rect is show in top left corner. ([#73](https://github.com/ksnip/kImageAnnotator/issues/73))
* Fixed: Drawing text tool rect from right to left and bottom top create no rect. ([#76](https://github.com/ksnip/kImageAnnotator/issues/76))
* Fixed: Text Tool FillType selection not saved. ([#75](https://github.com/ksnip/kImageAnnotator/issues/75))
* Fixed: Icons not scaled with HiDPI. ([#77](https://github.com/ksnip/kImageAnnotator/issues/77))
* Fixed: Text Cursor not show on Linux. ([#70](https://github.com/ksnip/kImageAnnotator/issues/70))

## Release 0.2.0
* New: Add image item and interface for adding them externally. ([#45](https://github.com/ksnip/kImageAnnotator/issues/45))
* New: Edit text box content. ([#51](https://github.com/ksnip/kImageAnnotator/issues/51))
* New: Add cmake uninstall target. ([#47](https://github.com/ksnip/kImageAnnotator/issues/47))
* New: Panning image by holding space or mouse middle button and dragging. ([#9](https://github.com/ksnip/kImageAnnotator/issues/9))
* New: Change annotation element config after drawing. ([#44](https://github.com/ksnip/kImageAnnotator/issues/44))
* Changed: Increase blur level so that large text is not visible. ([#62](https://github.com/ksnip/kImageAnnotator/issues/62))
* Changed: Crop widget updates shows via cursor if something is movable. ([#64](https://github.com/ksnip/kImageAnnotator/issues/64))
* Changed: Multi-tool buttons select current (last) tool on single click. ([#66](https://github.com/ksnip/kImageAnnotator/issues/66))
* Fixed: Ctrl Modifier stuck on second or third screenshot with Ctrl-N. ([#58](https://github.com/ksnip/kImageAnnotator/issues/58))
* Fixed: Unable to select number annotation when clicking on the number without background. ([#46](https://github.com/ksnip/kImageAnnotator/issues/46))
* Fixed: Undo/Redo is now disabled during crop and scale operation. ([#56](https://github.com/ksnip/kImageAnnotator/issues/56))
* Fixed: Mess with russian letters in text tool when typing in Russian. ([#59](https://github.com/ksnip/kImageAnnotator/issues/59))
* Fixed: Text tool does not allow me to type accents. ([#57](https://github.com/ksnip/kImageAnnotator/issues/57))
* Fixed: Highlighter rect and ellipse have only border but no fill. ([#65](https://github.com/ksnip/kImageAnnotator/issues/65))
* Fixed: Saved tool selection not loaded on startup. ([#67](https://github.com/ksnip/kImageAnnotator/issues/67))
* Fixed: On startup does not highlight tool, when this tool not the first item in the list. ([#63](https://github.com/ksnip/kImageAnnotator/issues/63))
* Fixed: Cursor image cannot be grabbed for moving. ([#69](https://github.com/ksnip/kImageAnnotator/issues/69))
* Fixed: Accents still not work in text tool on Linux. ([#61](https://github.com/ksnip/kImageAnnotator/issues/61))

## Release 0.1.0
* New: Double Arrow annotation tool. ([#23](https://github.com/ksnip/kImageAnnotator/issues/23))
* New: Marker Rectangle and Ellipse annotation tool. ([#26](https://github.com/ksnip/kImageAnnotator/issues/26))
* New: Add icons for dark theme. ([#37](https://github.com/ksnip/kImageAnnotator/issues/37))
* New: Add config option to setup blur radius. ([#25](https://github.com/ksnip/kImageAnnotator/issues/25))
* Changed: Blur tool is now preciser and fits the rect. ([#28](https://github.com/ksnip/kImageAnnotator/issues/28))
* Changed: Enter finishes text input and shift-enter adds new line in Text Tool. ([#30](https://github.com/ksnip/kImageAnnotator/issues/30))
* Changed: Text item draws border around the text when in text edit mode. ([#34](https://github.com/ksnip/kImageAnnotator/issues/34))
* Fixed: Double-click on annotation area causes SIGSEGV crash. ([#29](https://github.com/ksnip/kImageAnnotator/issues/29))
* Fixed: CAPS LOCK doesnt work on image editor. ([#27](https://github.com/ksnip/kImageAnnotator/issues/27))
* Fixed: Unable to select text item when clicking on text. ([#32](https://github.com/ksnip/kImageAnnotator/issues/32))
* Fixed: Some blurs get removed when losing focus. ([#35](https://github.com/ksnip/kImageAnnotator/issues/35))
* Fixed: Items cannot be resized when drawn from bottom right to top left. ([#38](https://github.com/ksnip/kImageAnnotator/issues/38))
* Fixed: Right click on annotation items selects item but doesn't switch tool. ([#40](https://github.com/ksnip/kImageAnnotator/issues/40))
* Fixed: Copy number annotation item doesn't increment number. ([#41](https://github.com/ksnip/kImageAnnotator/issues/41))
* Fixed: Crash on startup after adding Blur Radius Picker. ([#43](https://github.com/ksnip/kImageAnnotator/issues/43))

## Release 0.0.2
* New: Added blur annotation tool. ([#20](https://github.com/ksnip/kImageAnnotator/issues/20))
* New: Keep number tool sequence consecutive after deleting item. ([#7](https://github.com/ksnip/kImageAnnotator/issues/7))
* New: Added control for setting first number for numbering tool. ([#7](https://github.com/ksnip/kImageAnnotator/issues/7))
* New: Text and Number tool have now noBorderAndNoFill type. ([#22](https://github.com/ksnip/kImageAnnotator/issues/22))

## Release 0.0.1
* New: Initial release
