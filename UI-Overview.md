## plugdata UI overview:
![plugdata main window](screenshots/plugdata_main_interface_markup.png)

1. Main menu (including save / load) [see](UI-Overview.md#1-main-menu)
2. Undo / Redo action on current canvas
3. Add object menu
4. Mode selector: Edit / Run / Presentation
5. Activate plugin mode
6. Close right panel
7. Create new patch (tab)
8. Canvas / Patch tab
9. Palette selector
10. Canvas work area
11. Side panel
12. Center canvas view
13. Zoom to fit all objects into view
14. Overlay selector menu
15. Canvas object snapping menu
16. MIDI in/out activity indicator
17. Oversampling selector
18. Main volume control
19. Audio on/off (blue when on)
20. Limiter (protect output from high volume)

### 1) Main menu:
![main menu](screenshots/main_menu.png)

**New patch** Create new .pd patch

**Open patch...** Select .pd patch to open

**Recently opened** Menu shows recent patches

**Save patch** Save the currently selected patch

**Save patch as...** Save the current patch as

**Workspace** Menu allows saving current layout & state of plugdata

**Compile mode** Limits object selection & displays objects that can't be comipiled by the heavy compiler

**Compile** Compile and export current patch using heavy compiler

**Find externals...** Discover and install externals for PD (using deken)

**Setting...** Settings menu: Audio & MIDI, Themes, etc.

**About...** Show information and credits about the installed version of plugdata

### 3) Add object menu:

![add object menu](screenshots/add_object_menu.png)

Click and drag any object from this menu into the canvas. This menu shows a small usefull subset of objects, for access to all objects, click on the **Show Object Browser**

**Default objects** The first row of objects are default puredata objects, and are always displayed regardless of the selected category.

**Show Object Browser** will open up the **Object browser** which allows full access and searching of all available objects

**Pin** Will pin the object menu open while dragging and dropping new objects onto the canvas

**Category selector: UI, General, MIDI, IO, Osc~ etc...** Allows the user to change the objects that are displayed for drag and drop using easy to understand categories.

### 11) Add parameter panel:

![add parameter panel](screenshots/add_parameter_panel.png)

**Add new parameter** allows you to add new parameter automation to plugdata.
This is most useful when plugdata runs as a plugin in a host (such as a Digital Audio Workstation DAW).

Parameters are added with a default name, *param1,2,3 etc* which can be changed by double-clicking on the name area. :warning: Changing the name will not change the name at this point of any parameters already added to the canvas.

Parameters can added to any canvas by click and dragging over the name area, and dropping into a canavs of your choice.

Clicking the flippy triangle will expose the parameter settings, such as range and mode.

Hovering over the parameter will display a reorder and close icon. Click and drag the reorder icon to reposition the parameter in the list. Click close to remove the parameter from the list.

### 14) Overlay selector menu:

![overlay selector menu](screenshots/overlay_selector_menu.png)

This menu allows the user to turn on and off different overlays in the canvas.
Such as showing the canavs origin, or canvas border.
The menu is divided into different section, which each overlay relates to. Eg: Origin and Border are displays which relate to the canvas.

For each overlay item, they can be turned on/off for the mode that is currently selected. If the canvas is in edit mode (the pencil icon) then turning on the Origin's pencil icon will show the origin overlay in edit mode.

There is a universal control mode, shown as an eye icon. This allows you to turn on that item regardless of which mode the canvas is in.

:pushpin: The eye icon is able to be toggled **on** in the bottom menu (between Zoom to fit all, and Snapping options. :warning: Turning **on/off** the eye icon will override any other mode displays. Even if it is on for Edit & Run mode, if the eye icon is selected for that item, turning it off in the bottom menu will disable it.

### 15) Canvas object snapping menu:

![snapping menu](screenshots/snapping_menu.png)

This menu controls the way objects on the canvas snap to each other. The user can select from snapping to **Edges** or **Centers** of other objects on the canvas.

The option **Grid** allows the objects to snap to the canvas grid. The resolution of the canvas grid can also be changed from 5-30 pixels. Changing this value will also update the grid on the canvas, to reflect the size of the grid. :pushpin: this setting will change the resolution of all open patches.



