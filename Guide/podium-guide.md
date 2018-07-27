<div style="max-width: 45em; margin-left: auto; margin-right: auto;">

# <a name="podiumguide"></a>Podium Guide

Last updated: July 19, 2018  
Copyright © Zynewave  
[zynewave.com](https://zynewave.com/)

This guide is provided "as is" without any warranty of any kind. Zynewave and its contributors assume no responsibility or liability for any errors or inaccuracies that may appear in the guide.

* * *

#### Table Of Contents

[Guide Conventions](#toc.guideconventions)

[1. Quick Introduction](#toc.intro)
* [1.1. Start Page](#toc.intro.startpage)
* [1.2. New Project](#toc.intro.newproject)
* [1.3. The Arrangement Editor](#toc.intro.arrangement)
* [1.4. Setting Up Tracks](#toc.intro.tracks)
* [1.5. Recording](#toc.intro.recording)
* [1.6. Mixing](#toc.intro.mixing)
* [1.7. Automating Parameters](#toc.intro.automation)
* [1.8. Exporting To Sound File](#toc.intro.export)

[2. Projects](#toc.projects)
* [2.1. Project Properties](#toc.projectproperties)
* [2.2. Project Files](#toc.projectfiles)
* [2.3. Project Templates](#toc.projectemplates)
* [2.4. Project Window](#toc.projectwindow)
  * [2.4.1. Podium Menu](#toc.podiummenu)
  * [2.4.2. Setup Menu](#toc.setupmenu)
  * [2.4.3. Window Menu](#toc.windowmenu)
  * [2.4.4. Tab Bar](#toc.tabbar)
  * [2.4.6. Drag and Drop](#toc.draganddrop)
  * [2.4.7. Stickie Notes](#toc.stickienotes)
* [2.5. Start Page](#toc.startpage)
  * [2.5.1. File Menu](#toc.start.filemenu)
  * [2.5.2. View Menu](#toc.start.viewmenu)
* [2.6. Project Page](#toc.projectpage)
  * [2.6.1. New Project Panel](#toc.newprojectpanel)
  * [2.6.1. File Menu](#toc.project.filemenu)
  * [2.6.1. Project Info Panel](#toc.projectinfopanel)
  * [2.6.2. Recent Projects Panel](#toc.recentprojectspanel)
  * [2.6.3. Content Panel](#toc.contentpanel)
  * [2.6.4. Content Menu](#toc.contentmenu)
  * [2.6.5. Content List Menu](#toc.contentlistmenu)
  * [2.6.6. Device Panel](#toc.devicepanel)
  * [2.6.7. Device Menu](#toc.devicemenu)
  * [2.6.8. Device List Menu](#toc.devicelistmenu)
  * [2.6.9. Import Hardware Definition](#toc.importhardwaredefinition)
* [2.7. Inspector Page](#toc.inspectorpage)
* [2.8. Browser Page](#toc.browserpage)
  * [2.8.1. Browser Options Menu](#toc.browseroptionsmenu)
  * [2.8.2. Object Browser](#toc.objectbrowser)
  * [2.8.3. Object Browser Menu](#toc.objectbrowsermenu)
  * [2.8.4. Object List](#toc.objectlist)
  * [2.8.5. File Browser](#toc.filebrowser)
  * [2.8.6. File Browser Menu](#toc.filebrowsermenu)
  * [2.8.7. File List](#toc.filelist)
* [2.9. Help Page](#toc.helppage)

[3. Devices](#toc.devices)
* [3.1. Hardware Devices](#toc.hardwaredevices)
* [3.2. Plugins](#toc.plugins)
* [3.3. Multitimbral and Multiple IO Plugins](#toc.multitimbralplugins)
* [3.4. ReWire Devices](#toc.rewiredevices)
* [3.5. Device Mappings](#toc.devicemappings)
  * [3.5.1. Device Mapping Properties](#toc.devicemappingproperties)
* [3.6. Device Definitions](#toc.devicedefinitions)
  * [3.6.1. Device Definition Properties](#toc.devicedefinitionproperties)
  * [3.6.2. Creating Library Files](#toc.creatinglibraryfiles)
* [3.7. Presets](#toc.presets)
  * [3.7.1. Program Preset Properties](#toc.programpresetproperties)
  * [3.7.2. Library Preset Properties](#toc.librarypresetproperties)
* [3.8. Parameters](#toc.parameters)
  * [3.8.1. Parameter Properties](#toc.parameterproperties)
  * [3.8.2. System Exclusive Messages](#toc.systemexclusivemessages)
* [3.9. Folder Properties](#toc.folderproperties)

[4. Editors](#toc.editors)
* [4.1. Timeline](#toc.timeline)
* [4.2. Selection](#toc.selection)
* [4.3. Clipboard](#toc.clipboard)
* [4.4. Edit History](#toc.edithistory)
* [4.5. Toolbars](#toc.toolbars)
  * [4.5.1. Edit Toolbar](#toc.edittoolbar)
  * [4.5.2. Track Toolbar](#toc.tracktoolbar)
  * [4.5.3. Editor Profile Toolbar](#toc.editorprofiletoolbar)
  * [4.5.4. Transport Toolbar](#toc.transporttoolbar)
  * [4.5.5. Additional Toolbar Elements](#toc.additionaltoolbar)
* [4.6. Editor Menus](#toc.editormenus)
  * [4.6.1. File Menu](#toc.editorfilemenu)
  * [4.6.2. Track Menu](#toc.editortrackmenu)
  * [4.6.3. Edit Menu](#toc.editoreditmenu)
  * [4.6.4. View Menu](#toc.editorviewmenu)
  * [4.6.5. Grid and Snap Menu](#toc.gridandsnapmenu)
  * [4.6.6. Marker Menu](#toc.markermenu)
  * [4.6.7. Tempo Menu](#toc.tempomenu)
* [4.7. Sliding and Zooming](#toc.slidingzooming)
  * [4.7.1. Navigator](#toc.navigator)
  * [4.7.2. Scrollbars](#toc.scrollbars)
  * [4.7.3. Slide/Zoom Tools](#toc.slidezoomtools)
  * [4.7.4. Slide/Zoom Key Shortcuts](#toc.slidezoomkeyshortcuts)
* [4.8. Arrangement](#toc.arrangement)
  * [4.8.1. Arrangement Properties](#toc.arrangementproperties)
  * [4.8.2. Arrangement Editor](#toc.arrangementeditor)
  * [4.8.3. Marker Properties](#toc.markers)
  * [4.8.4. Time Signature, Tempo and Scale](#toc.timesigtemposcale)
  * [4.8.5. Track Tags](#toc.tracktags)
* [4.9. Sound](#toc.sound)
  * [4.9.1. Sound Properties](#toc.soundproperties)
  * [4.9.2. Sound Editor](#toc.soundeditor)
  * [4.9.3. Export to Sound File](#toc.exportsoundfile)
* [4.10. Note Sequence](#toc.notesequence)
  * [4.10.1. Note Editor](#toc.noteeditor)
  * [4.10.2. Piano Roll and Drum Map](#toc.pianorolldrummap)
  * [4.10.3. Editing Note Events](#toc.editingnoteevents)
  * [4.10.4. Note Event Hotspots](#toc.noteeventhotspots)
  * [4.10.5. Velocity Region](#toc.editingvelocity)
  * [4.10.6. Note Map](#toc.notemap)
* [4.11. Curve Sequence](#toc.curvesequence)
  * [4.11.1. Curve Editor](#toc.curveeditor)
  * [4.11.2. Splines](#toc.splines)
* [4.12. Edit Actions](#toc.editactions)
  * [4.12.1. Adjust Timing](#toc.adjusttiming)
  * [4.12.2. Adjust Sound Events](#toc.adjustsoundevents)
  * [4.12.3. Adjust Transposition](#toc.adjusttransposition)
  * [4.12.4. Adjust Velocities](#toc.adjustvelocities)
  * [4.12.5. Adjust Points](#toc.adjustpoints)
  * [4.12.6. Beat Slice](#toc.beatslice)

[5. Tracks](#toc.tracks)
* [5.1. Track Hierarchy](#toc.trackhierarchy)
* [5.2. Track Controls](#toc.trackcontrols)
* [5.3. Track Properties](#toc.trackproperties)
* [5.4. Track Templates](#toc.tracktemplates)
* [5.5. Track Inspector](#toc.trackinspector)
  * [5.5.1. Inspector Options Menu](#toc.inspectoroptionsmenu)
  * [5.5.2. Color Picker](#toc.colorpicker)
  * [5.5.3. Rack](#toc.rack)
  * [5.5.4. Track Panel](#toc.trackpanel)
  * [5.5.5. Device Panel](#toc.devicepanel)
  * [5.5.6. Preset Panel](#toc.presetpanel)
  * [5.5.7. Parameter Panel](#toc.parameterpanel)
  * [5.5.8. Input Panel](#toc.inputpanel)
* [5.6. Using Presets](#toc.usingpresets)
  * [5.6.1. Creating Plugin Library Presets](#toc.creatingpluginpresets)
  * [5.6.2. Creating SysEx Library Presets](#toc.creatingsysexpresets)

[6. Arranging](#toc.arranging)
* [6.1. Sequence Events](#toc.sequenceevents)
  * [6.1.1. Gain, Fade-In/Out and Crossfades](#toc.gainandfades)
  * [6.1.2. Time-Stretching](#toc.timestretching)
  * [6.1.3. Sound Event Properties](#toc.soundeventproperties)
* [6.2. Parameter Automation](#toc.parameterautomation)
  * [6.2.1. Mixer Faders](#toc.mixerfaders)
  * [6.2.2. Recording Automation](#toc.recordingautomation)
  * [6.2.3. Editing Automation](#toc.editingautomation)
  * [6.2.4. Parameter Event Automation](#toc.parametereventautomation)
* [6.3. Mixing](#toc.mixing)
  * [6.3.1. Mixer Options Menu](#toc.mixeroptionsmenu)
  * [6.3.2. Fader and Meter Grid](#toc.faderandmetergrid)
  * [6.3.3. Embedded Plugin Editors](#toc.embeddedplugineditors)
  * [6.3.4. Busses](#toc.busses)
  * [6.3.5. Levels](#toc.levels)
* [6.4. Recording](#toc.recording)
  * [6.4.1. Punch Mode](#toc.punchmode)
  * [6.4.2. Multi-Take Recording and Compositing](#toc.multitakerecording)
  * [6.4.3. Recording MIDI Parameters](#toc.recordingmidiparameters)

[7. Setup](#toc.setup)
* [7.1. Setup Files](#toc.setupfiles)
* [7.2. Interfaces](#toc.interfaces)
  * [7.2.1. Audio I/O](#toc.interfaces.audio)
  * [7.2.2. MIDI I/O](#toc.interfaces.midi)
  * [7.2.3. Control Surfaces](#toc.interfaces.controlsurfaces)
  * [7.2.4. Report](#toc.interfaces.report)
* [7.3. Preferences](#toc.preferences)
  * [7.3.1. Projects](#toc.preferences.projects)
  * [7.3.2. Engine](#toc.preferences.engine)
  * [7.3.3. Play/Record](#toc.preferences.playrecord)
  * [7.3.4. Metronome](#toc.preferences.metronome)
  * [7.3.5. Plugins](#toc.preferences.plugins)
  * [7.3.6. Editors](#toc.preferences.editors)
  * [7.3.7. Appearance](#toc.preferences.appearance)
  * [7.3.8. About 64-Bit Mixing](#toc.preferences.about64bit)
* [7.4. Colors](#toc.colors)
  * [7.4.1. Surface and Text Colors](#toc.colors.surfaceandtext)
  * [7.4.2. Indicator and Highlight Colors](#toc.colors.indicatorsandhighlight)
  * [7.4.3. Track Colors](#toc.colors.track)
  * [7.4.4. Color Setups](#toc.colorsetups)
* [7.5. Favorite Folders](#toc.favoritefolders)
* [7.6. Editor Profiles](#toc.editorprofiles)
  * [7.6.1. Space Region Properties](#toc.spaceregion)
  * [7.6.2. Toolbar Region Properties](#toc.toolbarregion)
  * [7.6.3. Timeline Ruler Region Properties](#toc.timelinerulerregion)
  * [7.6.4. Navigator Region Properties](#toc.navigatorregion)
  * [7.6.5. Scrollbar Region Properties](#toc.scrollbarregion)
  * [7.6.6. Format Region Properties](#toc.formatregion)
  * [7.6.7. Tracks Region Properties](#toc.tracksregion)
  * [7.6.8. Embedded Editor Region Properties](#toc.embeddededitorregion)
  * [7.6.9. Mixer Region Properties](#toc.mixerregion)
  * [7.6.10. Notes Region Properties](#toc.notesregion)
  * [7.6.11. Velocity Region Properties](#toc.velocityregion)
  * [7.6.12. Curve Region Properties](#toc.curveregion)
  * [7.6.13. Channels Region Properties](#toc.channelsregion)
  * [7.6.14. Event List Region Properties](#toc.eventlistregion)
* [7.7. Windows](#toc.windows)
  * [7.7.1. Screens](#toc.screens)

[8. Control Surfaces](#toc.controlsurfaces)
* [8.1. Configuration](#toc.controlsurfaceconfiguration)
* [8.2. Mixer Integration](#toc.mixerintegration)
* [8.3. Mackie Control](#toc.mackiecontrol)
  * [8.3.1. Help Mode](#toc.mackiehelpmode)
  * [8.3.2. Keyboard Simulation](#toc.mackiekeyboardsimulation)
  * [8.3.3. Arrangement Selection Mode](#toc.mackiearrangementmode)
  * [8.3.4. Mixer Mode](#toc.mackiemixermode)

[9. zPlugins](#toc.zplugins)
* [9.1. zPEQ](#toc.zpeq)
* [9.2. zPitch](#toc.zpitch)
* [9.3. zReverb](#toc.zreverb)

[Appendix A: Podium Key Shortcuts](#toc.keyshortcuts)

[Appendix B: Text Translations](#toc.texttranslations)

* * *

# <a name="toc.guideconventions"></a>Guide Conventions

These are some of the conventions and formatting used to keep the guide layout consistent.

#### Highlighting

*   GUI elements are written in bold, with capitalization as in the GUI. The element type is written in lowercase and not bold. Example: **View** menu.
*   UI elements that are not named in the GUI use lowercase and not bold. Example: track inspector, mixer region.
*   Links within the guide are lowercase, unless they refer to a named GUI element.
*   _Note:_ is written at the start of a paragraph to emphasize important information.
*   _Tip:_ is written at the start of a paragraph to offer shortcuts or other time-saving hints.
*   Double quotes are used for file paths.
*   Single quotes are used for concepts.

#### Spelling/Choice of Words

*   American English.
*   Chapter and section headings are prefixed with serial numbers. Numbering of sections within chapters or parent sections appends another serial number separated by a period. Example: 2.4.7.
*   "Chapter" refers to all sections within the chapter.
*   “Section" refers to a specific numbered section within a chapter.
*   "For example" and "that is" are used instead of e.g. and i.e.
*   plugin (not plug-in).
*   child track (not subtrack).
*   subfolder (not sub folder).

#### Navigation

*   "Click" is used with buttons in the GUI, and "press" with keys on the keyboard.
*   Mouse actions: double-click, right-click, Ctrl+click, Shift+click, Alt+click, Ctrl+drag, Shift+drag, Alt+drag.

#### Screenshots

*   Screenshots of the Podium UI uses the “Paper” Podium color setup.
*   Screenshots of dialog boxes uses the default Windows 7 Aero theme.

* * *

# <a name="toc.intro"></a>1. Quick Introduction

This introduction will take you through the basic steps of creating a new project, working on an arrangement, using instrument and effect plugins, recording audio and MIDI inputs, automating parameters, and exporting the final result as a sound file.

## <a name="toc.intro.startpage"></a>1.1. Start Page

![](images/intro_start_page.png)

The first time you start Podium the main window will show the Start page and the Help page. If this is not the first time you have used Podium, then you may want to use the **Restore Default Setup** command in the **Setup** menu to revert the setup back to its default state.

The help page provides a quick way to learn about the Podium features as it will show context help for the element that you point to with the mouse cursor. You can toggle the help page by clicking the **Help** tab at the top or by pressing F1.

The Start page will initially only show the **New Project** tile. As you create new projects these will appear as tiles on the Start page for quick loading. The tiles will either show a screenshot of the last saved state of the project, or show any image files you may have copied into the project folder.

You can have up to 10 projects open simultaneously. You access the page for an opened project by clicking its tab next to the Start page tab. You can close a project with the **File** menu on the project page.

Click the **New Project** tile to open a new project page.

## <a name="toc.intro.newproject"></a>1.2. New Project

![](images/intro_new_project.png)

Before the actual project file is created you are presented with the **New Project** panel where you can specify basic information about the project. For this quick introduction do the following steps:

Click the **Edit project name** button to open the **[Project Properties](#toc.projectproperties)** dialog, enter a name for your project and click OK. The **File path** field shows where the project file will be saved once the project is created.

The first time you create a project you will need to configure your audio and MIDI interfaces and your VST plugin folders. These configurations are stored in the Podium setup folder and will be remembered the next time you create a new project. Only if you have made changes to your interfaces and plugin installations will you then need to change these settings.

Click the **Configure audio** button to open the **Audio I/O** page in the **[Interfaces](#toc.interfaces.audio)** dialog. It is highly recommended that you select an ASIO audio driver to get the best low-latency performance. If your audio interface does not come with a dedicated ASIO driver, you can install the ASIO4ALL driver, which is available as a free download from [asio4all.org](http://asio4all.org/) website. Click OK to apply the changes. The **Enabled audio inputs** and **Enabled audio outputs** fields display the currently active audio interface and audio channels.

Click the **Configure MIDI** button to open the **MIDI I/O** page in the **Interfaces** dialog, and select the checkbox next to any MIDI interfaces you want to use with Podium.

If the plugin option selector is set to **Build and load plugin database** the project creation will perform a VST plugin scan and build a plugin database. The **VST plugin scan folders** field shows all configured VST plugin folders. If Podium hasn't automatically detected all your plugin folders, then click the **Configure plugin folders** button to open the **Plugins** page in the **[Preferences](#toc.preferences.plugins)** dialog. Here you can browse for the folders where you have installed your VST plugins. You only need to specify the main plugin folder. Podium will automatically scan any subfolders.

Click the **Create project** button.

If you selected to build or update the plugin database, Podium will now show the **Updating Plugin Database** progress dialog and start to scan for VST plugins. This can take several minutes depending on how many plugins you have installed.

When Podium scans a plugin it will load the plugin to examine its capabilities. This means that the plugin can cause Podium to crash. Should this happen, then the next time you start Podium you will see a dialog informing you that the crashing plugin has been put on the quarantine list. Plugin scanning will skip plugins that are on the quarantine list. You may need to repeat the project creation a few times until the plugin scanning finishes without encountering further crashing plugins.

When the plugin scanning has completed, the project file is saved and the arrangement editor is opened.

## <a name="toc.intro.arrangement"></a>1.3. The Arrangement Editor

![](images/intro_arrangement.png)

The default layout of the arrangement editor shows from top to bottom: Edit toolbar, navigator, timeline ruler, marker region, tempo/time signature region, track toolbar, tracks region, editor profile toolbar and transport toolbar.

The layout and edit options of an editor are defined by an editor profile. The Podium default setup includes a set of profiles that are designed for different purposes such as editing and mixing. You can quickly switch between these by clicking the buttons in the editor profile toolbar. The [editor profiles](#toc.editorprofiles) chapter has more information on how you can customize the editor profiles.

The navigator will show a miniature of all the events that are placed on the timeline. The navigator will be useful for keeping an overview of the entire timeline, and it will allow you to quickly zoom in on the areas you want to work on.

The arrangement is by default created with only a master track. There are several ways that you can add new tracks:

*   Left-click or right-click the **+** button in the track toolbar.
*   Double-click or right-click the empty area below the last track header.
*   Drag an input or device object from the inspector or from other track headers, and drop the object on the empty area below the last track header.
*   Click the **Track** menu button or right-click the background of a track header to access the **Insert New Track** command.

You can use the track menu to manage your tracks, but in many situations it will be easier to use the [track inspector](#toc.trackinspector). Click the **Inspector** tab at the top left corner to toggle the track inspector. The inspector will show the properties of the highlighted focus track.

## <a name="toc.intro.tracks"></a>1.4. Setting Up Tracks

![](images/intro_tracks.png)

Let's start by setting up a track for audio recording:

Click the **+** button in the track toolbar to create a new track. Name the track and click OK to close the dialog. Click the inspector **[Input](#toc.inputpanel)** panel header, or press F6, to open the list of available inputs. Open the **Audio Inputs** folder and double-click on an input to assign it to the track. You can also drag an input from the list onto the track header.

When an audio input is assigned to a track, it is "live", meaning that what is received on the input will be routed through the track and eventually out to the master output. You can disable the input by clicking the **X** bypass button located next to the input on the track.

Next, let's set up a track for playing an instrument plugin:

Create the track and then click the inspector **[Device](#toc.devicepanel)** panel header, or press F3, to open the list of available devices. This list shows all the VST plugins that were found when the project was created. If you had any VST instrument plugins installed, double click on one to assign it to the track, or drag it from the list onto the track header.

By default the arrangement is configured to auto-assign the first available MIDI input to the focus track. So if you have a MIDI keyboard connected, you should now be able to play the instrument plugin. Alternatively you can assign a MIDI input similar to how you assigned an audio input.

Click the plugin selector on the track header to open/close the plugin editor. Click the inspector **[Preset](#toc.presetpanel)** panel header, or press F4, to show the list of presets that are available in the plugin. Double-click a preset to change to that preset in the plugin.

The inspector device list can also be used when you want to add effect plugins to tracks. Either double-click an effect plugin to add it to the focus track effect chain, or drag the effect to any of the track headers.

## <a name="toc.intro.recording"></a>1.5. Recording

![](images/intro_recording.png)

The arrangement defaults to a time signature of 4/4 and a tempo of 120 BPM. To adjust this, double-click the [tempo event](#toc.timesigtemposcale) in the tempo region or double-click the tempo indicator in the transport toolbar.

The tracks you want to record should have audio or MIDI inputs assigned, as explained in the previous section. Click the **R** button on the track headers to arm them for recording. Click the record button on the transport toolbar to enable recording mode. The record armed tracks will be highlighted with red color in the range that will be recorded. Click the metronome button if you want an audible click synced to the tempo and time signature of the arrangement. Click the play button on the transport toolbar to start the recording.

You can limit the time range that is recorded by using punch in/out. To do so, click the punch in/out buttons on the transport toolbar, and then drag the handles of the red bar that has appeared in the timeline ruler.

Once you are done with recording a track, deselect the track **R** button to avoid erasing the recorded events the next time you start recording. If you want to record new tracks from the same input, just drag the input onto another track or onto the blank area below the last track. When done recording, either remove the input with the track menu or bypass the input by clicking the **X** button next to the input.

The sequences and sounds that you have recorded on the tracks can be edited in separate editors. Click the **Editor** button on the editor profile toolbar. This profile has an embedded editor that will automatically show the currently selected track event. You can resize the editor by dragging its title bar. Alternatively you can also double-click a track event to open a separate editor window.

## <a name="toc.intro.mixing"></a>1.6. Mixing

![](images/intro_mixing.png)

Click the **Mixer** button in the editor profile toolbar. The mixer can be useful for precision level metering and quick access to various track controls. The horizontal track lanes in the tracks region are mirrored as vertical strips in the mixer.

Let's add effects to our audio tracks using the selectors on the mixer strips: Click the **+** button on a strip to open a menu with available devices. Select the [zPEQ](#toc.zpeq) effect from the Zynewave Effects submenu. You should now see an embedded EQ editor in the mixer strip. Read the context help for this editor to see how you can edit the EQ curve.

After inserting an effect, you'll notice that the effect is added below the **+** button. This brings us to an important principle in Podium: The signal flow follows the visual layout of the track hierarchy. Audio starts at the bottom of the track hierarchy and flows up through the effect chain on the track, continuing up through effect chains on group tracks and the master track, until it arrives at the master output at the top of the master track.

Next, let's add a mixer bus. A bus allows you to extract audio from one or more tracks using a bus send, and then inject the mixed bus output to one or more tracks using a bus return.

Click the **+** button on a track and select Send 1 from the Busses submenu. A message box will appear asking if you want to create a matching bus return track. Click **Yes**. Notice that the bus send is added above the **+** button. This is because bus sends are typically applied as the last step in the effect chain. Insert the [zReverb](#toc.zreverb) effect on the Return 1 track, and then turn up the Send 1 sliders to send audio to the reverb.

The bus send sliders will control the level of the signal that is sent to the busses. The gain fader on the track will control the level of the signal going out of the track. Adjusting the send level will not affect the gain level. Adjusting the gain level will by default affect the send level, but this can be changed in the **Fader** submenu of the **Track** menu.

## <a name="toc.intro.automation"></a>1.7. Automating Parameters

![](images/intro_automation.png)

If you have recorded a note sequence with your MIDI keyboard, you may already have recorded MIDI parameter tracks for pitch bend, aftertouch or modulation. You can also record parameter tracks for adjustments you make to controls in the plugin editor during recording. To enable this, the track with the plugin must be record armed.

To manually create parameter tracks:

Click the inspector **[Param](#toc.parameterpanel)** panel header, or press F5, to show the list of parameters that can be automated for the focus track. If a device is assigned to the track you will see **Mixer** and **Device** buttons. Mixer parameters include **Level**, **Pan** and **Send**. These control the Podium mixer. The list of device parameters will depend on the device that is assigned on the track. This can be both MIDI parameters and VST parameters. Double-click a parameter to create a parameter track. Double-click on the parameter track timeline to add a curve sequence event.

[Curve sequences](#toc.curvesequence) can be edited both with the [curve editor](#toc.curveeditor) and with the mixer. The mixer strip for a parameter track has a slider that shows the value of the curve sequence at the play cursor position. Dragging the slider while playback is stopped will create a sharp curve change. Dragging during playback will create a smooth curve change.

## <a name="toc.intro.export"></a>1.8. Exporting To Sound File

![](images/intro_exporting.png)

At some point you may want to export the audio output of your arrangement to a sound file. To do this you use the bounce feature.

Select the master track and press the **B** key shortcut or select the **Render** command in the **Bounce** submenu of the **Track** menu. A progress dialog will appear. Once the render is done, a highlighted **B** button appears on the master track and the waveform of the bounced audio is drawn as an overlay on the master track. This indicates that the track is now set to play the bounced audio, and subsequently all child tracks are muted. Clicking the **B** button again will deactivate the bounced audio and reenable all the child tracks.

This method of bouncing does not only apply to the master track. You can bounce enable any group or individual audio track. If you keep adding tracks with instrument and effect plugins you may eventually run out of CPU resources during playback. The CPU indicator in the transport toolbar will indicate how much of the available CPU power is being used. When the CPU usage overloads you will hear drop-outs in the sound. You can bounce a track to free up the CPU resources used by the plugins on that track.

The bounced audio will be rendered to the end of the arrangement, which is the point on the timeline where the last event is placed. In some cases you may want to extend the bounced audio, for example to capture the decay of a reverb effect. In that case you can extend the arrangement by placing a [marker](#toc.markers) at the point on the timeline where you want the bounced audio to stop. Double click on the marker timeline region (above the tempo region) to place a marker. Then redo the bounce render.

When you finally are happy with the master track bounce, select the **[Export to Sound File](#toc.exportsoundfile)** command in the **File** menu. This will show a dialog where you can specify the bit resolution of the exported file. Some external tools such as mp3 encoders may only support sound files saved with 16-bit resolution. Click the **Export** button to show the save file dialog.

* * *

# <a name="toc.projects"></a>2. Projects

A project consists of different types of objects that are organized in a hierarchic folder structure similar to a file system. At the top of the hierarchy is the project object itself.

The objects in a project can be grouped into two categories:

*   Arrangements, sounds, note sequences and curve sequences are objects that have a timeline. A project can contain any number of these objects, so you can for example have a collection of arrangements within a single project.
*   Device mappings, device definitions, presets and parameters are objects that define your audio and MIDI interfaces, mixer busses, external devices and software plugins. You use these device objects to interact with the devices in the arrangement editor.

In addition to these objects, you also have the folder object. Device objects are grouped into a set of default folders. You can create additional folders, to for example sort your plugins into categories. Plugin folders will be presented as submenus when you open plugin selector menus in the editors.

Any type of object can act as a folder. For example, any sounds and sequences you create while working in an arrangement editor will be inserted in the project as child objects of the arrangement object.

The [project page](#toc.projectpage) presents an overview of the objects in the project. The project page can be used to manage the project content and device setup. The objects can also be browsed and edited directly using the [object browser](#toc.objectbrowser). Use caution and keep a backup of your project if you intend to edit the objects directly. Messing with the device objects can cause the devices not to respond as expected in arrangements.

## <a name="toc.projectproperties"></a>2.1. [](#dialog.project)Project Properties

![](images/dialog_project.png)

The **Project Properties** dialog is opened by selecting **Project Properties** in the **File** menu or by clicking the **...** button on the project page toolbar.

*   **Project name**: As long as the project is not yet saved to file, you can change the project name in this edit field. Once the project is saved, the project name will automatically be set to the saved filename. Renaming the project file will thus change the project name. The project name is shown on the project page tab at the top of the project window.
*   **File path**: If the project has been saved, this field shows the full file path of the project file.
*   **Project window image file**: If an image file is specified, it will be painted as wallpaper on the project page. If the image is smaller than the page, it will be tiled to fill the entire page. Use the **...** button to open a file dialog for selecting an image file. You can also drag and drop image files from a Windows file explorer onto the Podium project window to set the wallpaper image.
*   **Track timeline image file**: If an image file is specified, it will be painted as wallpaper on the tracks timeline area in arrangement editors.
*   **Track image opacity**: A value lower than 100% will draw the image blended with the timeline fill color of the current color setup.
*   **Dye track image with timeline fill color**: This option combined with the opacity setting can help tone down the image and make it blend in with your current Podium color setup.

The specified image files are stored as file references in the project file. If the image files are located in the folder or a subfolder of where the project file is saved, the image file references are stored with a file path relative to the project folder. This ensures that the image files still can be loaded with the project if you later on move or rename the project folder.

## <a name="toc.projectfiles"></a>2.2. Project Files

A project is saved to a single file with the filename extension .pod. Each sound object in the project is saved to a separate sound file. The project file only stores the file path to the sound file.

The **File** menu **Save Project** command will only save the project file and not any sound files. Use the **Save All Changes** command on the Start page **File** menu to save all modified project and sound files for all currently opened projects. To save a single sound, use the **File** menu in the sound editor.

When a project is created with the **New Project** page, Podium will create a project folder with the same name as the project. This project folder is created in the **New projects folder** as specified in **Preferences**. The project file will be saved inside the project folder. Any sounds you have created in the project will be saved in the project folder as well. The sound files will be saved in subfolders according to their folder placement in the project. For example, sounds recorded in an arrangement will be saved in a subfolder with the same name as the arrangement.

The **Project Properties** dialog has a field that shows the full file path for the project file.

## <a name="toc.projectemplates"></a>2.3. Project Templates

Project templates can be used for two purposes:

*   You can select a project template in the **Project option** selector menu on the **New Project** page. Selecting a template will hide the options for plugins and arrangements, as they are already configured in the template. As an example, you could have templates for studio recording, live recording, mastering, rock, orchestral, etc.
*   You can change the plugin setup in an existing project with the **Load Plugin Setup from Template** submenu of the **Device** menu on the project page. As an example, you could have templates where the plugins are sorted by plugin developer or by plugin category.

When you have created a project that you want to use as a project template, you save the template with the **Save Project as Template** command in the **File** menu. This will open the **New Project Template** dialog where you can enter a name for the template.

![](images/dialog_new_project_template.png)

The project template file is saved in the **Project template library folder** as specified in **Preferences**. If a template file already exists with the name you entered, Podium will ask if you want to overwrite it.

You can organize your template files with a Windows file explorer. You can rename or delete template files, or organize the files into subfolders. Template subfolders are shown as submenus when you open a menu that lists the project templates. After you have reorganized files in the template folder you need to restart Podium to update the template list shown in the Podium menus.

## <a name="toc.projectwindow"></a>2.4. [](#app.page)Project Window

![](images/window_project.png)

The main Podium application window is a project window. Additional project windows can be opened with the **New Project Window** command in the **Window** menu.

#### Menu Bar

If you maximize a project window, the standard Windows border is removed and the project window is shown full-screen. When maximized, the menu bar will include the following additional buttons:

*   [](#app.menubarautohide)**Auto-hide menu bar**: Toggles the menu bar auto-hide mode. When auto-hide is enabled the menu bar will disappear when the mouse cursor is moved away from the menu bar. The menu bar can be shown again by moving the mouse cursor to the top of the screen and holding it there for half a second.
*   [](#app.minimize)**Minimize**: Minimizes the window.
*   [](#app.restore)**Restore**: Restores the window to its size before it was maximized.
*   [](#app.close)**Close**: Closes the window if it is a project window. If the window is the main application window the app will exit. If there are unsaved changes you will be prompted to save changes.

#### Tab Bar

The project window contains a set of embedded pages that can be shown and hidden by clicking the tabs at the top of the window. The pages can be resized by dragging the space between the pages. You have the option to open the pages in separate windows, but using the embedded pages can often be more convenient.

*   [](#app.inspectortab)**Inspector**: Toggles the inspector. Shortcut keys are F2 to F6.
*   [](#app.browsertab)**Browser**: Toggles the browser. Shortcut key is F7.
*   [](#app.starttab)**Start Page**: Shows the Start page.
*   [](#app.projecttab)**Project Page**: Shows the project page.
*   [](#app.helptab)**Help**: Toggles the help page. Shortcut key is F1.

### <a name="toc.podiummenu"></a>2.4.1. [](#app.podiummenu)Podium Menu

Press Alt+P to open the [](#app.podiummenu.label)**Podium** menu.

*   [](#cmd.podium.about)**&About {}**: Shows a dialog with version and copyright information. The braces will contain either **Podium**, **Podium Free** or **Podium Demo**, depending on which version you are running.
*   [](#cmd.podium.guide)**Podium &Guide**: Opens the Podium guide document that was installed with the Podium application.
*   [](#cmd.podium.keyshortcuts)**Key Shortcuts**: Opens the key shortcuts section in the Podium guide document.
*   [](#cmd.podium.releasehistory)**Release History**: Opens the Podium release history document.
*   [](#cmd.podium.wwwzynewave)**Zynewave Website**: Opens the Zynewave website in a web browser.
*   [](#cmd.podium.wwwcommunity)**Zynewave User Community**: Opens the user community page on the Zynewave website.
*   [](#cmd.podium.wwwyoutube)**Zynewave YouTube Channel**: Opens the Zynewave video channel on the YouTube website.
*   [](#cmd.podium.exit)**E&xit...**: Exits the Podium application. If there are any open project and sounds with unsaved changes you will be prompted if you want to save before exiting.

### <a name="toc.setupmenu"></a>2.4.2. [](#app.setupmenu)Setup Menu

Press Alt+S to open the [](#app.setupmenu.label)**Setup** menu.

*   [](#cmd.setup.resetmidi)**&Reset MIDI Devices**: Sends note and controller reset messages to all connected external MIDI devices. Use this to stop notes which may have become stuck due to glitches in the MIDI communication.
*   [](#cmd.setup.interfaces)**&Interfaces...**: Opens the **[Interfaces](#toc.interfaces)** dialog.
*   [](#cmd.setup.preferences)**&Preferences...**: Opens the **[Preferences](#toc.preferences)** dialog where you configure global application options.
*   [](#cmd.setup.colors)**&Colors...**: Opens the **[Colors](#toc.colors)** dialog where you configure all the color settings that are saved to color setup files.
*   [](#cmd.setup.favorites)**&Favorite Folders...**: Opens the **[Favorite Folders](#toc.favoritefolders)** dialog where you configure the folders that will appear as favorite shortcuts in the Podium browsers.
*   [](#cmd.setup.profiles)**&Editor Profiles...**: Opens the **[Editor Profiles](#toc.editorprofiles)** dialog where you configure all the different types of editor profiles.
*   [](#cmd.setup.windows)**&Windows...**: Opens the **[Windows](#toc.windows)** dialog where you can manage all created windows and their assignment to different virtual screens.
*   [](#cmd.setup.restoredefault)**Restore &Default Setup**: Deletes the current setup and replaces it with the default setup.
*   [](#cmd.setup.restoredefaultprofiles)**Restore Default Editor Profiles**: Replaces the current editor profiles with the editor profiles from the default setup.
*   [](#cmd.setup.loadcolor)**Load Color Setup**: Submenu with shortcuts to all the color setup files.
*   [](#cmd.setup.savecolor)**Save Color Setup...**: Opens a file dialog where you can save the current color setup to a [color setup file](#toc.colorsetups). The files you save will appear in the **Load Color Setup** submenu.
*   [](#cmd.setup.load)**&Load Setup...**: Opens a file dialog where you can load a setup file you previously saved. Alternatively you can also drag and drop setup files on a project window.
*   [](#cmd.setup.save)**&Save Setup...**: Opens a file dialog where you can save a backup of the current setup.
*   [](#cmd.setup.exploresetupfolder)**Explore Setup Folder**: Opens a Windows file explorer for the setup folder.

### <a name="toc.windowmenu"></a>2.4.3. [](#app.windowmenu)Window Menu

Press Alt+W to open the [](#app.windowmenu.label)**Window** menu.

*   [](#cmd.window.projectwindow)**New &Project Window**: Opens a new [project window](#toc.projectwindow). Having multiple project windows open allows you to for example view different parts of your project at the same time or view the same arrangement with different profiles and zoom settings.
*   [](#cmd.window.linkprojectwindows)**&Link Project Windows**: Links page navigation in all open project windows. Navigating for example into an arrangement in one project window will automatically open the arrangement in the other project windows as well. Each project window remembers the last used editor profile, so one window can be set to show a tracks profile and the other a mixer profile.
*   [](#cmd.window.inspectorwindow)**New &Inspector Window**: Opens a new [track inspector](#toc.trackinspector) window.
*   [](#cmd.window.browserwindow)**New &Browser Window**: Opens a new [browser window](#toc.browserpage).
*   [](#cmd.window.helpwindow)**New &Help Window**: Opens a new help window.
*   [](#cmd.window.screen1)**Screen &1**: Switches to virtual [screen](#toc.screens) 1.
*   [](#cmd.window.screen2)**Screen &2**: Switches to virtual screen 2.
*   [](#cmd.window.screen3)**Screen &3**: Switches to virtual screen 3.
*   [](#cmd.window.screen4)**Screen &4**: Switches to virtual screen 4.

### <a name="toc.draganddrop"></a>2.4.6. Drag and Drop

Objects can be dragged from any list or button that shows the object with its icon. You can use drag and drop to reorder objects in the project, or you can drag and drop objects in an arrangement editor to assign them to tracks or create events on the timeline. When you are drag-reordering objects in a list, you can hold down the Ctrl key to drop the object as a child of the object under the cursor. You can also drop an object onto the page tabs at the top of the project window, to drop the object as a child of the object on that page.

When you are dragging an object, a small translucent image will be attached to the mouse cursor showing the object icon and name. If you are dragging a multiple object selection, the folder icon is shown and the text tells you how many objects you are dragging.

If you drag the object over an area that does not accept the object, the mouse cursor turns into a 'no go' cursor. If you drag over an area that can accept the object, a translucent mask is drawn to highlight what will be affected by the drop.

Dragging objects over a project page tab will open that project page. This is useful if you want to drag objects from one opened project into another open project.

As with any mouse drag operation in Podium you can abort the drag operation by right-clicking while still holding the left button.

If you want to reorganize objects in the project, it is recommended that you move objects with drag and drop instead of using the cut and paste edit menu commands. When cutting objects to the clipboard they are removed from the project and thus any links to the objects in arrangements are reset. Moving objects with drag and drop will not break any links between the objects.

### <a name="toc.stickienotes"></a>2.4.7. Stickie Notes

![](images/window_stickie_note.png)

Stickie notes can be attached to objects in the project as well as tracks in arrangements. The project page shows stickie note buttons in the object info panels. The track inspector shows a stickie note button for the focus track. Stickie notes can also be shown in object browser lists. A stickie note button will have a dimmed image when the note is empty, and a bright yellow image when the note contains text. Hovering the mouse over the button will temporarily pop up the stickie note.

To edit a stickie note for an object, open the stickie note window by clicking the stickie note button or by using the the **Stickie Note** command in the object right-click menu. Pressing Alt+N opens the stickie note window for the current focus object.

To remove a stickie note, just delete all the text (including spaces and linefeeds) in the stickie note window. The quickest way to do this is to press Ctrl+A to select all the text, and then press the delete key.

## <a name="toc.startpage"></a>2.5. [](#start.page)Start Page

This page shows large tiles for all your recently opened projects, as well as tiles for all the project files that Podium finds in the **New projects folder** as configured in Preferences. If you have moved some of your project folders into subfolders then these subfolders will be shown as tile groups with the subfolder name as title.

If Podium finds an image file in a project folder it will display this image on the tile. If no image file is found then Podium will save a screenshot of the arrangement editor and show this on the tile. The idea with the screenshots is that in addition to the project name it can be helpful when you are looking for a specific project file.

The tile images are stored in a file named ProjectImageCache.db located in the New projects root folder. If you delete this file Podium will regenerate the images on next startup.

#### Toolbar

The toolbar at the top of the page contains an option button for locking help content.

*   **File**: Opens the **File** menu for the start page.
*   **View**: Opens the **View** menu for the start page.
*   [](#start.increasetilesize)**Increase Tile Size**: Increases the size of the project tiles.
*   [](#start.decreasetilesize)**Decrease Tile Size**: Decreases the size of the project tiles.

### <a name="toc.start.filemenu"></a>2.5.1. [](#start.filemenu)File Menu

Press Alt+F to open the [](#start.filemenu.label)**File** menu.

*   [](#cmd.start.file.newproject)**&New Project**: Opens a project page showing the **[New Project](#toc.newprojectpanel)** panel. Follow the instructions on that page to give the project a name and finally create the project file.
*   [](#cmd.start.file.openproject)**&Open Project...**: Opens a file dialog for loading a project file.
*   [](#cmd.start.file.saveallchanges)**&Save All Changes**: Saves all open projects and sound files that contain unsaved changes.
*   [](#cmd.start.file.explore)**Explore Projects Folder**: Opens a Windows file explorer for the projects folder.
*   [](#cmd.start.file.refresh)**Refresh Projects List**: Refreshes the list of project tiles. Use this command if you have changed the project folder contents with a Windows file explorer.
*   [](#cmd.start.file.clearrecent)**Clear Recent Projects List**: Clears the tiles in the **Recent Projects** group. The project files are not affected.
*   [](#cmd.start.file.closeall)**Close All Projects**: Closes all open projects. If any of the projects contain unsaved changes, you will be prompted if you want to save the changes.

### <a name="toc.start.viewmenu"></a>2.5.2. [](#start.viewmenu)View Menu

Press Alt+V to open the [](#start.viewmenu.label)**View** menu.

*   [](#cmd.start.view.showdetails)**Show File Modification Date**: Display project file modification date and time on a separate line on each project tile.
*   [](#cmd.start.view.folderlabel)**Folder:** Selecting a project group beneath this header line will scroll the start page to that group.

## <a name="toc.projectpage"></a>2.6. [](#project.page)Project Page

![](images/editor_project.png)

The project page is the home page in a project window.

The project page presents an organized view of the project contents and devices.

When you start on a new project, the project page shows the **New Project** panel. When a project is loaded, the project page shows the **Content** and **Device** panels.

### <a name="toc.newprojectpanel"></a>2.6.1 [](#newproject.panel)New Project Panel

The [](#newproject.title)**New Project** panel contains information and controls for setting up the type of project you want to create.

*   [](#newproject.option)**Project option**:
    *   [](#newproject.option.stereo)**New stereo project**: Creates mono/stereo mappings for I/O and plugins.
    *   [](#newproject.option.surround)**New surround project**: Creates surround mappings for I/O and plugins. I/O mappings will only be created for surround configurations that fit within the number of audio interface channels that you enable with the **Configure audio** button.
    *   [](#newproject.option.stereosurround)**New stereo and surround project**: Creates both stereo and surround mappings (see descriptions above).
    *   [](#newproject.option.templates)**Project Templates:** If you previously have saved project templates then this option will appear followed by the list of your templates. You can save project templates using the **File** menu on a project page. If you select a template, then the plugin and arrangement options are removed, since the configuration of these are already contained in the project template.
*   [](#newproject.name.button)**Edit project name**: Opens the **[Project Properties](#toc.projectproperties)** dialog where you can enter the project name. The project name will be used to create a new file folder when you save the project for the first time. The project folder will be placed in the **New projects folder** location specified in the **[Preferences dialog](#toc.preferences.projects)**. In the Podium default setup this folder location is "Documents\Zynewave Podium\Projects". The full file path of the new project file is shown beneath the [](#newproject.name.label)**Project name:** label.
*   [](#newproject.audioconfig)**Configure audio**: Opens the interfaces dialog where you can select all the audio inputs and outputs that you want to use. When a new project is created a set of device mappings will be created for all selected channels.
*   [](#newproject.midiconfig)**Configure MIDI**: Opens the interfaces dialog where you can select all the MIDI inputs and outputs that you want to use. When a new project is created a set of device mappings will be created for all selected interfaces.
*   [](#newproject.pluginoption)**Plugin option**:
    *   [](#newproject.pluginoption.none)**Don't load plugins**: Create the project without plugin mappings.
    *   [](#newproject.pluginoption.load)**Load plugin database**: Load plugin mappings from the plugin database. If you haven't changed your plugin installations since the last database update then this option skips the time consuming process of scanning for plugin files. Only plugins that are compatible with the selected stereo/surround project option will be loaded from the database.
    *   [](#newproject.pluginoption.buildload)**Build and load plugin database**: Build a plugin database by scanning for VST plugins in the configured VST plugin scan folders. The database is stored in the Podium setup folder.
    *   [](#newproject.pluginoption.updateload)**Update and load plugin database**: Updates the existing plugin database with any new VST plugins you may have installed. New plugins are added to the end of the plugin list in the database.
*   [](#newproject.pluginconfig)**Configure plugin folders**: Opens the preferences dialog where you can set up your VST plugin scan folders. These folders and any subfolders will be scanned for VST plugins when the project is created. All the configured scan folders are shown beneath the [](#newproject.pluginfolder.label)**VST plugin scan folders:** label.
*   [](#newproject.arroption)**Arrangement option**:
    *   [](#newproject.arroption.none)**Don't create a new arrangement**: Create the project with no initial arrangements. You can manually create new arrangements using the contents panel that will appear once the project is created.
    *   [](#newproject.arroption.create)**Create a new arrangement**: Create the project with a default initialized arrangement. The arrangement name will be set to the name you enter for the project. If the word "project" is found in the name it will be replaced with "arrangement". The arrangement editor will be opened after the project is created.
    *   [](#newproject.arroption.dialog)**Open properties dialog for a new arrangement**: Opens the properties dialog for a new arrangement when the project is created.
*   [](#newproject.create)**Create project**: Creates the project based on your selections on this page. A plugin scanning progress dialog will appear if you selected to build or update the plugin database. If you later on change your interface or plugin configurations you can update these in your existing projects using the **Device** panel on the project page.

### <a name="toc.project.filemenu"></a>2.5.1. [](#project.filemenu)File Menu

Press Alt+F to open the [](#project.filemenu.label)**File** menu.

*   [](#cmd.project.file.projectproperties)**Project &Properties**: Opens the **[Project Properties](#toc.projectproperties)** dialog.
*   [](#cmd.project.file.mergeproject)**&Merge Project...**: Opens a file dialog for selecting a project to be merged into the current project. The merge project file is not modified. Arrangements imported from the merge project are modified to use matching devices found in the current project. Device objects in the merge project are imported as well, if matching devices are not already found in the current project.
*   [](#cmd.project.file.saveproject)**&Save Project**: Saves the project, but does not save any edited sounds. Saving sound files can take a long time, so use this command if you only want to save your project changes.
*   [](#cmd.project.file.saveprojectas)**Save Project &As...**: Opens a file dialog for saving the project to another filename. The project will be renamed to the new filename, and following project save commands will save to the new filename. Use this command if you want to keep backup copies of older revisions of your project.
*   [](#cmd.project.file.saveprojecttemplate)**Save Project as Template...**: Opens the **New Project Template** dialog where you can enter a name for the template. A project template can be used for creating new projects or for changing device setups in an existing project.
*   [](#cmd.project.file.deleteproject)**Delete Project**: Closes the project and deletes all related project and sound files.
*   [](#cmd.project.file.exploreprojectfolder)**Explore Project Folder**: Opens a Windows file explorer for the current project folder.
*   [](#cmd.project.file.closeproject)**&Close Project**: Closes the project.

### <a name="toc.projectinfopanel"></a>2.6.1. Project Info Panel

The info panel at the upper left corner shows information for the current project. The panel has buttons for opening the **Project Properties** dialog and the project stickie note window.

If the project is saved, the full file path is shown. If the project has not been saved yet, the **New file** line shows the folder and filename that will be used when you save the project for the first time. If you change the project name in the **Project Properties** dialog before saving, then the new folder and filename will be updated accordingly. If a folder already exists with the project name, then "_01" (or a higher number) is appended to the folder name. Once the project is saved, the project name is the same as the project filename. You can change the project name by renaming the project file.

### <a name="toc.recentprojectspanel"></a>2.6.2. Recent Projects Panel

Below the project info panel is the **Recent Projects** panel. This shows a list of previously opened project files sorted with the most recently opened project at the top. The info panel at the bottom shows file information for the currently selected project in the list.

Double-click a project in the list or press the Enter key to load the selected project. If your current project is not saved, Podium will ask if you want to save the changes before loading the new project. Once a project is loaded it will move to the top of the recent project list. You can remove a project from the list using the **Remove Project** right-click menu command or by pressing the Delete key.

### <a name="toc.contentpanel"></a>2.6.3. [](#project.contentpanel)Content Panel

The content list shows all arrangements and sounds in the project. New content can be created or imported using the **Content** menu and the list right-click menu.

If you prefer to have one file for each arrangement you work on, you can choose to create a new project each time you start on a new arrangement. However, in the content panel you have the option to create multiple arrangements in a single project.

If after loading a project you see a sound that has a red icon in the list, it indicates a "missing" sound, meaning that the linked sound file could not be loaded. This can happen if you have moved the sound file or have renamed file folders. To relink missing sounds to their sound files you can select one or more missing sounds in the list, right-click the selection and use the **Search for Missing Sounds in Folder...** command. Podium will search for the missing files in the folder you specify. Note that this method will not work if you have renamed the sound files. In that case you should select **Properties** for the missing sound, and use the **Relink file...** button in the **Sound Properties** dialog.

### <a name="toc.contentmenu"></a>2.6.4. [](#project.contentmenu)Content Menu

Press Alt+C to open the [](#project.contentmenu.label)**Content** menu.

*   [](#cmd.project.content.newfolder)**New &Folder...**: Opens the properties dialog for a new folder object. The new empty folder is inserted at the bottom of the list. If your project contains a large number of arrangements and sounds, you may find it useful to organize them into folders.
*   [](#cmd.project.content.newarrangement)**New &Arrangement...**: Opens the properties dialog for a new arrangement object. After the arrangement is created it is opened in the arrangement editor.
*   [](#cmd.project.content.newsound)**New &Sound...**: Opens the properties dialog for a new sound object. After the sound is created it is opened in the sound editor. Creating new sounds is only necessary if you want to record directly in the sound editor. Recording audio in the arrangement editor will automatically create new sounds. If you want to edit an existing sound file, you should use the **Import File...** command, or drag the sound file onto the project page or onto a track in an arrangement editor.
*   [](#cmd.project.content.importfile)**Import File...**: Various types of media files can be imported to create either arrangement or sound objects. Importing a sound file (.wav or .aif) will create a sound object that links to the sound file. Importing a MIDI file (.mid) will create an arrangement. The tracks in the arrangement will be set up with the first available instrument in the device list that matches the MIDI channel numbers specified in the MIDI file. Note that you can also import MIDI files by dragging and dropping them onto tracks, but in that case only the first note or curve sequence in the MIDI file will be imported onto the track.

### <a name="toc.contentlistmenu"></a>2.6.5. Content List Menu

*   [](#cmd.objectlist.openeditorpage)**Open &Editor**: Opens an editor page for the selected object. Shortcut key is Enter. The editor page can also be opened by double-clicking the object.
*   [](#cmd.objectlist.openeditorwindow)**Open Editor in &Window**: Opens an editor window for the selected object.
*   [](#cmd.objectlist.clonearrunique)**New Arrangement as Unique Copy...**: Creates a copy of the arrangement including unique copies of all sounds and sequences used in the arrangement.
*   [](#cmd.objectlist.clonearrphantom)**New Arrangement as Phantom Copy...**:  Creates a copy of the arrangement without copying sounds and sequences. Timeline events are still linked to the sounds and sequences used by the original arrangement. Useful if you want to create alternative mixes of an already completed song.
*   [](#cmd.objectlist.clonearrtracks)**New Arrangement as Track Copy...**: Creates a copy of the arrangement without any timeline events. Useful for starting a new arrangement with a default track layout.
*   [](#cmd.objectlist.movetonewfolder)**Move to New &Folder...**: Opens the properties dialog for a new folder object. All selected objects are moved into the new folder. The new folder is inserted in the list at the position of the first selected object.
*   **&Delete**: Deletes all selected objects. A confirmation dialog will appear.
*   **&Sort Alphabetically**: Sorts all selected objects alphabetically. If the selected objects span multiple folders, then objects within each folder are sorted separately.
*   [](#cmd.objectlist.searchmissingsounds)**Search for Missing Sounds in Folder...**: Opens a **Browse For Folder** dialog. Podium will relink the missing sounds if it finds matching filenames in the specified folder. Use this command if you have moved your sound files to another folder.
*   **&Properties**: Opens the properties dialog for the selected object.
*   **Stickie &Note**: Opens the stickie note window for the selected object.

### <a name="toc.devicepanel"></a>2.6.6. [](#project.devicepanel)Device Panel

The device list shows all device mapping objects in the project. This includes I/O, busses, ReWire and VST plugins. The list can be maintained with the commands in the **Device** menu and the list right-click menu.

When a project is created, the device list is by default grouped into folders according to device type. If audio and MIDI interfaces were enabled, there will be folders for **Audio Inputs**, **Audio Outputs**, **MIDI Inputs**, **MIDI Outputs** and **Busses**. If the ReWire option in **Preferences** was enabled, the **ReWire** folder will contain all the installed ReWire device applications that Podium detected. If the VST plugin option was enabled, the plugins will be organized in folders matching the disk folders of the installed plugins. You can customize the folder organization in the project without having to change the plugin installation folders.

If after loading a project you see a plugin device mapping that has a red icon in the list, it indicates a "missing" plugin, meaning that the linked plugin file could not be loaded. This can happen if you have made changes to your plugin installations. Use the **Search for Missing Plugins** command in the **Device** menu, to let Podium search for and relink all the missing plugins it can find in the VST plugin scan folders as configured in **Preferences**. To search for plugins in a specific folder you can select one or more missing plugins in the list, right-click the selection and use the **Search for Missing Plugins...** command.

### <a name="toc.devicemenu"></a>2.6.7. [](#project.devicemenu)Device Menu

Press Alt+D to open the [](#project.devicemenu.label)**Device** menu.

This menu provides commands tailored for easy management of the I/O, bus and plugin device mappings in the project. For advanced editing of device objects use the object browser.

*   [](#cmd.project.device.newfolder)**New &Folder...**: Opens the properties dialog for a new folder object. The new empty folder is inserted at the bottom of the list.
*   [](#cmd.project.device.newbusinstance)**Add New Bus Instance**: Creates send/return mappings for a new bus instance.
*   [](#cmd.project.device.updateaudiomidi)**Update Audio and MIDI Mappings**: If you have changed the **Audio/MIDI** configuration since the project was created, then you can use this command to update all the audio and MIDI device mappings in the project. Note that when you change the configuration in the **[Interfaces](#toc.interfaces)** dialog, Podium will ask you if you want to update the mappings in all open projects.
*   [](#cmd.project.device.updaterewire)**Update ReWire Mappings**: Creates device mappings for all available ReWire devices not already imported in the project. For more information about ReWire, see the [ReWire devices](#toc.rewiredevices) section. The command is only available if the ReWire option is enabled in **Preferences**.
*   [](#cmd.project.device.loaddatabase)**Load Plugin Database**: Replaces the plugin setup in the current project with the latest plugin database. Use this command to update an older project with your latest plugin installations. This command is quick since it does not scan for plugins. If you have changed your plugin installations since the database was last updated, then you should use the build or update commands instead.
*   [](#cmd.project.device.builddatabase)**Build and Load Plugin Database**: Builds a new plugin database and then replaces the plugin setup in the current project.
*   [](#cmd.project.device.updatedatabase)**Update and Load Plugin Database**: Updates the existing plugin database and then replaces the plugin setup in the current project. The command will only search for new plugin files. Any new detected plugins are added to the end of the plugin list in the database.
*   [](#cmd.project.device.loadpluginsetuptemplate)**Load Plugin Setup from Template**: Shows a submenu with a list of all your project templates. Selecting a project template will replace the plugin setup in the current project with the plugin setup from the project template. If arrangements in the current project uses plugins mappings that are not present in the selected template, then these plugin mappings are preserved and merged with the plugin setup from the template.
*   [](#cmd.project.device.importplugin)**Import Plugin...**: Opens a file dialog where you can select one or more VST plugin files. The selected plugins will be imported and added to the end of the device list. In comparison to the plugin database commands, plugin import allows you to set up a smaller set of plugins in your project.
*   [](#cmd.project.device.importpluginfolder)**Import Plugins from Folder...**: Opens a **Browse For Folder** dialog. Podium will scan for and import detected plugins in the specified folder and any subfolders. Plugins that are already imported are skipped.
*   [](#cmd.project.device.importhardwaredef)**Import Hardware Definition**: Shows a submenu with a list of all your hardware definition files. See the [import hardware definition](#toc.importhardwaredefinition) section for more information.
*   [](#cmd.project.device.selectmissing)**Select All Missing Plugins**: Selects all missing plugins in the list. If you no longer have the plugins available you can choose to delete the mappings by right-clicking the selection and use **Delete**.
*   [](#cmd.project.device.searchmissing)**Search for Missing Plugins**: Searches for and relinks all the missing plugins that can be found in the VST plugin scan folders as configured in **Preferences**.

### <a name="toc.devicelistmenu"></a>2.6.8. Device List Menu

*   [](#cmd.objectlist.clonemap)**New Copy...**: Opens the **Device Mapping Properties** dialog for creating a copy of the selected mapping.
*   [](#cmd.objectlist.cloneinstance)**New Instance**: Creates a new instance of the selected global device. The new instance will have copies of all the mappings belonging to the original instance, only the copied mappings will use the next available instance number. You can access the command by right-clicking on either a device mapping or a folder containing device mappings for a global instance.
*   [](#cmd.objectlist.clonemultitimbral)**New Multitimbral Instance**: Creates a new global instance of the selected instrument insert mapping. The new global instance will have 16 MIDI channel mappings in addition to the audio output mapping. Some VST instrument plugins cannot be detected as being multitimbral capable when they are scanned. For those plugins Podium will only create a single instrument insert mapping. If you know a plugin instrument is multitimbral capable, you can use this command to get mappings for the individual MIDI channels.
*   [](#cmd.objectlist.cloneinsertmulti)**New Multichannel Insert Mapping**: Creates a new multichannel insert mapping that combines the input and output channels used by all mappings of the selected global device. Some VST plugins cannot be detected as being multichannel capable when they are scanned. For those plugins Podium will create separate stereo mappings for the number of supported input and output channels. If you know a plugin is multichannel capable, you can use this command to create a single multichannel insert mapping. Afterwards you can adjust the channel settings in the properties of the new insert mapping. See also [multitimbral and multiple io plugins](#toc.multitimbralplugins).
*   **Move to New Folder...**:  Opens the properties dialog for a new folder object. All selected objects are moved into the new folder. The new folder is inserted in the list at the position of the first selected object.
*   **&Delete**: Deletes all selected objects. A confirmation dialog will appear.
*   **&Sort Alphabetically**: Sorts all selected objects alphabetically. If the selected objects span multiple folders, then objects within each folder are sorted separately.
*   [](#cmd.objectlist.searchmissingplugins)**Search for Missing Plugins in Folder...**: Opens a **Browse For Folder** dialog. Podium will relink the missing plugins if it finds matching filenames in the specified folder or subfolders.
*   **&Properties**: Opens the properties dialog for the selected object.
*   **Stickie &Note**: Opens the stickie note window for the selected object.

### <a name="toc.importhardwaredefinition"></a>2.6.9. [](#dialog.importhardwaredefinition)Import Hardware Definition

![](images/dialog_import_hardware_definition.png)

The **Device** menu contains an **Import Hardware Definition** submenu which lists all the files that are found in the **Hardware definition library folder** as specified in **Preferences**. The default location of this folder is "Documents\Zynewave Podium\Library\Hardware Definitions". Podium will search this folder during startup.

Device definition files contain a set of device objects that have been customized for a particular device. This includes mappings, presets and parameters. If you chose to build the default folders the first time you ran Podium, there will be a set of generic device definition files in the hardware definitions folder.

The available definition files in the Podium library are limited, but Podium also supports Cubase patch script files (the version that uses the .txt extension). If you copy your patch script files to the hardware folder then these will show up in the **Import Hardware Definition** submenu the next time you start Podium.

If you select a hardware definition from the submenu, Podium will display the **Import Hardware Definition** dialog. Here you specify how your device is connected to your MIDI and audio interfaces. If you have more than one MIDI input or more than one MIDI output interface enabled, you should select the interface that the device is connected to. Otherwise leave it at the [](#text.option.usedefaultfromfile)**\<Use default setting from file>** setting. You should also leave it at the default setting if you are importing a device that uses virtual MIDI ports such as the Yamaha SW1000XG. Finally select the first channel in the audio interface connections. This will typically be the first channel in a stereo pair. If you don't have either input or output connected to your audio interface, then leave the setting at [](#text.option.notconnected)**\<Not connected>**. Clicking **OK** will import the device definition and adjust the imported mappings to your interface selections.

## <a name="toc.inspectorpage"></a>2.7. Inspector Page

The inspector can be opened and closed by clicking the **Inspector** tab at top left side of the project window, and its width can be adjusted by dragging the divider between the inspector and the arrangement editor. It can also be opened in a separate window by selecting **New Inspector Window** from the **Window** menu.

The inspector page shows detailed information about the focus track in an arrangement. The page is blank if there is no arrangement editor open. See the [track inspector](#toc.trackinspector) chapter for more information.

## <a name="toc.browserpage"></a>2.8. [](#browser.page)Browser Page

![](images/window_browser.png)

The browser page can be opened/closed by clicking the **Browser** page tab, or by pressing the F7 shortcut key. Browser windows can be opened with the **New Browser Window** command in the **Window** menu. Several browser windows can be open at the same time.

The browser can show an object browser and/or a file browser. The object browser (on the left) shows the objects in the current project. The file browser (on the right) shows the contents of a disk folder that you specify. The file browser can be used to get an overview of the files that are used by the current project, and it can be used to import files into your project by for example dragging sound and MIDI files onto the track timeline in arrangement editors.

The project and file browsers can be resized by dragging the space between the two lists. Pressing the Tab key will switch key focus between the two lists.

#### Toolbar

The toolbar at the top of the browser page contains various controls for configuring the browser. Some of the toolbar controls can be shown/hidden using the browser options menu.

*   **Browser Options Menu**: Opens the options menu.
*   [](#browser.refresh)**Refresh File List**: Refreshes the contents of the file browser list.
*   [](#browser.addfavorite)**Add to Favorites**: Adds the current address bar folder in the file browser to the favorite folders list, provided that the folder is not already in the favorite folders list.
*   [](#browser.autoaudition)**Auto-audition**: Enables automatic audition of the selected sound or MIDI file in the file browser list. Audition is restarted when you select another file in the list, either by cursor key navigation or by clicking in the list.
*   **Audition Gain Slider**: Sets the gain of auditioned sounds. Ctrl+click the slider to reset it to 0 dB. Shift+click+drag to fine adjust the gain value.

#### [](#browser.favorite)Favorite Folder

If you have added favorite folders, you will see numbered buttons to the left of the **Add to Favorites** button. A maximum of nine numbered buttons are shown. These buttons are shortcuts to the first nine favorite folders. If you have more favorites, you can access them all in the file browser menu.

*   Click to go to favorite folder. Click again to return to previous folder.
*   Ctrl+Click to overwrite favorite with current folder.
*   Alt+Click to remove favorite.

Right-click to show the favorite options menu:

*   [](#cmd.favorite.insertnew)**Insert New Favorite**: Inserts the current address bar folder as a new favorite before the selected favorite.
*   [](#cmd.favorite.overwrite)**Overwrite Favorite**: Overwrites the selected favorite with the current address bar folder. This can also be done by Ctrl+clicking the button.
*   [](#cmd.favorite.delete)**Delete Favorite**: Deletes the favorite folder. This can also be done by Alt+clicking the button.
*   [](#cmd.favorite.moveleft)**Move Left**: Moves the favorite to the left in the list of favorites.
*   [](#cmd.favorite.moveright)**Move Right**: Moves the favorite to the right in the list of favorites.

_Note:_ All the browser options, including the audition gain value, are local settings for each browser window. The favorite folders list however is globally shared among all browsers.

### <a name="toc.browseroptionsmenu"></a>2.8.1. [](#browser.menu)Browser Options Menu

*   [](#cmd.browser.showobject)**Show Object Browser**: Shows/hides the object browser.
*   [](#cmd.browser.showfile)**Show File Browser**: Shows/hides the file browser.
*   [](#cmd.browser.showstickies)**Show Stickie Notes**: Shows yellow stickie note icons next to the objects that have a stickie note attached. Clicking a stickie note icon will open the stickie note window. Stickie notes can be created for any object by using the **Stickie Note** right-click menu command.
*   [](#cmd.browser.dragreorder)**Enable Drag-Reordering**: Enables drag-reordering of objects in the object browser list. Hold the Ctrl key to drop objects as child objects of the object under the mouse cursor.
*   [](#cmd.browser.favoritebuttons)**Show Favorite Buttons**: Shows favorite folder shortcut buttons on the toolbar.
*   [](#cmd.browser.auditioncontrols)**Show Audition Controls**: Shows the **Auto-audition** button and audition gain slider on the toolbar.
*   [](#cmd.browser.auditionfocustrack)**Audition on Focus Track**: If an arrangement is powered on, audition is performed on the focus track instead of the master track. This means the sound is auditioned with any effect processing that is set up on the focus track. If the option is disabled, then the sound is auditioned directly on the master track. If an arrangement is not currently powered on, then any auditioned sounds are sent directly to the audio interface. MIDI files will always be auditioned on the focus track, since they require an instrument device to play back the notes in the MIDI file.
*   [](#cmd.browser.auditionbarstart)**Audition on Bar Start**: If an arrangement is playing, audition start is delayed so that it plays in sync on the next bar. MIDI files will play back at the current arrangement tempo.
*   [](#cmd.browser.showallfiles)**Show All File Types**: Shows all file types in the file browser. When disabled, only media file types recognized by Podium will be shown in the file browser list.

### <a name="toc.objectbrowser"></a>2.8.2. [](#browser.objectpanel)Object Browser

The address bar at the top of the object browser shows the object whose folder contents is shown as a tree view in the list below. The project object is initially set in the address bar. You can drag an object onto the address bar or use the commands in the object browser menu and object list menu to set a new object in the address bar.

### <a name="toc.objectbrowsermenu"></a>2.8.3. [](#browser.objectpanel.menu)Object Browser Menu

The menu can be opened by right-clicking the address bar or by clicking the menu button at the right edge of the address bar.

*   [](#cmd.objectbrowser.gotoproject)**Go To Project Object**: Sets the project object in the address bar.
*   [](#cmd.objectbrowser.gotoparent)**Go Up One Level**: Moves up to the parent object in the address bar.
*   [](#cmd.objectbrowser.addnewobject)**Add New Object**: Shows a submenu where you select which type of object to create. The object is added as child object of the address bar object.
*   [](#cmd.objectbrowser.selectall)**Select All**: Selects all objects in the list.
*   [](#cmd.objectbrowser.paste)**Paste**: Pastes any objects in the clipboard at the end of the list.
*   [](#cmd.objectbrowser.properties)**&Properties**: Opens the properties dialog for the address bar object.
*   [](#cmd.objectbrowser.stickienote)**Stickie &Note**: Opens the stickie note window for the address bar object.

### <a name="toc.objectlist"></a>2.8.4. [](#browser.objectpanel.list)Object List

To the left of each object is shown an icon that identifies the object type. An asterisk symbol is drawn on project and sound icons if the object has been modified and not yet saved to file.

Object lists are also available in the [track inspector](#toc.trackinspector). The inspector lists are used for easy selection of device mappings, presets and parameters and they show only the objects that are available for the focus track.

#### Object List Menu

The menu can be opened by right-clicking on an object in the list.

*   [](#cmd.objectlist.gotofolder)**Go To Folder**: Sets the selected object in the address bar.
*   **Open Editor in &Window**: Opens an editor window for the selected object. Available if the selected object is an arrangement, sequence or sound object.
*   [](#cmd.objectlist.insertnewobject)**Insert New Object**: Shows a submenu where you select which type of object to create. The object is inserted before the selected object and under the same parent object as the selected object. If you want to add a new child object to an object which does not yet have any child objects, use the **Go To Folder** command on the desired parent object and then use the **Add New Object** submenu in the object browser menu.
    *   [](#cmd.objectlist.newfolder)**New Folder...**: Opens the properties dialog for a new folder object.
    *   [](#cmd.objectlist.newarrangement)**New Arrangement...**: Opens the properties dialog for a new arrangement object.
    *   [](#cmd.objectlist.newsound)**New Sound...**: Opens the properties dialog for a new sound object.
    *   [](#cmd.objectlist.newmapping)**New Device Mapping...**: Opens the properties dialog for a new device mapping object.
    *   [](#cmd.objectlist.newdefinition)**New Device Definition...**: Opens the properties dialog for a new device definition object.
    *   [](#cmd.objectlist.newpreset)**New Preset...**: Opens the properties dialog for a new preset object.
    *   [](#cmd.objectlist.newparameter)**New Parameter...**: Opens the properties dialog for a new parameter object.
*   [](#cmd.objectlist.cut)**Cut**: Cuts all selected objects to the clipboard.
*   [](#cmd.objectlist.copy)**Copy**: Copies all selected objects to the clipboard.
*   [](#cmd.objectlist.paste)**Paste**: Pastes any objects on the clipboard into the object list before the selected object.
*   [](#cmd.objectlist.delete)**&Delete**: Deletes all selected objects. A confirmation dialog will appear.
*   [](#cmd.objectlist.sortalpha)**&Sort Alphabetically**: Sorts all selected objects alphabetically. If the selected objects span multiple folders, then objects within each folder are sorted separately.
*   [](#cmd.objectlist.properties)**&Properties**: Opens the properties dialog for the selected object.
*   [](#cmd.objectlist.stickienote)**Stickie &Note**: Opens the stickie note window for the selected object.

### <a name="toc.filebrowser"></a>2.8.5. [](#browser.filepanel)File Browser

The address bar at the top of the file browser shows the folder whose contents is shown as a tree view in the list below. Moving the mouse cursor over the address bar will highlight the individual parent folders in the folder path. Clicking a parent folder will set that folder in the address bar.

A folder select dialog can be opened by double-clicking on the blank area to the right of the folder name (to avoid going to a parent folder as described above), or by selecting the **Browse for Folder...** command in the file browser menu. You can also use the **Go To Folder** right-click menu command on a folder in the list.

When a folder is set in the address bar, any subfolders will initially be shown as collapsed in the file list. Searching all subfolders can be time-consuming so Podium only searches a folder when you open it in the list for the first time. The icon for a folder is shown dimmed to indicate that the folder has not yet been searched.

### <a name="toc.filebrowsermenu"></a>2.8.6. [](#browser.filepanel.menu)File Browser Menu

The menu can be opened by right-clicking the address bar or by clicking the menu button at the right edge of the address bar.

*   [](#cmd.filebrowser.gotoproject)**Go To Project Folder**: Sets the project folder for the currently selected project in the address bar.
*   [](#cmd.filebrowser.gotoparent)**Go Up One Level**: Moves up to the parent folder in the address bar.
*   [](#cmd.filebrowser.favorites)**Favorites**: Shows a submenu listing all configured favorite folders. Selecting a favorite will set that folder in the address bar.
*   [](#cmd.filebrowser.addfavorite)**&Add to Favorites**: Adds the current address bar folder to the favorite folders list.
*   [](#cmd.filebrowser.organizefavorites)**&Organize Favorites...**: Opens the **[Favorite Folders](#toc.favoritefolders)** dialog. In this dialog you can reorder the favorites and delete favorites you no longer need.
*   [](#cmd.filebrowser.browse)**Browse for Folder...**: Opens the **Browse For Folder** dialog where you can select a new address bar folder.
*   [](#cmd.filebrowser.explore)**Explore Folder**: Opens a Windows file explorer for the address bar folder.
*   [](#cmd.filebrowser.refresh)**Refresh File List**: Refreshes the contents of the file list. Use this command if you have changed the folder contents with a Windows file explorer.

### <a name="toc.filelist"></a>2.8.7. [](#browser.filepanel.list)File List

Navigation in the file list uses the same key shortcuts as all other tree lists in Podium. Use arrow, page up/down, home/end keys to navigate the list. Use -/+ or arrow left/right keys to collapse/expand a folder.

By default only file types that can be imported into the project are shown in the list. Icons similar to the ones used in the object browser are shown next to the files. A folder in the list may appear to be empty but can in fact contain hidden files. Enable the **Show All File Types** option in the browser options menu to show all files in the list.

If you double-click, press Enter or use the **Start Audition** right-click menu command on a sound or MIDI file, Podium will play the file while showing a progress bar. You can drag the sound or MIDI file directly onto the tracks in an arrangement editor, which will import the file as a sound or sequence object under the arrangement object. Alternatively you can use the **Import into Project** right-click menu command to import into the folder currently shown in the object browser address bar.

MIDI file audition is only available if an arrangement is currently powered on. The MIDI file will be played on the focus track, so you will only hear the notes if you have an instrument assigned on that track. Only the first available note sequence in the MIDI file will be auditioned. If the MIDI file contains multiple tracks, you can import it as a new arrangement using the **Import File...** command in the **Content** menu on the project page.

Files that are linked to the project are marked with pin icons at the left side of the file list. Pins will be placed next to the project file, sound files, and any image files specified in the **Project Properties** dialog. If a folder contains linked files, a dimmed pin icon is shown next to the folder. If there are linked files outside of the address bar folder, a dimmed pin icon will be shown in the address bar.

#### File List Menu

The menu can be opened by right-clicking on a file or folder in the list.

*   [](#cmd.filelist.startplay)**Start Audition**: Starts audition of the selected sound or MIDI file. Audition behavior can be configured in the [browser options menu](#toc.browseroptionsmenu).
*   [](#cmd.filelist.stopplay)**Stop Audition**: Stops the currently playing audition.
*   [](#cmd.filelist.gotofolder)**Go To Folder**: Sets the selected folder as the address bar folder.
*   [](#cmd.filelist.openproject)**Open Project**: Opens the selected project file.
*   [](#cmd.filelist.import)**Import into Project**: Imports the selected sound or MIDI files into the current project. MIDI files will be imported as arrangements. You can also drag MIDI files onto tracks of an existing arrangement, in which case only the first sequence in the MIDI file will be imported and placed on the track.
*   [](#cmd.filelist.delete)**Delete**: Moves the selected files and folders to the Windows Recycle Bin. A confirmation dialog will appear. Be careful with deleting folders: Unless the **Show All File Types** option is enabled, folders that appear to be empty in the file browser may in fact contain non-media files.

## <a name="toc.helppage"></a>2.9. [](#help.page)Help Page

The help page can be opened/closed by clicking the **Help** page tab, or by pressing the F1 shortcut key. Help windows can be opened with the **New Help Window** command in the **Window** menu.

The help page displays context help for the UI element that you point to with the mouse cursor. This offers a quick way to learn about features in the Podium UI, and is also helpful for quick lookup of mouse and key shortcuts for the various Podium features.

The shown help text is extracted from the Podium guide document. When Podium is starting up it will load the Podium guide and link the individual sections to the corresponding UI element. Not only are the help texts extracted from the guide, but also all the Podium UI texts including menus, dialog boxes, and so on. By loading a translated guide document in the **Preferences** dialog the entire Podium UI can be translated to a different language.

The guide that comes with the Podium installer is written in US English but preparations have been made to help the user community to create translations of the guide. Translation instructions are available on the [Zynewave GitHub](https://github.com/zynewave/) page.

Some chapters in the guide are not linked to UI elements, such as the [quick introduction](#toc.intro) chapter and the [control surfaces](#toc.controlsurfaces) chapter. If you want to read the full guide you can open it in your web browser from the **Podium** menu.

The toolbar at the top of the page contains the following control:

*   [](#help.lock)**Lock Content**: Position the mouse cursor over any UI element and press Shift+F1 to open and lock the corresponding help text. If the help text for a feature is larger than can fit on the help page you will need to lock the content to be able to move the mouse cursor to the help page and scroll through the help text. Click the lock button or close the help page to unlock the content.

* * *

# <a name="toc.devices"></a>3. Devices

When working with devices in Podium, you use the same types of objects, whether you want to access simple MIDI and audio inputs, audio monitoring outputs, software plugins, mixer busses, ReWire devices, or external hardware devices connected via MIDI and audio interfaces.

Podium uses [Device Mappings](#toc.devicemappings), [Device Definitions](#toc.devicedefinitions), [Presets](#toc.presets) and [Parameters](#toc.parameters) to encapsulate the configuration of devices. The purpose of these device objects is both to hide the technical aspects of the different types of devices and to offer a uniform way of working with the devices in the arrangement editor.

Device mappings are the main handle to a device. A device may have multiple mappings associated if the device supports multiple MIDI or audio channel configurations. Each device mapping links to a device definition object that contains preset and parameter objects configured for that particular device. Preset objects are used to recall and store settings for a device. Parameter objects are used for automating single parameters in a device.

When you want to use a device in an arrangement you assign the device mapping to a track. Once assigned, you have access to the list of presets and parameters that are available for the device. You can then assign a preset to the track and create child tracks for parameter automation.

The project page can be used to configure your devices, so normally you don't have to deal with the internal workings of the device objects.

## <a name="toc.hardwaredevices"></a>3.1. Hardware Devices

External hardware devices can be fully integrated into the Podium engine. If you hook up both the MIDI and audio connections of a device to your PC interfaces then you can control and route the audio through the device on a single track in an arrangement. You use the same approach whether you are working with hardware devices or with software plugins. This makes it possible to route hardware and plugins interchangeably in effect chains. Podium also supports full MIDI and audio latency compensation with hardware devices as well as with plugins.

To configure a hardware synth or effects unit, you import a device definition file from the project page. A device definition file contains device objects that have been customized for a particular device. When you select a hardware definition on the project page, a dialog pops up where you select the MIDI interfaces and the audio interface channels that your device is connected to. These settings will then be used by Podium to configure the imported mappings accordingly.

Note that the Podium installer only includes a few generic definition files. You can download device specific definition files from the Wiki section on zynewave.com. If you can't find a definition file for your device, you can import Cubase patch script files, or import one of the generic definition files that matches the type of your device. This will give you a set of default mappings, presets and parameters, which you then can modify according to the specs of your device.

## <a name="toc.plugins"></a>3.2. Plugins

Plugins are software program extensions that can be loaded into a plugin 'host' application where they are used to generate or process audio. There are many plugin formats available for audio processing. Podium supports the VST format including VSTi instruments. The device definitions forum on zynewave.com has links to plugin developers offering both free and commercial plugins.

Podium does not scan your harddisk for plugins when starting up. Rather you choose which plugins you want to work with in your current project by importing the plugins. Importing a plugin will create device objects based on the information provided by the plugin. The plugin itself is only loaded once you assign the plugin device mapping to a track in an arrangement and activate monitoring.

Plugins are imported on the project page. Some of the more advanced plugins may have a premade device definition file in the Podium library. These device definition files are configured with additional information that cannot be extracted from the plugin itself. This can be MIDI parameter objects, customized mappings and categorized folders for presets and parameters.

Many plugins have a native editor window which can be opened within Podium. Plugins that don't have a native editor window will be opened in a generic editor window. The generic editor shows a list of parameters, their current value and a value dial. Rather than showing the VST parameters as defined by the plugin, the editor builds the list from the parameter objects found in the plugin device definition. Some plugins may expose invalid or incorrectly labeled parameters. By removing or renaming these parameter objects you can make the editor more accessible. Furthermore, if you organize the parameter objects into folders, the folder names will appear as group headers in the editor window. The generic editor is also available in the track inspector info panel.

![](images/window_plugin.png)

## <a name="toc.multitimbralplugins"></a>3.3. Multitimbral and Multiple IO Plugins

Some instrument plugins are multitimbral, meaning that they support the use of MIDI channels to play multiple programs simultaneously. Unless the plugin supports the VST v2.4 protocol there is no way for a host to know if the plugin supports multitimbrality. If an instrument plugin has been imported without individual MIDI channel mappings, right-click the corresponding object on the project page and choose the **New Multitimbral Instance** command.

Plugins can be configured to work in either 'insert' or 'global' mode. If the plugin provides a single input/output configuration it will typically be configured as an insert plugin. Separate instances of the insert plugin will be created for each track the insert plugin mapping is assigned to.

A plugin that supports multitimbrality or multiple IO will typically be configured as a global plugin. A global plugin instance has a set of associated mappings, identified by the global instance number in the device mapping properties. This also means that, unlike insert plugins, separate sets of mappings are required for each instance that you want to use. The mappings for a global plugin instance are labeled (#1) etc. to help identify the instance. Extra mappings, labeled (#2), (#3) etc., can be created on the project page by right-clicking an existing mapping and choosing the **New Instance** command.

If you don't want to use the multitimbrality or multiple IO capabilities of a plugin, it is highly recommended to use the plugin configured as an insert. It is easier to manage multiple instances of insert plugins, and furthermore the nature of the Podium hierarchic engine offers many benefits when both MIDI and audio routing of a plugin can be managed on a single track.

If you want to use a global plugin as an insert plugin but an insert mapping is missing, you can create one on the project page by right-clicking a global mapping and choosing the **New Insert Mapping** command.

Some of the global plugin device definition files in the Podium library have alternative (global) and (insert) file versions. This gives you the option to import the plugin as either a global or an insert plugin.

## <a name="toc.rewiredevices"></a>3.4. ReWire Devices

ReWire (by [Propellerhead Software](https://www.propellerheads.se/)) is a system that makes it possible to transfer audio and MIDI data between two music applications, a ReWire host and a ReWire device, in real time. Podium can act as a ReWire host and implements ReWire mixer support.

You can stream audio from a ReWire device (such as Propellerhead's Reason) to Podium. You can use the transport controls in either Podium or the ReWire device to play, stop, or move the playback cursor and the applications will stay in sync. You can also control the ReWire device from Podium using MIDI. Record enabling a ReWire MIDI mapping track will record parameter tracks of control changes made in the ReWire device window if the ReWire device supports MIDI output.

When creating new projects, Podium will automatically detect any installed ReWire device applications and create audio mappings for these in a ReWire devices folder if the **Enable ReWire devices** option on the **[Plugins](#toc.preferences.plugins)** preferences tab is enabled. If you have installed new ReWire device applications you can import these into your existing projects using the **Import ReWire Devices** command on the **Device** menu on the project page.

Working with ReWire device mappings is similar to working with mappings of a global VST plugin. You have one or more audio output mappings and a set of MIDI mappings. The MIDI mappings are created and renamed dynamically by Podium in response to changes made in the ReWire device. For that reason you should not manually modify the ReWire MIDI mappings that Podium creates in the ReWire devices folder.

When you assign a ReWire mapping to a track, Podium will try to start the ReWire application. The **E** editor button on the track will light up to indicate that the ReWire application is open. You can click the **E** button to open/close the application, but most ReWire devices only produce sound when their application is open. Some ReWire applications will not start automatically when requested by Podium. That is the case with for example Ableton Live 7, which you will need to start manually after powering on an arrangement with Live mappings assigned to tracks, to make Live start up in ReWire device mode.

The use of ReWire devices can be enabled and disabled using the **Enable ReWire devices** option on the **[Plugins](#toc.preferences.plugins)** preferences tab.

## <a name="toc.devicemappings"></a>3.5. Device Mappings

Podium will create and maintain many device mappings for you automatically. In some cases, however, you may have to create or modify a device mapping manually. This could be the case for example if you want to connect a hardware device for which a device definition doesn’t exist or if an automatically created mapping doesn’t work with your configuration.

It is recommended that you use the project page commands to create the device mapping objects. The properties of the objects can then be customized afterwards.

Device mapping objects can be configured for either audio/MIDI interfaces, plugins or mixer busses. Audio/MIDI interface mappings can furthermore be categorized as input mappings, audio output monitor mappings or external device specific mappings.

Input mappings are configured as either MIDI or audio interface inputs. These mappings are used with MIDI controllers and microphone/line audio inputs to record MIDI and audio on tracks. Input mappings are available in the track inspector input panel, and can be assigned to tracks independently of output mapping assignments.

Audio monitor mappings are configured with only audio interface outputs. These are used for monitoring the audio output of your arrangements, either through speakers or headphones connected to your audio interface.

External devices controlled via a single MIDI channel and a single audio IO configuration can be configured within a single device mapping object. This allows total integration of the device on just one track in the arrangement. If the device supports multitimbrality or multiple IO, there need to be mappings for each MIDI channel and IO configuration.

The way plugins are configured is very similar to how external devices are configured. The main difference is that the plugin file is specified instead of MIDI and audio interfaces.

Mixer busses are a feature of the Podium mixing engine that allows audio to be extracted from tracks assigned with bus send mappings, and injected at tracks assigned with matching bus return mappings. A total of 99 mixer bus instances can be configured, and each mixer bus supports up to 32 audio channels.

### <a name="toc.devicemappingproperties"></a>3.5.1. [](#dialog.devicemap)Device Mapping Properties

![](images/dialog_device_mapping.png)

To display the **Device Mapping Properties** dialog for a device mapping, locate the device mapping on the project page, right-click it and choose **Properties**.

The **Device definition** drop-down list is used to select a device definition folder that will contain preset and parameter objects for this device.

The choices for **Mapping type** are: Audio/MIDI interfaces, mixer bus, VST plugin, and ReWire device. Various settings in the dialog will be disabled if they have no relevance to the selected mapping type.

Select **Link to global instance** and specify a number if this mapping is referring to an instance that is shared with other mappings. When used with plugins, the instance number is joined with the plugin file name to identify a unique instance of the plugin. When used with audio/MIDI interfaces, the instance number is joined with the device definition object to identify a unique instance of the external device.

The interface settings will be available when the mapping type is set to audio/MIDI interfaces. If you only use one MIDI interface in your studio setup, you would typically select the [](#text.option.anyinterface)**\<Any available interface>** option, to ensure that the mapping will still be valid if you later change your MIDI interface. If you use several MIDI interfaces you need to select the specific interface that this device is connected to.

#### Plugin Configuration

For software plugin mapping types, the plugin file name should be entered either directly or by locating the installed plugin with the **Browse plugin** dialog. If your plugin is located within the folder path of the default VST folder defined in the **[Plugins](#toc.preferences.plugins)** preferences tab, you should select the **Relative path** option. This will remove the absolute path part of the file name. If you later relocate your VST folder or try to open the project on a system with a different VST folder location, the plugins can still be found with the relative path.

If the **Use generic editor instead of plugin editor** option is enabled, Podium will open the generic plugin editor window, even if the plugin has its own native editor. This may be preferable if the plugin native editor is badly designed. Some native plugin editors may even be unstable and cause crashes.

#### MIDI Input Configuration (Plugin Output)

If a MIDI input interface is configured you can choose to filter the incoming MIDI to a specific channel. This can be useful if you have a MIDI controller that supports selection of MIDI channel. If you create separate device mappings for each channel, and assign these to your instrument tracks in an arrangement, you can control the different instruments just by switching MIDI channel on your controller.

The **Transpose notes on input** setting will transpose all incoming MIDI notes before they are sent to the receiving device or recorded to sequences. This is useful if you have a MIDI controller that does not allow easy transposition of octaves. You can then create alternative input mappings with different octave transpositions and just switch among these in the track inspector input panel.

If the mapping is configured with both a MIDI input and output interface then the **Send input thru to output interface** option determines if the received MIDI input should be echoed straight through to the output interface. This option should be set only if the local on/off setting on the external device is set to off, otherwise you will get 'double notes' played on the device. Setting the device to local off, and enabling the mapping thru option, will route the keys and controllers action on the device into Podium before being sent back to the device for playback. This allows you to record the performance in Podium.

#### MIDI Output Configuration (Plugin Input)

The MIDI output **Channel** should be set to the same channel that is selected on the controlled device. Furthermore, if the device supports SysEx, the **SysEx device ID** should match the device setup. The two SysEx variables provide a means to encode mapping related numbers into the parameter SysEx messages. Depending on the device this could for example be a part number that corresponds to the MIDI channel number.

The **Device is an instrument** option is used by Podium to distinguish between effect and instrument mappings. This determines for example what kind of sequence is created by default on tracks assigned with this mapping. If configured as an instrument, note sequences will be created. Otherwise curve sequences will be created for parameter automation.

#### Audio Configuration

If the mapping is configured to use audio you can select how many source and target channels are used by this mapping. If the device being mapped is a multiple IO plugin or an external device connected to a multiple channel audio interface, then you can set the **First channel** to offset the channels into the number of available channels.

Note that the source and target channels are to be seen from the perspective of the Podium mixer engine. For audio interfaces 'source' refers to the audio interface inputs, but for plugins 'source' refers to the plugin outputs. It is perhaps easier to think of source channels as 'providing a source of audio to the Podium mixer engine'.

## <a name="toc.devicedefinitions"></a>3.6. Device Definitions

When you want to use a hardware device or a plugin in your project, the recommended procedure is to use the project page to import a device definition file from the Podium library. Definition files contain an organized collection of device mapping, preset and parameter objects, enabling you to fully control the device in your arrangements.

If the Podium library does not contain a file for your hardware device, you can alternatively import the widely available Cubase patchname script files. Searching the internet for scripts for your device will likely provide you with links to sites where you can download the files.

If you have a plugin that is not available in the Podium library, you import it by locating the installed plugin file. This will automatically create device mapping objects for all the supported IO configurations and create program presets and VST parameters as declared by the plugin. The VST specification does not provide a means for the plugin to declare its MIDI parameter support, so if you want to use MIDI automation you will have to configure these parameters manually.

### <a name="toc.devicedefinitionproperties"></a>3.6.1. [](#dialog.devicedef)Device Definition Properties

![](images/dialog_device_definition.png)

Device definition objects are simple folder objects that act as containers of preset and parameter objects. They are not shown in the device list on the project page, but they can be accessed in the object browser.

In the **Device Mapping Properties** dialog you select a device definition object to create a link between the mapping and a compatible collection of presets and parameters. Podium uses this relation to make it possible to create several mappings for a particular device and only keep one copy of the device definition folder in the project.

### <a name="toc.creatinglibraryfiles"></a>3.6.2. Creating Library Files

By using the project page to import device definition files, you don't need to go into the details of configuring device objects. If on the other hand you have a device that is not available in the Podium library, you may want to create a library file for it.

For starters it would be a good exercise to load some of the existing library files and browse the project hierarchy to examine their structure.

To create a new library file you should start out with an empty project. Create a new project and remove all default generated objects using the object browser.

To create a definition file for a hardware device, the best approach is to import a Cubase patch script file for the device using the **Import File...** command on the **File** menu (or by pressing Ctrl+I). When you import a Cubase patch script file all presets will be configured correctly. Script files do not contain definitions for parameters, so Podium will create a set of default MIDI controller parameters. You may want to customize the parameters according to the MIDI specification of the device. If you cannot find a script file for the device, the next best approach is to import one of the generic library files and customize the objects.

To create a definition file for a plugin, select **Import Plugin...** on the **Device** menu and locate the plugin. Podium creates a device mapping and a definition folder for the plugin. If you browse into the definition folder you should see a "Library" folder. Depending on the type of plugin you may also find a "VST Parameters" folder and/or "MIDI Parameters" folder. The "VST Parameters" folder contains preset and parameter objects created from information provided by the plugin. The "MIDI Parameters" folder contains MIDI parameters created by Podium assuming they are supported by the plugin. This is the folder where you create additional MIDI parameters supported by the plugin.

Before creating additional MIDI parameters, check the plugin documentation to determine what MIDI messages are supported by the plugin. The plugin should preferably provide a preconfigured setup of MIDI controllers. If the plugin only supports user-assignment of controller numbers to certain parameters, then the library file will most likely not be compatible with other users' setup.

The easiest way to create new MIDI parameter objects is to copy an existing parameter and paste it for each new parameter. Open the **Parameter Properties** dialog for the new parameters and edit the **Parameter name** and **Control change number**. See the [parameters](#toc.parameters) section for a more detailed explanation of the various parameter configurations.

If there are many VST or MIDI parameters you should group them into subfolders. Create folders for things like Osc, Filter, Amp, Effects etc. Organizing the parameters into folders will help you with the overview and navigation in the track inspector parameter panel. It is also recommended to order the parameters according to the layout of the user interface.

When done, browse up to the main project and open the **Project Properties** dialog to enter a proper name for the project. The naming convention used in the Podium library is "manufacturer name - product name". Optionally add a stickie note to the device definition or mapping objects with details about configuration of the external device, website links, version number of the plugin etc. Save the project file in the proper library folder with a file name matching the project name. The file is now ready to be imported into any of your future projects using the import commands on the project page.

## <a name="toc.presets"></a>3.7. Presets

There are two types of presets. Program presets are used for selecting predefined programs in your plugins and hardware devices. Library presets contain the actual preset data either in the form of a VST plugin preset or bank file or MIDI SysEx messages.

Importing a device definition on the project page or importing a plugin directly should provide you with all the program presets that the device supports. Library presets are created by importing preset files or by using the various preset menu commands in the arrangement editor.

You use preset objects by assigning them to tracks. Whenever that track is being prepared for monitoring/playback the preset will be recalled on the device if needed.

More information on how to work with presets in arrangements can be found in the [preset panel](#toc.presetpanel) and [using presets](#toc.usingpresets) chapters.

### <a name="toc.programpresetproperties"></a>3.7.1. [](#dialog.presetasprogram)Program Preset Properties

![](images/dialog_program_preset.png)

Program presets for external devices use MIDI bank and program change messages. Program presets for plugins will normally use VST program numbers but can also be configured to use MIDI messages. Note that not all plugins support MIDI program changes. VST program numbers cannot be used to select programs on individual MIDI channels, so when using multitimbral plugins you have to use MIDI program changes for that purpose.

Some advanced MIDI devices, such as those supporting the XG format, can automate parameters for individual drum notes. If you on the same track assign a drum parameter and a drum preset configured with a limited key range, then any curve sequences playing on that track will combine the drum preset key range with the parameter to automate that specific drum sound.

### <a name="toc.librarypresetproperties"></a>3.7.2. [](#dialog.presetaslibrary)Library Preset Properties

![](images/dialog_library_preset.png)

The data contained in a library preset consists either of a VST plugin program file (.fxp) or bank file (.fxb) or binary MIDI SysEx messages (.syx).

Plugins and external hardware devices hold only a limited number of presets. You may need to store more presets than can be stored in the device. Rather than relying on loading VST bank files in your plugins or using various storage media with your hardware devices, you can opt to store the presets in your project file and have your entire collection of presets instantly available when you need them.

Just as with program presets, library presets need to be placed within the device definition folder for the device, or else they won't be available in the track inspector preset panel. To create library presets by importing preset files: Use the project window to navigate into the proper device definition folder. Optionally create a "Library" subfolder and navigate into it. Use the **Import File...** command on the **File** menu. Set the file dialog filter to All Files (\*.\*) and open the preset files.

With the two buttons in the **Library Preset Properties** dialog you can import and export the preset files, in case you need to exchange presets with other applications.

When Podium stores a plugin or SysEx preset it uses a zip packing algorithm to minimize the memory and disk space requirements. For some plugins this can drastically reduce the size to less than 1% of the unpacked preset. The byte size shown in the **Library Preset Properties** dialog is the size of the compressed data.

## <a name="toc.parameters"></a>3.8. Parameters

Parameter objects can be configured for various types of MIDI messages as well as VST plugin parameters and Podium mixer engine parameters.

You use parameter objects by assigning them to tracks with curve sequence automation, or by dragging them onto tracks to create parameter events.

More information on how to work with parameters in arrangements can be found in the [parameter panel](#toc.parameterpanel) and [parameter automation](#toc.parameterautomation) chapters.

### <a name="toc.parameterproperties"></a>3.8.1. [](#dialog.parameter)Parameter Properties

![](images/dialog_parameter.png)

The MIDI protocol defines a wide range of message types used for transmitting various sorts of information. With the **Parameter type** drop-down list you can select among these MIDI message types, as well as: Plugin Parameter, Audio Level, Audio Panning and Audio Send.

For polyphonic pressure messages you specify an associated **Note number**. This message type was designed to provide separate 'aftertouch' for each key held. Keyboards supporting polyphonic pressure are rare and often expensive. Some synthesizers uses polyphonic pressure messages in an unconventional way as an addition to control change messages.

For control change messages you specify a **Control change number**. This number is used to identify the parameter in the plugin or external device. Control change messages can transmit 7-bit values (0-127).

The dual control change message combines a pair of control change messages for a single parameter and by doing so can transmit 14-bit values (0-16383). The MIDI protocol specifies that controller numbers 0-31 are intended as the MSB values and controller numbers 32-63 the LSB counterparts. If you select the dual control change type the **Control change number** should be set to the MSB number (0-31). Podium will add 32 to this number to get the LSB number. Note that very few devices support the dual control change method.

Many devices support a larger number of parameters than is accessible with simple control change messages. To access these parameters a device may implement support for RPN/NRPN or System Exclusive messages.

RPN/NRPN is short for 'registered parameter number/non-registered parameter number'. Parameters using RPN are defined by the MIDI protocol and include generic parameters such as master-tune. NRPN definitions are entirely in the hands of the manufacturer of a device, and can be unique for each product. RPN/NRPN messages consist of a series of control change messages reserved by the MIDI protocol. Two control change numbers are used to set a current parameter number and a further two control change numbers are used to set the value of the current parameter. So when combined, you can access 16384 parameters and set their values with 14-bit resolution (0-16383). When using RPN/NRPN parameters, Podium handles all necessary transmission of control changes internally.

The **Use note number for LSB part of number** option is used for example to encode the note of a drum preset into the NRPN message. The **Data value consists only of MSB** option will skip the LSB value and only send 7-bit values.

The value definition settings allow you to restrict the range of valid values, set a default value for use by the curve editor and automation tracks, and to define a zero offset point. If you are configuring a center based parameter such as a panning position, you can specify a value range of 0-127 and a default value and zero offset of 64. Thus when displaying a curve sequence, the curve will be drawn with its base at the center.

By default plugin parameters use 32-bit floating point values ranging from zero to one. This is the resolution Podium will use if both the min and max settings for the range are set to 0. Most plugin parameters will use a limited number of value steps, such as an on/off switch, a type selector, or a dial with a 0-127 value range. The floating point values stored in the plugin and sent to Podium will be quantized accordingly. The plugin will of course accept values from Podium in the full floating point range and just round to the nearest valid value. When the number of plugin parameter value steps is known, you can enter the same number of steps in the parameter value range settings. This will make Podium remap the floating point parameter values when displaying the value in the curve editor and the mixer sliders.

The **Record as curve sequence on separate track** option should be enabled for any parameters that are suited for curve automation. If this option is disabled then parameter changes will be recorded as individual parameter events.

### <a name="toc.systemexclusivemessages"></a>3.8.2. System Exclusive Messages

Understanding and configuring SysEx messages can be a complex task and requires that you are confident with hexadecimal numbers and the MIDI protocol in general.

Podium supports dynamic SysEx messages by using a simple macro language. This allows Podium to encode parameter value and information from device mapping and preset objects into the transmitted SysEx message.

The following macro identifiers are available:

*   [value]
*   [deviceid] or [devid] or [id]
*   [variable1] or [var1] or [v1]
*   [variable2] or [var2] or [v2]
*   [channel] or [chnl]
*   [note]

You may truncate the macro names, for example [value], [val], [v] as long as the macro name is surrounded by [ ]. The macro names are not case sensitive.

You can append bit operators after the macro name. This is used to mask out bits and split up a large number in several bytes within the message. If you write a number immediately after the macro name this will be used as a bit start offset (in essence a right shift operator). A bit width can be specified by writing a colon followed by the bit width.

You can use the '|' character between elements in the message to 'OR' the numbers into a single byte.

The [device id] and [channel] are the **SysEx device ID** and MIDI output **Channel** from the **Device Mapping Properties** dialog.

The [variable1] and [variable2] can be used for alternative enumerations of the voices on a device. As an example the Yamaha SW1000XG sound card has 32 different 'parts' that are accessed through two different MIDI ports for normal channel messages. However SysEx messages use part numbers 0-31 rather than MIDI channel numbers. The SW1000XG device mappings are configured with both MIDI channel numbers and their corresponding part number in 'SysEx variable 1'. Furthermore the SW1000XG supports routing its audio channels through its built in effects, which requires the use of 'SysEx variable 2' to enumerate the alternative audio channels.

The [note] value is the low note of the key range defined in the preset object that is active on the track that sends this message. This can be used to control specific drum note voices within a drum kit.

Here is an example of a master tune message for the SW1000XG. The value is split up into 4 bytes that each holds 4 bits of the value: F0,43,10,4C,00,00,00, [val12:4], [val8:4], [val4:4], [val0:4], F7

Here is an example of 'Reverb Return Level' from the Yamaha AN1x synth. The 'OR' operator is used to combine the hex value 10 (indicating parameter message) with a 4 bit device ID: F0,43,10|[id:4],5C,10,00,41,[val],F7

### <a name="toc.folderproperties"></a>3.9. [](#dialog.folder)Folder Properties

![](images/dialog_folder.png)

*   [](#folder.name.label)**Folder &name:** The name of the folder object.


* * *

# <a name="toc.editors"></a>4. Editors

Sequences are objects that have a timeline. There are four different types: [arrangement](#toc.arrangement), [sound](#toc.sound), [note sequence](#toc.notesequence)and [curve sequence](#toc.curvesequence). All sequences can contain various types of events that place data on the timeline. Arrangements add the use of tracks to hold some types of events. Sounds additionally contain one or more channels of audio samples.

For each type of sequence there is a dedicated editor. These editors share some common features which are described in this chapter.

Typically you enter into an arrangement, and access sounds, note and curve sequences on the tracks in the arrangement editor. You access editors for these sequences either with the arrangement embedded sequence editor, or by opening separate editor windows. All sounds, note and curve sequence objects created in the arrangement editor are placed under the arrangement object in the project.

Many of the editor controls can be activated using key shortcuts and some of the tools have alternate actions when used in combination with key shortcuts. Placing the mouse over a control will show a description with mouse and key shortcuts hints on the help page.

A common feature of the editors, is that any drag action can be canceled by right-clicking before releasing the left button. This applies both to dragging objects, editing and zooming with the editor tools, dragging value dials, dragging mixer sliders and resizing panels in the editor. Canceling by right-clicking will undo the effect of the drag operation and revert to the state before the drag action was begun. If the canceled drag action was an edit to a sequence then the edit can be restored using the redo edit command.

## <a name="toc.timeline"></a>4.1. Timeline

![](images/editor_timeline.png)

The timeline ruler region at the top of the editor shows the currently displayed timeline range. The ruler shows a handle for the edit cursor and draggable bars for segment selection, punch and loop ranges. When the mouse is placed over the timeline you can use the mouse wheel to zoom in/out. Holding Shift while using the mouse wheel will scroll the timeline.

The timeline context menu has commands for setting the timeline controls based on the clicked position, the edit cursor position or the current selection. The time position is shown in the menus that use either the clicked position or the edit cursor position. The editor snap mode and quantize value will affect these positions.

If the editor is showing a sound, note or curve sequence that is opened from a sequence event in the arrangement editor, then the timeline resolution will be locked to the arrangement timeline, as will the edit cursor, punch and loop settings. Only the segment selection is independent of the arrangement. The part of the sequence timeline that extends beyond the range of the sequence event is painted with a darker background color.

Use the four **CSPL** buttons or the ruler context menu to select either cursor, segment, punch or loop edit mode. The edit mode determines which of the four is painted topmost and also which is affected when you click and drag in the ruler. For example the loop bar may be overlapped by the punch bar, in which case you need to select the loop edit mode to be able to drag the loop range.

Set the edit cursor position by dragging the handle or by clicking and dragging in the ruler using the cursor edit mode. The editors can optionally show separate edit and play cursors. The **Link Edit Cursor To Play Cursor** option is available on the timeline ruler context menu and on the editor **View** menu. When this option is disabled the editor will show separate edit and play cursors during playback. The edit cursor can be moved without affecting playback. Stopping playback will return the play cursor to the edit cursor position. Pressing the play button during playback will restart playback from edit cursor position. When the option is enabled, double-clicking in the timeline ruler starts and stops playback. When using key shortcuts to move the cursor during playback the separate edit cursor appears and there is a small pause before playback jumps to the new position. The pause gives you time to use multiple keypresses to reposition playback.

The segment, punch and loop ranges are displayed as bars with handles at the edges. Drag the top part of the bar to move the whole range, and drag the handles to resize the range.

The segment bar is only displayed if a segment is selected. The segment is highlighted by a translucent curtain that is painted on top of all regions that have a timeline.

The appearance of the punch bar depends on whether punch in and out are enabled. If only one of the punch in or out buttons are enabled, then the punch bar is extended to the edge of the timeline to indicate that recording will not punch in or punch out. The punch bar is painted with a dimmed color if neither punch in or punch out are enabled and recording mode is not activated. When recording mode is activated, areas that will be affected by recording, such as record enabled tracks, are painted with the record color.

The loop bar is painted with a dimmed color if looping is not activated. When looping is activated, the loop range is highlighted by a brighter background color in all regions that have a timeline.

#### Timeline Context Menu

*   [](#cmd.time.Cursor)**Set Cursor**: Sets edit cursor at clicked position.
*   [](#cmd.time.CursorStart)**Set Cursor at Selection Start**: Sets edit cursor at start of current selection.
*   [](#cmd.time.CursorTail)**Set Cursor at Selection End**: Sets edit cursor at end of current selection.
*   [](#cmd.time.SegmStart)**Set Segment Start**: Sets segment start at clicked position.
*   [](#cmd.time.SegmTail)**Set Segment End**: Sets segment end at clicked position.
*   [](#cmd.time.SegmCursor)**Set Segment at Cursor**: Sets closest edge of the segment range at snapped edit cursor position.
*   [](#cmd.time.SegmSelection)**Set Segment around Selection**: Sets segment range around current event selection.
*   [](#cmd.time.PunchIn)**Set Punch In**: Sets punch in at clicked position.
*   [](#cmd.time.PunchOut)**Set Punch Out**: Sets punch out at clicked position.
*   [](#cmd.time.PunchCursor)**Set Punch at Cursor**: Sets closest edge of the punch range at snapped edit cursor position.
*   [](#cmd.time.PunchInCursor)**Set Punch In at Cursor**: Sets punch in at snapped edit cursor position.
*   [](#cmd.time.PunchOutCursor)**Set Punch Out at Cursor**: Sets punch out at snapped edit cursor position.
*   [](#cmd.time.PunchSelection)**Set Punch around Selection**: Sets punch range around current selection.
*   [](#cmd.time.PunchInSelection)**Set Punch In at Selection Start**: Sets punch in at start of current selection.
*   [](#cmd.time.PunchOutSelection)**Set Punch Out at Selection End**: Sets punch out at end of current selection.
*   [](#cmd.time.LoopStart)**Set Loop Start**: Sets loop start at clicked position.
*   [](#cmd.time.LoopTail)**Set Loop End**: Sets loop end at clicked position.
*   [](#cmd.time.LoopCursor)**Set Loop at Cursor**: Sets closest edge of the loop range at snapped edit cursor position.
*   [](#cmd.time.LoopSelection)**Set Loop around Selection**: Sets loop range around current selection.
*   [](#cmd.time.ZoomFull)**Zoom Full Range**: Sets the time range to the full length of the sequence.
*   [](#cmd.time.ZoomSelection)**Zoom Selection**: Sets the time range to the current segment or event selection.
*   [](#cmd.time.ZoomSegm)**Zoom Segment Range**: Sets the time range to the segment selection range.
*   [](#cmd.time.ZoomPunch)**Zoom Punch Range**: Sets the time range to the punch range.
*   [](#cmd.time.ZoomLoop)**Zoom Loop Range**: Sets the time range to the loop range.

## <a name="toc.selection"></a>4.2. Selection

On the timeline you can use two different types of selection methods. You can select events or you can select a timeline segment. In arrangements you also have a focus track that receives key focus when there are no event or segment selections.

Selection can be done with the mouse or with key shortcuts. Edit actions will apply to the current selection. The state of the current selection and the clipboard contents determine which commands are available on the **Edit** menu and editor context menus.

Mouse selection of events can be done using the select and pencil tools. Clicking on an empty spot with the select tool will reset all selections. Clicking on an unselected event will select it and deselect other events. Clicking on an already selected event will only deselect other events when you release the button. This allows you to click on a multiple event selection and drag them to a new position. Ctrl+clicking an event will toggle selection of that event and preserve selections of other events.

Clicking on an empty spot with the select tool will start a marquee drag selection. When the mouse is released all events that overlap the marquee are selected. Holding the Shift key while clicking will start a marquee selection no matter if you click on an empty spot or an existing event. Using Shift will also preserve the existing event selection and it can be used with the pencil tool as well.

Segment selections can be made by dragging with the segment tool, or by dragging in the timeline ruler if the ruler segment edit mode is selected.

Press Ctrl+A to select all events in the sequence. Press J or Alt+J to set the segment selection to the markers that surround the edit cursor. Press Shift+J to move either the start or end edge of the segment selection to the edit cursor position. Press the arrow keys to move either the track focus or a currently selected event focus to the closest track or event.

## <a name="toc.clipboard"></a>4.3. Clipboard

In addition to the object clipboard used in the project and browser windows, there is a sequence clipboard that is accessed with the **Edit** and context menus in the editors. The sequence clipboard can store events, segments, tracks and sound channel samples.

When you paste an an event selection that you have cut or copied to the clipboard, the events are inserted starting at the current segment selection, or if there is no segment selection, at the edit cursor position. When copying track events in the arrangement editor, the events are stored with a track offset relative to the focus track. Thus you can paste events onto other tracks by moving the track focus before doing the paste.

Cutting and pasting an event selection will not change the positions of the other events in the sequence. Use segment selection to cut or copy entire segments and all events within. Events will be split if they extend across the segment edges. Pasting a clipboard segment will insert the segment at either the current segment selection, or else at the edit cursor position. Existing events that extend across the insert position will be split and the last part moved to the end of the inserted segment.

The track context menu has a submenu with clipboard commands.

## <a name="toc.edithistory"></a>4.4. Edit History

Edit actions are logged in a history list for each sequence object. The undo and redo toolbar buttons and the Ctrl+Z and Ctrl+Y key shortcuts will step back and forth in the history. The maximum number of logged actions can be defined in the **Preferences** dialog.

You can also access the edit history using the undo and redo menus. The menus show each undo and redo edit with the time elapsed since the edit was made. Open the menus by Shift+clicking or right-clicking the buttons or by using the keyboard shortcuts Alt+Z and Alt+Y respectively.

Some edit actions in the arrangement editor involves changes both to the arrangement and other sequences. The changes made to the other sequences are logged in the history of these sequences. Undoing the edit action in the arrangement editor will also undo the related edit action in the sequences, provided that you have not since made edits to the sequences in their own editors.

Note that changes that only relate to the visual layout are not logged in the edit history. This includes minimizing and hiding track lanes and track groups, resizing tracks or sound channels, zooming and scrolling.

## <a name="toc.toolbars"></a>4.5. Toolbars

This chapter describes the elements of the default edit, track, editor profile and transport toolbars. The track and editor profile toolbars are only present in the arrangement editor. The transport toolbar is only present in the arrangement editor and the standalone sound editor, since sounds, note sequences and curve sequences placed on tracks are controlled by the arrangement editor transport.

#### [](#toolbar.region)Toolbar Region

You can customize the elements in the toolbars, if you for example want to remove elements you have no need for, or if you want to join the edit and transport toolbars into one toolbar. See the [editor profiles](#toc.editorprofiles) chapter for more information about how to configure an editor profile.

You can specify the height of a toolbar in the toolbar region properties dialog. You can also adjust the height directly on the toolbar: Move the mouse cursor onto the toolbar and use the mouse wheel while holding the Ctrl key down. The elements in the toolbar will resize accordingly. Note that the **Default button size** setting in preferences controls the height of all buttons in the UI, including those in toolbars. To adjust the default button size: Move the mouse cursor onto the project window menu bar and use the mouse wheel while holding the Ctrl key down.

### <a name="toc.edittoolbar"></a>4.5.1. Edit Toolbar

![](images/editor_toolbar_edit.png)

#### Menus

*   **File menu**: See the [File menu](#toc.editorfilemenu) section.
*   **Track menu**: See the [Track menu](#toc.editortrackmenu) section. Only available in the arrangement editor.
*   **Edit menu**: See the [Edit menu](#toc.editoreditmenu) section.
*   **View menu**: See the [View menu](#toc.editorviewmenu) section.

#### [](#toolbar.undo)Undo

Undoes the previous edit. Hover the mouse cursor over the button to show a popup with a description of the next undo action.
*   Press Ctrl+Z to undo the previous edit.
*   Shift+Click or Right-click the button, or press Alt+Z, to show a menu with all undoable edits. Each edit has a timestamp that shows the time elapsed since the edit was made. Select an edit to undo all up to and including that edit.

#### [](#toolbar.redo)Redo

Redoes the next edit that was previously undone. Hover the mouse cursor over the button to show a popup with a description of the next redo action.
*   Press Ctrl+Y to redo the next edit.
*   Shift+Click or Right-click the button, or press Alt+Y, to show a menu with all the redoable edits. Each edit has a timestamp that shows the time elapsed since the edit was made. Select an edit to redo all up to and including that edit.

#### Tool Buttons

The selected tool button will determine the primary edit function of the left mouse button. The default editor profiles contain a subset of the available tool buttons. Some of the actions you can do with a certain tool can also be done with other tools, using key modifiers. Selecting a tool for a specific purpose can speed up editing in some situations. Press D or F to cycle the currently selected tool. Enable the **Include editor tool shortcuts in timeline context menus** option on the **Application** tab in **Preferences** to allow selecting tools from the right-click menu in the editor timeline.

#### [](#toolbar.selecttool)Select Tool

*   Click and drag to select and rearrange events.
*   Double-click on a blank spot to create new events.
*   Shift+Click to start dragging a marquee selection.
*   Ctrl+Click to toggle selection or start dragging a copy.
*   Alt+Click to start dragging size of events.

#### [](#toolbar.segmenttool)Segment Tool

*   Click and drag to select a time segment. Drag segment handles in the timeline ruler to adjust the start and end position.

#### [](#toolbar.penciltool)Pencil Tool

When editing events:
*   Click and drag to select and rearrange events.
*   Click on a blank spot to create new events.
*   Click and drag edges to resize events.
*   Shift+Click to start dragging a marquee selection.
*   Ctrl+Click to toggle selection or start dragging a copy.
*   Alt+Click to start dragging size of events.

When editing sound waveform:
*   Click and drag in the channels region to draw a freehand line. Intended for detailed sample editing.

#### [](#toolbar.erasertool)Eraser Tool

When editing events:
*   Click events or track headers to delete them.
*   Shift+Click to start dragging a marquee deletion.

When editing sound waveform:
*   Click and drag in the channels region to zero the waveform. Intended for detailed sample editing.

#### [](#toolbar.scalpeltool)Scalpel Tool

When editing events:
*   Click on events to split them into two phantom copies. Use the edit menu or press Ctrl+U to convert to unique copies.

When editing sound waveform:
*   Click and drag in the channels region to draw a straight line. Intended for detailed sample editing.

#### [](#toolbar.slidetool)Slide Tool

*   Click and drag to slide the zoomed area displayed in the editor. Right-click while dragging will restore the previous zoom range.
*   Hold Shift+Alt to activate this tool.

#### [](#toolbar.zoomxytool)Zoom X/Y Tool

*   Click on a fix point in the timeline area and drag left/up to zoom in, or drag right/down to zoom out. Right-click while dragging will restore the previous zoom range.
*   Hold Ctrl+Shift+Alt to activate this tool.

#### [](#toolbar.zoomxtool)Zoom X Tool

*   Click on a fix point in the timeline area and drag left/right to zoom in/out. Right-click while dragging will restore the previous zoom range.
*   Hold Ctrl+Alt to activate this tool.

#### [](#toolbar.zoomytool)Zoom Y Tool

*   Click on a fix point in the timeline area and drag up/down to zoom in/out. Right-click while dragging will restore the previous zoom range.
*   Hold Ctrl+Shift to activate this tool.

#### [](#toolbar.particlezoom)Particle Zoom

Sets the zoomed time range so that one pixel on the screen equals one sample. Use when doing detailed sample editing.

#### [](#toolbar.snap)Snap

Toggles snapping of mouse actions on the timeline. Snap behaviour can be configured with the adjacent [grid and snap menu](#toc.gridandsnapmenu) button.
*   Press A to toggle snap on and off.
*   Press and hold Shift after starting a drag action on the timeline to temporarily disable snap.
*   Press and hold Alt after starting a drag action on the timeline to lock dragged events in horizontal or vertical position.

#### [](#toolbar.mousecursor)Mouse Cursor

Displays the position of the mouse cursor when it is positioned within the timeline area of the editor. When editing time signature based arrangements the beats are shown with a subdivision of the editor grid value. If snap mode is disabled the percentage value indicates the relative position between the two nearest grid lines.

#### [](#toolbar.segmentrange)Segment Range

Shows the start and end position of a segment selection. Use the segment tool to drag a segment selection, or use the timeline ruler to set the segment start and end positions.

*   Press Shift+J to set the segment start or end at the edit cursor.
*   Press Alt+J to select a segment around the current event selection or between the markers surrounding the edit cursor.

### <a name="toc.tracktoolbar"></a>4.5.2. Track Toolbar

![](images/editor_toolbar_track.png)

#### [](#toolbar.addtrack)Add New Track

Opens the **Track Properties** dialog for a new track. The new track will be added to the bottom of the track list. New tracks can also be added by double-clicking or right-clicking the empty space after the last track header in the tracks and mixer regions.

Right-click the button to show an options menu:

*   **Add New Track**: Opens the **Track Properties** dialog for a new track added to the bottom of the track list.
*   **Add New Track from Template:** If you have saved any track templates then this option will appear followed by the list of your track templates.

#### Global Solo, Mute and Record Arm

These buttons are useful for quick overview, in case you work with a lot of tracks that don't fit on the screen at the same time.

*   [](#toolbar.globalsolo)**Global Solo**: Indicates if there are any soloed tracks. Hovering the mouse cursor over the button will show a popup listing the names of all affected tracks. Clicking the button will reset solo mode on all tracks.
*   [](#toolbar.globalmute)**Global Mute**: Indicates if there are any muted tracks. Hovering the mouse cursor over the button will show a popup listing the names of all affected tracks. Clicking the button will reset mute mode on all tracks.
*   [](#toolbar.globalrecord)**Global Record Arm**: Indicates if there are any record armed tracks. Hovering the mouse cursor over the button will show a popup listing the names of all affected tracks. Clicking the button will reset the record arm mode on all tracks.

#### [](#toolbar.tracktagbar)Track Tag Bar

Clicking the [](#toolbar.tracktagbar.tags)**Tags** button opens the **Track Tags** dialog. If there are any tags defined in the arrangement, these will be presented as buttons to the right of the **Tags** button. See the [track tags](#toc.tracktags) section for more information about track tags and how to configure them.

Clicking a tag button will select/reset the tag. Only tracks assigned with the selected tags will be shown in the tracks and mixer regions. Deselect all tag buttons to show all tracks. Selecting a tag that is part of a mutually exclusive group (buttons that are joined with no space between them) will reset other tags in the group. Ctrl+click a tag to toggle it without resetting other tags.

Each tag button has a small check button inside it. Check buttons indicate which tags are assigned to the focus track. Click a check button to assign/remove the tag on the focus track. Note that if you remove a tag from the focus track, the track may become hidden if the tag is selected.

Right-clicking a tag button will show an options menu:

*   [](#cmd.tracktag.assigntracksatcursor)**Assign Tracks with Events at Edit Cursor**: Assigns this tag with tracks that have events at the edit cursor position.
*   [](#cmd.tracktag.assigntracksinlooprange)**Assign Tracks with Events in Loop Range**: Assigns this tag with tracks that have events within the loop range.
*   [](#cmd.tracktag.solo)**Solo**: Toggles the solo state for all tracks that has this tag. The state is enabled for all tracks, if the state is off for one or more of the tagged tracks. Otherwise the state is disabled for all tracks.
*   [](#cmd.tracktag.mute)**Mute**: Toggles the mute state for all tracks that has this tag. The state is enabled for all tracks, if the state is off for one or more of the tagged tracks. Otherwise the state is disabled for all tracks.
*   [](#cmd.tracktag.recordarm)**Record Arm**: Toggles the record arm state for all tracks that has this tag. The state is enabled for all tracks, if the state is off for one or more of the tagged tracks. Otherwise the state is disabled for all tracks.
*   [](#cmd.tracktag.customize)**Customize Tag**: Opens the **Track Tags** dialog with the tag selected in the list, and key focus set to the tag name edit field.

### <a name="toc.editorprofiletoolbar"></a>4.5.3. Editor Profile Toolbar

![](images/editor_toolbar_profile.png)

The editor profile toolbar is used to quickly switch between editor profiles. In the default setup this toolbar is only included in the arrangement editor. The available arrangement editor profiles are: Tracks, Editor, Mixer, and Big Transport. The only element contained in the toolbar is the **Editor profile bar** element. 

#### [](#toolbar.editorprofilebar)Editor Profile Bar

The profile bar shows a row of buttons that represent the available editor profiles. Editor profiles are designed specifically for either arrangements, sounds, note sequences or curve sequences. Only profiles that are compatible with the editor are shown in the profile bar. In addition to the editor specific profiles you also have generic profiles, such as the **Event List** profile, which can be selected in all editors. Generic profiles are rarely used, so they are not included in the profile bar.

Click a profile button or press the 1-9 number keys to select a profile. You can also select a profile from the list in the **View** menu.

You can customize the editor profiles by right-clicking one of the profile buttons to bring up an options menu:

*   [](#cmd.editorprofile.customize)**Customize Editor Profile**: Opens the **Editor Profile Properties** dialog for the selected profile. The same command is also available for the current profile in the **View** menu.
*   [](#cmd.editorprofile.duplicate)**Duplicate Editor Profile**: Creates and inserts a copy next to the selected profile. The copy can for example be modified by stripping away regions you rarely use, in order to maximize the available vertical space for timeline editing.
*   [](#cmd.editorprofile.delete)**Delete Editor Profile**: Removes the selected profile from the setup completely. If it is the current profile, then the first available profile in the list will become the current profile.
*   [](#cmd.editorprofile.moveleft)**Move Left**: Moves the selected profile one position to the left in the profile list.
*   [](#cmd.editorprofile.moveright)**Move Right**: Moves the selected profile one position to the right in the profile list.

The toolbars in the default setup are configured so that they will fit on a small screen resolution without being truncated. If you are working with a large screen resolution, you may, for example, want to move the editor profile bar into the edit toolbar, so that you can free up some vertical space by deleting the dedicated editor profile toolbar. To do that, follow the steps listed below. Note that you will need to repeat those steps for each of the profiles in the editor profile bar.

*   Right-click a profile button and select **Customize Editor Profile** to open the profile dialog.
*   Select **Toolbar (Edit)** in the **Region list** and click **Properties** to open the toolbar dialog.
*   Scroll to the bottom of the **Layout** list and select the bottom line divider in the list.
*   Select **Align to right** in the **Elements** list and click **Insert**.
*   Select **Editor profile bar** in the **Elements** list and click **Insert**.
*   Click **OK** to close the toolbar dialog.
*   Select **Toolbar (Editor profile bar)** in the **Region list** and click **Delete**.
*   Click **OK** to close the profile dialog. If you select the profile you should see that the profile bar has moved up on the edit toolbar.

If you have created your own additional profiles for sound, note sequence and curve sequence editors, you could also use the above procedure to add the editor profile bar to those editors.

If you accidentally mess things up while experimenting with the editor layout configuration, you can retrieve the default editors by using the **Restore Default Editor Profiles** command in the **Setup** menu.

### <a name="toc.transporttoolbar"></a>4.5.4. Transport Toolbar

![](images/editor_toolbar_transport.png)

The Power, Play, Loop, Record, Metronome, Punch In and Punch Out buttons can be right-clicked to open an options menu. Most of the menu options are shortcuts to relevant options in the **Preferences** dialog.

#### [](#toolbar.power)Power

Powering On an arrangement loads plugins and starts monitoring of any MIDI and audio inputs that are assigned to tracks. Powering Off unloads plugins and stops monitoring. The power button pulsates when power is off.

_Note:_ Power is not automatically turned off if you close the arrangement editor. Only one arrangement can be powered on at a time, so powering on an arrangement will automatically power off the previous arrangement.

*   Press Ctrl+Shift+Alt+Space to toggle power on/off.

Right-click the button to show an options menu:

*   [](#cmd.toolbar.automaticpower)**&Activate Power when Opening Arrangement Editor**: Toggles option for automatically enabling power when opening an arrangement editor.

#### [](#toolbar.stop)Stop Playback

Stops playback and if the **Link Edit Cursor to Play Cursor** option is enabled the edit cursor will remain at the paused play cursor position. Pressing stop when playback is not running will return the edit cursor to the start of the arrangement.

*   Press Space to start/stop playback.
*   Press numpad Zero to stop playback.
*   Press numpad Zero twice to move the edit cursor back to start.

#### [](#toolbar.play)Start Playback

Playback will start from the edit cursor position. If the **Link Edit Cursor to Play Cursor** option in the **View** menu is disabled then clicking play during playback will restart playback from the edit cursor position.

*   Press Space to start/stop playback.
*   Press numpad Enter to start playback.

Right-click the button to show an options menu:

*   [](#cmd.toolbar.playbackstopatend)**Stop Playback when End is Reached**: Toggles option for stopping playback when end of arrangement/sound is reached.
*   [](#cmd.toolbar.playrecordpreferences)**Play/Record &Preferences**: Opens the play/record page in the preferences dialog.

#### [](#toolbar.loop)Loop

Enabling loop mode will reveal the loop region above the timeline ruler, where you can set the loop range by dragging the loop bar.

*   Click the button or press L to toggle loop mode.
*   Shift+Click the button or press Shift+L to set the loop start or end at the edit cursor position.
*   Alt+Click the button or press Alt+L to set the loop range around the current event or segment selection. If there is no selection the loop range is set between the markers surrounding the edit cursor.

Right-click the button to show an options menu. These commands are also available in the timeline ruler context menu:

*   **Set Loop at Cursor**: Sets closest edge of the loop range at snapped edit cursor position.
*   **Set Loop around Selection**: Sets loop range around current selection.

#### [](#toolbar.looprange)Loop Range

Shows the loop start/end positions. The positions are displayed with a subdivision of the time signature at the start/end position. The text is dimmed if loop is not enabled. Use the timeline ruler to set the loop start and end positions.

#### [](#toolbar.record)Record

The record button arms the arrangement for recording. Recording will start on all record armed tracks once playback is started.

*   Press K or Numpad Decimal to toggle recording mode.
*   Press R to toggle record arming of individual tracks.

Right-click the button to show an options menu:

*   [](#cmd.toolbar.recorddeactivateonstop)**Deactivate Record Mode when Playback is Stopped**: Toggles option for deactivating record mode when playback is stopped.
*   **Play/Record &Preferences**: Opens the play/record page in the preferences dialog.

#### [](#toolbar.metronome)Metronome

Outputs MIDI or audio clicks on bar and beats during playback.

*   Press U to toggle metronome mode.

Right-click the button to show an options menu:

*   [](#cmd.toolbar.metronomerollback)**&Roll Back on Playback Start**: Enables roll back of the play cursor on playback start.
*   [](#cmd.toolbar.metronomepreferences)**Metronome &Preferences**: Opens the **[Metronome](#toc.preferences.metronome)** page in the preferences dialog.

#### [](#toolbar.punchin)Punch In

When punch in is active, recording is only enabled beyond the punch in position. Enabling punch in mode will reveal the punch region above the timeline ruler, where you can set the punch range by dragging the punch bar.

*   Click the button or press I to toggle punch in mode.
*   Shift+Click the button or press Shift+I to set punch in at the edit cursor.
*   Alt+Click the button or press Alt+I to set punch in at the start of the current selection or at the marker before the edit cursor.

Right-click the button to show an options menu. These commands are also available in the timeline ruler context menu:

*   **Set Punch In at Cursor**: Sets punch in at snapped edit cursor position.
*   **Set Punch In at Selection Start**: Sets punch in at start of current selection.

#### [](#toolbar.punchout)Punch Out

When punch out is active, recording is only enabled before the punch out position. Enabling punch out mode will reveal the punch region above the timeline ruler, where you can set the punch range by dragging the punch bar.

*   Click the button or press O to toggle punch out mode.
*   Shift+Click the button or press Shift+O to set punch out at the edit cursor.
*   Alt+Click the button or press Alt+O to set punch out at the end of the current selection or at the marker after the edit cursor.

Right-click the button to show an options menu. These commands are also available in the timeline ruler context menu:

*   **Set Punch Out at Cursor**: Sets punch out at snapped edit cursor position.
*   **Set Punch Out at Selection Start**: Sets punch out at end of current selection.

#### [](#toolbar.punchrange)Punch Range

Shows the punch in/out positions. The positions are displayed with a subdivision of the time signature at the start/end position. The text is dimmed if punch in or out is not enabled. Use the timeline ruler to set the punch in/out positions.

*   Press Shift+K to set punch in or out at the edit cursor.
*   Press Alt+K to set punch in/out around the current selection or between the markers surrounding the edit cursor.

#### [](#toolbar.editcursor)Edit Cursor and Play Cursor

Shows the position of the edit/play cursor. The play cursor position is shown during playback, and the edit cursor position is shown when stopped. If the arrangement time resolution is time signature based, the time is displayed both as hours:minutes:seconds,hundreds and as bars and beats, followed by a meter that illustrates the position within the current bar. If the arrangement time resolution is linear, the time is shown as hours:minutes:seconds,hundreds only.

*   Press Q/W or numpad 4/6 to move to the previous/next grid line.
*   Press Shift+Q/W or numpad 7/9 to move to the previous/next marker, loop, punch or segment range.
*   Press Ctrl+Q/W or numpad 1/3 to move to the start/end of the current selection.

#### [](#toolbar.timesigtempo)Time Signature and Tempo

Shows the time signature and tempo at the edit/play cursor position. Use the tempo region to add or edit tempo events.

Double-clicking the field will open the properties dialog for the tempo event that is placed before or at the cursor position. If there is no tempo event, a new event will be created at the start of the arrangement. Note that, since tempo events can be configured with either time signature and/or tempo settings, the displayed time signature or tempo may be set by a previous tempo event.

#### [](#toolbar.cpuindicator)Performance Indicator

The first percentage shows how much of the available CPU time is spent waiting for the processing of plugins and audio mixing. The second percentage shows how long the engine is blocked while waiting for sound file streaming. The percentages indicate the time used in relation to the available time period before overload will occur. The percentages do not indicate actual CPU usage.

When overload occurs it can result in gaps in the audio output. If Podium detects an overload the indicator will flash with the overload color (as specified in the current color setup) to alert you that audio processing was interrupted. The overload coloring will stick in the indicator. Click the indicator to reset the overload coloring.

Things to consider when trying to optimize performance:

*   Factors that will affect performance include: available computing power, the buffer size configured for the audio interface, disk read/write access time, and other programs running on the PC.
*   The mix percentage includes the processing of plugins, but the actual CPU usage of plugins may be smaller. You can verify this with the Windows Task Manager performance graphs.
*   In order to process audio without audible gaps, the mix engine must be able to complete its processing within the time of each buffer that is requested by the audio interface. Using small buffer sizes will result in low latency, but it increases the sensitivity to CPU spikes caused by software running in high priority mode. This could be a plugin that needs to do occasional CPU intensive initialization in response to program or parameter changes, or system critical processes that needs to do file access. You will see a more frequent occurrence of performance spikes when you are using small buffer sizes.

#### [](#toolbar.midiindicator)MIDI Indicator

The upper part lights up when MIDI is received on any configured MIDI input interfaces. The bottom part lights up when MIDI is being sent out to any configured MIDI output interfaces.

### <a name="toc.additionaltoolbar"></a>4.5.5. Additional Toolbar Elements

There are additional toolbar elements that are not included in the default editor profiles. These elements are available if you customize the toolbars.

#### [](#toolbar.togglenavigator)Toggle Navigator Region

Shows/hides the navigator region.

#### [](#toolbar.togglemarker)Toggle Marker Region

Shows/hides the marker region.

#### [](#toolbar.toggletempo)Toggle Tempo Region

Shows/hides the tempo region.

#### [](#toolbar.togglevelocity)Toggle Velocity Region

Shows/hides the velocity region.

## <a name="toc.editormenus"></a>4.6. Editor Menus

### <a name="toc.editorfilemenu"></a>4.6.1. [](#editor.filemenu)File Menu

Press Alt+F to open the [](#editor.filemenu.label)**File** menu.

The following menu items are available in the arrangement editor:

*   [](#cmd.file.arrangementproperties)**Arrangement &Properties**: Opens the **[Arrangement Properties](#toc.arrangementproperties)** dialog.
*   [](#cmd.file.exportarrangementtosoundfile)**Export Arrangement to Sound File...**: Exports the bounced audio of the master track to a sound file.
*   [](#cmd.file.exportarrangementtomidifile)**Export Arrangement to MIDI File...**: Exports this arrangement to a MIDI file.
*   [](#cmd.file.deactivateallbouncetracks)**Deactivate All Bounce Tracks**: Deactivates bounce playback on all bounce tracks.
*   [](#cmd.file.renderallinactivebouncetracks)**Render All Inactive Bounce Tracks**: Renders and activates bounce playback of all inactive bounce tracks.
*   [](#cmd.file.closearrangementeditor)**Close Arrangement &Editor**: Closes the arrangement editor.
*   **Save Project**: Shortcut to the project file menu item. It is included in the arrangement editor as a convenience so that you don't have to close the editor to access the save command.
*   **Close Project**: Shortcut to the project file menu item.

The following menu items are available in the sound editor:

*   [](#cmd.file.soundproperties)**Sound &Properties**: Opens the **[Sound Properties](#toc.soundproperties)** dialog.
*   [](#cmd.file.savesound)**&Save Sound**: Saves the sound.
*   [](#cmd.file.savesoundas)**Save Sound &As...**: Saves the sound with a new name.
*   [](#cmd.file.exportsoundtosoundfile)**Export to Sound File...**: Exports the sound to a sound file.
*   [](#cmd.file.exportselectiontosoundfile)**Export Selection to Sound File...**: Exports the selected segment and selected channels to a sound file.
*   [](#cmd.file.closesoundeditor)**Close Sound &Editor**: Closes the sound editor.

The following menu items are available in the sequence editor:

*   [](#cmd.file.sequenceproperties)**Sequence &Properties**: Opens the **Sequence Properties** dialog.
*   [](#cmd.file.exportsequencetomidifile)**Export Sequence to MIDI File...**: Exports this sequence to a MIDI file.
*   [](#cmd.file.exportselectiontomidifile)**Export Selection to MIDI File...**: Exports selected events in this sequence to a MIDI file.
*   [](#cmd.file.closesequenceeditor)**Close Sequence &Editor**: Closes the sequence editor.

### <a name="toc.editortrackmenu"></a>4.6.2. [](#editor.trackmenu)Track Menu

Press Alt+T to open the [](#editor.trackmenu.label)**Track** menu.

*   [](#cmd.track.properties)**Track Properties**: Changes settings for this track.
*   [](#cmd.track.properties2)**Track Properties**: Changes settings for this track.
*   [](#cmd.track.propertiesfx)**Effect Track Properties**: Changes settings for this effect track.
*   [](#cmd.track.stickienote)**Track Stickie &Note**: Opens a stickie note window for this track.
*   [](#cmd.track.addtrack)**Add New Track**: Opens the **Track Properties** dialog for a new track added to the bottom of the track list.
*   [](#cmd.track.addtrackfromtemplate)**Add New Track from Template:** If you have saved any track templates then this option will appear followed by the list of your track templates.
*   [](#cmd.track.addchildtrack)**Add New Child Track**: Adds a new child track to the bottom of this group track.
*   [](#cmd.track.inserttrack)**Insert New Track**: Inserts a new track before this track.
*   [](#cmd.track.insertfxtrack)**New Effect Track**: Inserts a new effect track into the chain.
*   [](#cmd.track.delete)**Delete**: Deletes this track and any child parameter tracks.
*   [](#cmd.track.deletefx)**Delete**: Deletes this effect track.
*   [](#cmd.track.deleteparam)**Delete**: Deletes this parameter track.
*   [](#cmd.track.deletegroup)**Delete Group Track**: Deletes this group track.
*   [](#cmd.track.deletegroupall)**Delete Group and Child Tracks**: Deletes this group track and all child tracks.
*   [](#cmd.track.deletecomp)**Delete Composite Track**: Deletes this composite track.
*   [](#cmd.track.deletecompall)**Delete Composite and Child Tracks**: Deletes this composite track and all child tracks.
*   [](#cmd.track.unassigninput)**Unassign Input**: Unassigns the input mapping from this track.
*   [](#cmd.track.unassigndevice)**Unassign Device**: Unassigns the device mapping from this track.
*   [](#cmd.track.unassignpreset)**Unassign Preset**: Unassigns the preset from this track.
*   [](#cmd.track.unassignparam)**Unassign Parameter**: Unassigns the parameter from this track.
*   [](#cmd.track.pluginpresetlist)**Plugin Preset**:
*   [](#cmd.track.loadpluginpreset)**Load Preset File...**: Loads an fxp or fxb file into the plugin current settings.
*   [](#cmd.track.savepluginprogram)**Save Program File...**: Saves the current plugin program to an fxp file.
*   [](#cmd.track.savepluginbank)**Save Bank File...**: Saves the entire plugin program bank to an fxb file.
*   [](#cmd.track.namepluginpreset)**Edit Program Name...**: Opens a dialog where the name of the current plugin program can be edited.
*   [](#cmd.track.storepluginpreset)**Store Current Settings to Library Preset**: Stores the plugin current settings to the assigned library preset.
*   [](#cmd.track.newpluginprogram)**New Program Library Preset**: Creates a new library preset with the current plugin program and assigns it to this track.
*   [](#cmd.track.newpluginbank)**New Bank Library Preset**: Creates a new library preset with the entire plugin program bank and assigns it to this track.
*   [](#cmd.track.importpluginpreset)**Import Library Preset from File...**: Creates new library presets with imported fxp or fxb files and assigns the first preset to this track.
*   [](#cmd.track.newpluginprogramall)**Create Library Presets for All Programs**: Creates new library presets for all programs in the plugin.
*   [](#cmd.track.updatepluginlist)**Update Programs List**: Updates the programs list with the current program names in the plugin.
*   [](#cmd.track.expandall)**Expand All Groups**: Expands all child groups in this group track.
*   [](#cmd.track.collapsegroup)**Collapse Child Tracks**: Collapses all child tracks in this group track.
*   [](#cmd.track.hidegroup)**Hide Child Tracks**: Hides all child tracks in this group track.
*   [](#cmd.track.hidelane)**Hide Track Lane**: Hides the timeline lane of this track.
*   [](#cmd.track.fadergain)**Enable Gain Control**: Toggles the gain control option.
*   [](#cmd.track.faderpan)**Enable Pan Control**: Toggles the pan control option.
*   [](#cmd.track.faderaftersend)**Set Fader After Sends**: Sets the fader to control the output after the sends.
*   [](#cmd.track.faderafterfx)**Set Fader After Effects**: Sets the fader to control the output after the effect chain.
*   [](#cmd.track.faderbeforefx)**Set Fader Before Effects**: Sets the fader to control the output before the effect chain.
*   [](#cmd.track.faderat)**Set Fader At**
*   [](#cmd.track.meterpeak)**Enable Peak Meter**: Toggles the peak meter option.
*   [](#cmd.track.meterrms)**Enable RMS Meter**: Toggles the RMS meter option.
*   [](#cmd.track.meteraftersend)**Set Meter After Sends**: Sets the meter to show the output after the sends.
*   [](#cmd.track.meterafterfx)**Set Meter After Effects**: Sets the meter to show the output after the effect chain.
*   [](#cmd.track.meterbeforefx)**Set Meter Before Effects**: Sets the meter to show the output before the effect chain.
*   [](#cmd.track.meterat)**Set Meter At**
*   [](#cmd.track.bounceoffline)**Enable Offline Render Bouncing**: Enables offline rendering bounce mode.
*   [](#cmd.track.bouncerealtime)**Enable Realtime Record Bouncing**: Enables realtime recording bounce mode.
*   [](#cmd.track.bounceunload)**Unload Plugins when Bounced**: Toggles option to unload plugins from memory when bounce playback is activated.
*   [](#cmd.track.bouncerender)**Render**: Renders bounced audio and activates playback of bounced audio.
*   [](#cmd.track.bouncepunch)**Render Within Punch Range**: Renders bounced audio within the punch range and activates playback of bounced audio.
*   [](#cmd.track.bouncerecord)**Arm Bounce Recording**: Toggles realtime bounce recording mode.
*   [](#cmd.track.bounceplay)**Playback Bounced Audio**: Toggles playback mode of bounced audio.
*   [](#cmd.track.bouncemove)**Move Bounced Audio to New Track**: Moves the bounced audio to a new track.
*   [](#cmd.track.bounceexport)**Export Bounced Audio to Sound File...**: Exports the bounced audio to a sound file.
*   [](#cmd.track.solo)**Solo**: Toggles solo mode.
*   [](#cmd.track.autosolo)**Automatic Solo**: Toggles automatic solo mode for soloing the track when solo is activated on other tracks.
*   [](#cmd.track.mute)**Mute**: Toggles mute mode.
*   [](#cmd.track.record)**Record Arm**: Toggles record arm mode.
*   [](#cmd.track.defaultheight1)**Set Height of All Tracks**: Sets the height of all non-parameter tracks to the height of this track.
*   [](#cmd.track.defaultheight2)**Set Height of All Parameter Tracks**: Sets the height of all parameter tracks to the height of this parameter track.
*   [](#cmd.track.options)**Options**
*   [](#cmd.track.grouptrack)**Group Track**: Toggles the group track mode for the selected track.
*   [](#cmd.track.compositetrack)**Composite Track**: Toggles the composite track mode for the selected track.
*   [](#cmd.track.saveeffecttemplate)**Save Effect Track as Template...**: Saves the selected effect track as a template for new tracks.
*   [](#cmd.track.savechaintemplate)**Save Effect Chain as Template...**: Saves the selected track chain as a template for new tracks.
*   [](#cmd.track.savetracktemplate)**Save Track as Template...**: Saves the selected track as a template for new tracks.
*   [](#cmd.track.savecomptemplate)**Save Composite Track as Template...**: Saves the selected composite track as a template for new tracks.
*   [](#cmd.track.savegrouptemplate)**Save Group Track as Template...**: Saves the selected group track as a template for new tracks.
*   [](#cmd.track.exploretemplatefolder)**Explore Templates Folder**: Opens Windows Explorer for the track templates folder.
*   [](#cmd.track.updatetemplatelist)**Update Templates List**: Updates the templates list to reflect changes made to the templates folder.
*   [](#cmd.track.showrackallparams)**Add All Rack Editor Parameters**: Adds all parameters to the embedded rack editor.
*   [](#cmd.track.showracknoparams)**Remove All Rack Editor Parameters**: Removes all parameters from the embedded rack editor.
*   [](#cmd.track.showmixernoparams)**Remove All Mixer Editor Parameters**: Removes all parameters from the embedded mixer editor.

todo:

*   [](#cmd.track.assigninput)**Assign/Move to Track**: Assigns this input to the selected track and removes it from other tracks.
*   [](#cmd.track.assigninputCopy)**Assign/Copy to Track**: Assigns this input to the selected track without removing it from other tracks.
*   [](#cmd.track.assigninputAuto)**Auto-Assign to Focus Track**: Selects this input to be auto-assigned to the focus track.
*   [](#cmd.track.assigndevice)**Assign to Track**: Assigns this device mapping to the selected track.
*   [](#cmd.track.assignpreset)**Assign to Track**: Assigns this preset to the selected track.
*   [](#cmd.track.assignparthis)**Assign to This Track**: Assigns this parameter to the selected track.
*   [](#cmd.track.assignparnew)**Assign to Separate Track**: Assigns this parameter to a separate child track.
*   [](#cmd.track.newpitchbend)**Pitch Bend**: Creates a new pitch bend parameter.
*   [](#cmd.track.newchnlpress)**Channel Pressure**: Creates a new channel pressure parameter.
*   [](#cmd.track.newpolypress)**Polyphonic Pressure**: Creates 128 new polyphonic pressure parameters.
*   [](#cmd.track.newprgchange)**Program Change**: Creates a new program change parameter.
*   [](#cmd.track.newsysex)**SysEx...**: Opens the parameter properties dialog for creating a new MIDI SysEx parameter.

### <a name="toc.editoreditmenu"></a>4.6.3. [](#editor.editmenu)Edit Menu

Press Alt+E to open the [](#editor.editmenu.label)**Edit** menu.

*   [](#cmd.edit.select)**&Select**
*   [](#cmd.edit.select.allaudio)**Select &All**: Selects all audio.
*   [](#cmd.edit.select.allaudiofrom)**Select All from Cursor**: Selects all audio starting from the edit cursor position.
*   [](#cmd.edit.select.allevents)**Select &All Events**: Selects all events.
*   [](#cmd.edit.select.allfromcursor)**Select All from Cursor**: Selects all events starting from the edit cursor position.
*   [](#cmd.edit.select.allontrack)**Select All on Track**: Selects all events on the selected track.
*   [](#cmd.edit.select.reset)**Reset Selection**: Resets current selection.
*   [](#cmd.edit.select.invert)**Invert Selection**: Inverts the selection state for all events.
*   [](#cmd.edit.select.shorterthangrid)**Select Shorter than Grid**: Selects all events with a length shorter than the editor grid value.
*   [](#cmd.edit.select.longerthangrid)**Select Longer than Grid**: Selects all events with a length longer than the editor grid value.
*   [](#cmd.edit.select.overlapping)**Select Overlapping**: Selects all events that overlap previous events.
*   [](#cmd.edit.select.eventsinsegment)**Select Events in Segment**: Selects all events starting inside the segment.

todo

*   [](#cmd.clipboard)**Clipboard**
*   [](#cmd.clip.cuttrack)**Cu&t Track**: Cuts the selected track into the clipboard.
*   [](#cmd.clip.cuttracks)**Cu&t Track Group**: Cuts the selected group and child tracks into the clipboard.
*   [](#cmd.clip.copytrack)**&Copy Track**: Copies the selected track into the clipboard.
*   [](#cmd.clip.copytracks)**&Copy Track Group**: Copies the selected group and child tracks into the clipboard.
*   [](#cmd.clip.inserttrack)**&Insert Track**: Inserts clipboard track before the selected track.
*   [](#cmd.clip.inserttracks)**&Insert Track Group**: Inserts clipboard track group before the selected track.
*   [](#cmd.clip.inserttracklast)**Add New Track from Clipboard**: Adds clipboard track to the bottom of the track list.
*   [](#cmd.clip.replaceeffectchain)**&Replace Effect Chain**: Replaces the effect chain of the selected track with the clipboard effect chain.
*   [](#cmd.clip.templates)**Templates**
*   [](#cmd.clip.templatesinsertnew)**Insert New Track**
*   [](#cmd.clip.templatesreplacechain)**Replace Effect Chain**
*   [](#cmd.clip.templatesinsertchain)**Insert Effect Chain**
*   [](#cmd.clip.cutevent)**Cut Event**: Cuts the selected event into the clipboard.
*   [](#cmd.clip.cutevents)**Cut Events**: Cuts selected events into the clipboard.
*   [](#cmd.clip.copyevent)**Copy Event**: Copies the selected event into the clipboard.
*   [](#cmd.clip.copyevents)**Copy Events**: Copies selected events into the clipboard.
*   [](#cmd.clip.insertevent)**Insert Event**: Inserts clipboard event at segment selection start or alternatively at the edit cursor position.
*   [](#cmd.clip.insertevents)**Insert Events**: Inserts clipboard events at segment selection start or alternatively at the edit cursor position.
*   [](#cmd.clip.pasteevent)**Paste Event**: Pastes clipboard event onto segment selection or alternatively at the edit cursor position.
*   [](#cmd.clip.pasteevents)**Paste Events**: Pastes clipboard events onto segment selection or alternatively at the edit cursor position.
*   [](#cmd.clip.cutsegm)**Cut Segment**: Cuts the segment to the clipboard.
*   [](#cmd.clip.copysegm)**Copy Segment**: Copies the segment to the clipboard.
*   [](#cmd.clip.insertsegm)**Insert Segment**: Inserts clipboard segment at segment selection start or alternatively at the edit cursor position.
*   [](#cmd.clip.pastesegm)**Paste Segment**: Pastes clipboard segment onto segment selection or alternatively at the edit cursor position.
*   [](#cmd.clip.insertblank)**Insert &Blank**: Inserts blank space in the segment selection.

todo

*   [](#cmd.edit.deleteevent)**Delete Event**: Deletes this event.
*   [](#cmd.edit.deleteevents)**Delete Events**: Deletes selected events.
*   [](#cmd.edit.deletesegm)**Delete Segment**: Deletes the segment and the data inside it.
*   [](#cmd.edit.cropsegm)**Crop Segment**: Deletes the data outside the segment.
*   [](#cmd.edit.bundleevents)**Bundle Events**: Bundles selected events.
*   [](#cmd.edit.unbundleevents)**Unbundle Events**: Unbundles selected events.
*   [](#cmd.edit.muteevent)**Mute Event**: Mutes this event.
*   [](#cmd.edit.muteevents)**Mute Events**: Mutes selected events.
*   [](#cmd.edit.unmuteevent)**Unmute Event**: Unmutes this event.
*   [](#cmd.edit.unmuteevents)**Unmute Events**: Unmutes selected events.
*   [](#cmd.edit.quantize)**&Quantize**: Quantizes the start position of selected events to the editor grid.
*   [](#cmd.edit.setlength)**Set Length**: Sets the length of selected events to the editor grid value.
*   [](#cmd.edit.adjusttiming)**Adjust &Timing...**: Adjusts timing of selected events.
*   [](#cmd.edit.reverttiming)**Revert Timing Adjustments**: Discards timing adjustments of selected events and restores original timing.
*   [](#cmd.edit.committiming)**Commit Timing Adjustments**: Commits timing adjustments of selected events and overwrites original timing.
*   [](#cmd.edit.resetstretch)**Reset Time-Stretch**: Resets the time-stretching of selected events.
*   [](#cmd.edit.adjustsoundevents)**Adjust Sound &Events...**: Adjusts properties of selected sound events.
*   [](#cmd.edit.adjusttransposition)**Adjust Tr&ansposition...**: Adjusts transposition of selected note events.
*   [](#cmd.edit.adjustvelocities)**Adjust &Velocities...**: Adjusts velocities of selected note events.
*   [](#cmd.edit.adjustpoints)**Adjust &Points...**: Adjusts values of selected point events.
*   [](#cmd.edit.invertnotes)**Invert Notes**: Flips the selected notes vertically.
*   [](#cmd.edit.reversenotes)**Reverse Notes**: Flips the selected notes horizontally.
*   [](#cmd.edit.invertvelocities)**Invert Velocities**: Flips the selected note velocities vertically.
*   [](#cmd.edit.reversevelocities)**Reverse Velocities**: Flips the selected note velocities horizontally.
*   [](#cmd.edit.snapleft)**Snap Left**:
*   [](#cmd.edit.snapright)**Snap Right**:
*   [](#cmd.edit.nudgeleft)**Nudge Left**:
*   [](#cmd.edit.nudgeright)**Nudge Right**:
*   [](#cmd.edit.shuffleleft)**Shuffle Left**:
*   [](#cmd.edit.shuffleright)**Shuffle Right**:
*   [](#cmd.edit.findmatchingscale)**Find Matching Scale**: Shows a dialog with a list of scales matching selected note events.
*   [](#cmd.edit.stripsilence)**Strip Silence**: Splits up selected sequence events removing blank ranges with a minimum length of the editor grid value.
*   [](#cmd.edit.crossfade)**Crossfade Overlapping**: Sets the fade-in and fade-out times on overlapping sound events.
*   [](#cmd.edit.split)**Split**: Splits selected events at the edit cursor position.
*   [](#cmd.edit.merge)**Merge**: Merges events into a single event and if necessary creates a new sequence.
*   [](#cmd.edit.beatslice)**Beat Slice...**: Splits the selected sound events at detected transient points.
*   [](#cmd.edit.clone)**Convert to Unique Copy**: Converts the phantom sequence/sound to a unique copy for this event.
*   [](#cmd.edit.crop)**Crop**: Crops the sequence/sound to the range used by the event.
*   [](#cmd.edit.clonecrop)**Convert to Unique Cropped Copy**: Converts the phantom sequence/sound to a unique cropped copy for this event.

todo

*   [](#cmd.edit.streamtopreset)**Create Library Preset from SysEx Event**: Creates a new library preset with the SysEx data of the selected event.
*   [](#cmd.edit.streamstoonepreset)**Create Library Preset from Combined SysEx Events**: Creates a new library preset with the combined SysEx data of the selected events.
*   [](#cmd.edit.streamstopresets)**Create Library Presets for Each SysEx Event**: Creates new library presets with the SysEx data for each of the selected events.
*   [](#cmd.edit.parambar)**Convert to Bar Point**: Converts selected event to bar point event.
*   [](#cmd.edit.parambars)**Convert to Bar Points**: Converts selected events to bar point events.
*   [](#cmd.edit.paramline)**Convert to Line Point**: Converts selected event to line point event.
*   [](#cmd.edit.paramlines)**Convert to Line Points**: Converts selected events to line point events.
*   [](#cmd.edit.paramspline)**Convert to Spline Point**: Converts selected event to spline point event.
*   [](#cmd.edit.paramsplines)**Convert to Spline Points**: Converts selected events to spline point events.
*   [](#cmd.edit.resetspline1)**Reset Spline Backward Tangent**: Resets the length of the backward tangent part on selected spline point events.
*   [](#cmd.edit.resetspline2)**Reset Spline Forward Tangent**: Resets the length of the forward tangent part on selected spline point events.
*   [](#cmd.edit.invertpoint)**Invert Point**: Flips the selected point event vertically.
*   [](#cmd.edit.invertpoints)**Invert Points**: Flips the selected point events vertically.
*   [](#cmd.edit.reversespline)**Reverse Point**: Flips the selected spline point event horizontally.
*   [](#cmd.edit.reversepoints)**Reverse Points**: Flips the selected point events horizontally.
*   [](#cmd.edit.tospline)**Transform to Spline Curve**: Transforms selected curve by tracing a spline curve going through the selected point events.
*   [](#cmd.edit.splinetoline)**Transform Spline Curve to Lines**: Transforms selected spline curve with interpolated line point events using the editor grid value as minimum resolution.
*   [](#cmd.edit.togridpoints)**Transform to Grid Aligned Points**: Transforms selected curve with interpolated point events aligned on the editor grid.

todo

*   [](#cmd.edit.seqdisplay)**Open Sequence Editor**: Displays this sequence with a compatible profile.
*   [](#cmd.edit.seqproperties)**Sequence Properties**: Changes settings for this sequence.
*   [](#cmd.edit.snddisplay)**Open Sound Editor**: Displays this sound with a compatible profile.
*   [](#cmd.edit.sndproperties)**Sound Properties**: Changes settings for this sound.
*   [](#cmd.edit.soundeventproperties)**Sound Event Properties**: Changes settings for this sound event.
*   [](#cmd.edit.parameventproperties)**Parameter Event Properties**: Changes settings for this parameter event.
*   [](#cmd.edit.drumpresetproperties)**Drum Preset Properties**: Changes settings for this drum preset.

todo

*   [](#cmd.edit.zeroaudio)**Silence**: Silences the selected segment.
*   [](#cmd.edit.normalizeaudio)**Normalize**: Normalizes the selected segment.
*   [](#cmd.edit.fadeinaudio)**Fade-In**: Applies a gradual fade-in from silence on the selected segment.
*   [](#cmd.edit.fadeoutaudio)**Fade-Out**: Applies a gradual fade-out to silence on the selected segment.
*   [](#cmd.edit.invertaudio)**Invert Phase**: Inverts the phase of the selected segment.
*   [](#cmd.edit.reverseaudio)**Reverse**: Reverses the selected segment.
*   [](#cmd.edit.rotatechannels)**Rotate Channels**: Rotates the selected segment downwards through all selected channels.

### <a name="toc.editorviewmenu"></a>4.6.4. [](#editor.viewmenu)View Menu

Press Alt+V to open the [](#editor.viewmenu.label)**View** menu.

*   [](#cmd.editor.view.followfocustrack)**Follow Focus Track**: Enables automatic track scrolling to follow focus track navigation.
*   [](#cmd.editor.view.followcontrolsurface)**Follow Control Surface**: Enables automatic track scrolling to follow control surface navigation.
*   [](#cmd.editor.view.followcursor)**Follow Play Cursor**: Enables automatic timeline scrolling to follow the play cursor.
*   [](#cmd.editor.view.linkcursor)**Link Edit Cursor to Play Cursor**: Links the edit cursor to the play cursor position during playback.
*   [](#cmd.editor.view.profileproperties)**Customize Editor Profile**: Opens the editor profile properties dialog for the currently selected editor profile.
*   [](#cmd.editor.view.customizeregionlist)**Customize Region**:

### <a name="toc.gridandsnapmenu"></a>4.6.5. [](#toolbar.snapmenu)Grid and Snap Menu

Options for grid value and snap behaviour. The grid value sets the minimum spacing of the grid lines when snap is enabled. The grid value is also used by various edit menu commands. The current grid value is displayed on the menu button. Press Shift+D or Shift+F to cycle through the grid values. Press Alt+G to open the menu.

*   [](#cmd.grid.bar)**&Bar**: Sets grid value to whole bars.
*   [](#cmd.grid.1)**1/1**: Sets grid value to 1/1 note.
*   [](#cmd.grid.2)**1/&2**: Sets grid value to 1/2 note.
*   [](#cmd.grid.4)**1/&4**: Sets grid value to 1/4 note.
*   [](#cmd.grid.8)**1/&8**: Sets grid value to 1/8 note.
*   [](#cmd.grid.16)**1/&16**: Sets grid value to 1/16 note.
*   [](#cmd.grid.32)**1/&32**: Sets grid value to 1/32 note.
*   [](#cmd.grid.64)**1/&64**: Sets grid value to 1/64 note.
*   [](#cmd.grid.128)**1/128**: Sets grid value to 1/128 note.
*   [](#cmd.grid.triplet)**&Triplet**: Toggles triplet grid value.
*   [](#cmd.grid.dotted)**&Dotted**: Toggles dotted grid value.
*   [](#cmd.snap.closest)**Snap to &Closest Grid Line**: Snaps mouse clicking and dragging to the closest grid line.
*   [](#cmd.snap.previous)**Snap to &Previous Grid Line**: Snaps mouse clicking and dragging to the previous grid line.
*   [](#cmd.snap.relative)**Snap &Relative to Grid**: Snaps mouse dragging to the relative grid position of the dragged selection.
*   [](#cmd.snap.editcursor)**Snap to &Edit Cursor**: Snaps mouse clicking and dragging to the edit cursor when it is closer than one grid unit.

### <a name="toc.markermenu"></a>4.6.6. Marker Menu

Right-clicking anywhere on the marker lane will bring up the marker menu. The following menu items are available:

*   [](#cmd.marker.selectall)**Select All Markers**: Selects all marker events and deselects other types of events.

If you have right-clicked on an empty area of the timeline:

*   [](#cmd.marker.new)**New Marker... ({})**: Inserts a new marker event at the clicked position. The position is snapped if the editor snap mode is enabled. The menu item is disabled if there already is a marker event at the specified position.
*   [](#cmd.marker.newatcursor)**New Marker at Cursor ({})**: Inserts a new marker event at the snapped edit cursor position. The menu item is disabled if there already is a marker event at the specified position. The menu item does not open the **Marker properties** dialog, and thus the Alt+M shortcut can be used to create markers on the fly during playback.

If you have right-clicked on an existing marker event:

*   [](#cmd.marker.setsegment)**Set Segment Selection**: Selects the segment between the clicked marker and the next marker.
*   [](#cmd.marker.setpunch)**Set Punch Range**: Sets the punch range between the clicked marker and the next marker.
*   [](#cmd.marker.setloop)**Set Loop Range**: Sets the loop range between the clicked marker and the next marker.
*   [](#cmd.marker.addpunch)**Extend Punch Range**: Extends the punch range with the range between the clicked marker and the next marker.
*   [](#cmd.marker.addloop)**Extend Loop Range**: Extends the loop range with the range between the clicked marker and the next marker.
*   **Delete Event** or **Delete Events**: Deletes any selected events.
*   [](#cmd.marker.properties)**Marker Properties**: Opens the **Marker Properties** dialog for the clicked marker event.

### <a name="toc.tempomenu"></a>4.6.7. Tempo Menu

Right-clicking anywhere on the tempo lane will bring up the tempo menu. The following menu items are available:

*   [](#cmd.tempo.selectall)**Select All Tempo Events**: Selects all tempo events and deselects other types of events.

If you have right-clicked on an empty area of the timeline:

*   [](#cmd.tempo.new)**New Tempo Event... ({})**: Inserts new tempo event at clicked position.
*   [](#cmd.tempo.newatcursor)**New Tempo Event at Cursor... ({})**: Inserts new tempo event at snapped edit cursor position.
*   [](#cmd.tempo.adjustcursor)**Adjust Tempo to Align Grid at Cursor**: Adjusts the previous tempo event to make the grid lines align at the edit cursor time position. This can be used to create a tempo map based on an audio recording. The editor quantize value determines the grid snap resolution.
*   [](#cmd.tempo.adjuststretch)**Adjust Tempo and Stretch to Align Grid at Cursor**: Adjusts the previous tempo event and stretches sequences to make the grid lines align at the edit cursor time position.

If you have right-clicked on an existing tempo event:

*   **Delete Event** or **Delete Events**: Deletes any selected events.
*   [](#cmd.tempo.properties)**Tempo Event Properties**: Opens the **Tempo Event Properties** dialog for the selected tempo event.

## <a name="toc.slidingzooming"></a>4.7. Sliding and Zooming

This chapter describes the different methods you can use to slide and zoom the timeline area in the editors.

### <a name="toc.navigator"></a>4.7.1. Navigator

![](images/editor_navigator.png)

#### [](#navigator.region)Navigator Region

The navigator can be used as an advanced scrollbar while simultaneously displaying a miniature overview of the full timeline.

*   The arrangement navigator displays a line for each non-hidden track, with colored blocks representing sequence events on the tracks.
*   The sound navigator shows a half-height miniature of the waveform.
*   The note sequence and curve sequence navigators show miniatures similar to those that are shown on the sequence events in the tracks region.

The navigator height can be resized by dragging the bar below the navigator. If you have a lot of tracks in your arrangement, it can be necessary to increase the height of the arrangement navigator to see all the tracks.

Zoom snapshots can be used to quickly jump between different areas in your arrangement. Each zoom snapshot stores the timeline position and zoom setting, as well as the track list vertical position and zoom setting. The snapshots are managed using the buttons to the left of the miniature.

A zoom pane is displayed on top of the miniature. The pane is painted as a frame around the current zoom range in the editor. There are several ways you can adjust the zoom range using the mouse and keyboard:

*   Click+Drag the zoom pane to slide the zoom range. In the arrangement navigator you can also drag up/down to set the vertical position in the tracks region.
*   In the arrangement navigator, click above or below the zoom pane to drag the timeline with the vertical track position locked.
*   Click+Drag the zoom pane side handles to resize the zoom range.
*   Click outside the zoom pane to set the zoom range centered on the clicked position.
*   Double-click to set zoom to full range. Double-click again to restore previous zoom range.
*   Double-click the zoom pane left/right side handles to set the zoom range to start/end.
*   Alt+Click+Drag anywhere in the navigator to select a zoom range.
*   Shift+Click+Drag anywhere in the navigator to select a zoom range without snapping.

Mouse wheel shortcuts:

*   Use mouse wheel on the zoom pane to zoom in/out locked on the mouse position.
*   Use mouse wheel outside the zoom pane to set the zoom range centered on the mouse position.

Key shortcuts for sliding:

*   Press Shift+Alt+ArrowKeys to slide.
*   Press Shift+Home/End to slide to the top/bottom.
*   Press Alt+Home/End to slide to the start/end.
*   Press Home to center the timeline on the current selection.
*   Press End to center vertically on the current selection.

Key shortcuts for zooming:

*   Press Ctrl+Shift+Alt+ArrowKeys to zoom in/out.
*   Press Ctrl+Shift+End to set vertical zoom to default.
*   Press Ctrl+Home to set timeline zoom to full range.
*   Press Ctrl+End to set timeline zoom to the current selection.

#### [](#navigator.addsnapshot)Add Zoom Snapshot

Adds the current timeline and tracks region zoom range to a new zoom snapshot, unless a snapshot already exists with that exact zoom range. Each snapshot will be shown as a numbered button on the left side of this button. Up to nine snapshots can be stored for each arrangement.

Right-click to show the options menu:

*   [](#cmd.navigator.newtimeoffset)**New Timeline Offset Snapshot**: Adds a new snapshot with only the timeline offset option enabled.
*   [](#cmd.navigator.newtimezoom)**New Timeline Zoom Snapshot**: Adds a new snapshot with only the timeline zoom option enabled.
*   [](#cmd.navigator.newvertoffset)**New Vertical Offset Snapshot**: Adds a new snapshot with only the track vertical offset option enabled.
*   [](#cmd.navigator.newvertzoom)**New Vertical Zoom Snapshot**: Adds a new snapshot with only the track vertical zoom option enabled.
*   [](#cmd.navigator.loaddefaults)**Load Default Snapshots**: Loads the default snapshots into this arrangement.
*   [](#cmd.navigator.savedefaults)**Save As Default Snapshots**: Saves the snapshots and the current zoom settings as defaults for new arrangements.

#### [](#navigator.snapshot)Zoom Snapshot

The button is shown as selected when the current zoom range matches the range stored in the snapshot. If you hover the mouse cursor over a snapshot button, the snapshot zoom range will be highlighted on the navigator miniature.

*   Click to recall zoom snapshot. Click again to restore previous zoom range.
*   Ctrl+Click to overwrite snapshot with current zoom range.
*   Alt+Click to remove snapshot.
*   Press Shift+1..9 to recall a zoom snapshot.

Right-click to show the options menu:

*   [](#cmd.navigator.timeoffset)**Timeline Offset**: Enables recall of the timeline start offset from the snapshot.
*   [](#cmd.navigator.timezoom)**Timeline Zoom**: Enables recall of the timeline zoom range from the snapshot.
*   [](#cmd.navigator.vertoffset)**Vertical Offset**: Enables recall of the track vertical top offset from the snapshot.
*   [](#cmd.navigator.vertzoom)**Vertical Zoom**: Enables recall of the track vertical zoom setting from the snapshot.
*   [](#cmd.navigator.insertnew)**Insert New Snapshot**: Creates a new snapshot of the current zoom range and inserts it before the selected snapshot.
*   [](#cmd.navigator.overwrite)**Overwrite Snapshot**: Overwrites the snapshot with the current zoom range.
*   [](#cmd.navigator.delete)**Delete Snapshot**: Deletes the snapshot.
*   [](#cmd.navigator.moveleft)**Move Left**: Moves the snapshot to the left in the list of snapshots.
*   [](#cmd.navigator.moveright)**Move Right**: Moves the snapshot to the right in the list of snapshots.

### <a name="toc.scrollbars"></a>4.7.2. Scrollbars

![](images/editor_scrollbars.png)

The tracks, channels and notes regions all have a vertical scrollbar and a vertical zoom slider. Use these to get an overview of your current vertical zoom range, as well as for adjusting the position and zoom setting. You can also scroll up and down with the mouse wheel, provided that you are not holding down any key modifiers.

#### Scrollbar Region

You can insert a horizontal timeline scrollbar region in the editor profile, as an alternative to the navigator region. A scrollbar region contains: a timeline scrollbar, a timeline zoom slider, and buttons for zooming to full range and zooming to the current selection. The scrollbar shows the current zoom range in relation to the full range. Clicking the right arrow button on the scrollbar allows you to step beyond the full range, so that you can add new content with the edit tools. The zoom slider will zoom in/out fixed on the edit cursor position. When releasing the zoom slider, the handle will return to its center position, allowing you to drag the handle again to zoom further in/out.

In the default setup, the editors have been configured with a navigator instead of a scrollbar region. If you prefer the more simplistic style of a scrollbar, you can add a scrollbar region and optionally delete the navigator region. To do so, follow these steps:

*   Open the editor where you want to replace the navigator.
*   Select **Customize Editor Profile** from the **View** menu to open the profile dialog.
*   Select **Navigator** in the **Region list** and click **Delete**.
*   The next region in the list should be **Space (Texture image, drag)**. If so, click **Delete**. The purpose of this region is to separate the navigator from the regions below, as well as providing a drag region for resizing the navigator.
*   Scroll to the bottom of the **Region list** and select the bottom line divider in the list.
*   Click the **Insert new...** button and select **Scrollbar**.
*   Click **OK** to close the scrollbar dialog, and click **OK** to close the profile dialog.

#### [](#scrollbar.zoomfull)Zoom Full Range

*   Press Ctrl+Home to set timeline zoom to full range.

#### [](#scrollbar.zoomselection)Zoom Selection

*   Press Ctrl+End to set timeline zoom to the current selection.

#### [](#scrollbar.scrollbar)Timeline Scrollbar

*   Press Shift+Alt+Left/Right to slide left/right.
*   Press Alt+Home/End to slide to the start/end.
*   Press Home to center the timeline on the current selection.

#### [](#scrollbar.zoomslider)Timeline Zoom Slider

Drag the knob or click the +/- buttons to zoom in/out. The zoom will lock around the edit cursor. If the edit cursor is outside the zoom range then the edge of the zoom range is locked.

*   Press Ctrl+Alt+Left/Right to zoom in/out.

#### [](#editor.verticalscrollbar)Vertical Scrollbar

*   Press Shift+Alt+Up/Down to slide up/down.
*   Press Shift+Home/End to slide to the top/bottom.
*   Press End to center vertically on the current selection.

#### [](#editor.verticalzoomslider)Vertical Zoom Slider

Drag the knob or click the +/- buttons to zoom in/out.

*   Ctrl+Click to set zoom to default.
*   Press Ctrl+Shift+Up/Down to zoom in/out.
*   Press Ctrl+Shift+End to set vertical zoom to default.

### <a name="toc.slidezoomtools"></a>4.7.3. Slide/Zoom Tools

There are four different tools that can be used to slide/zoom the timeline area: **Slide**, **Zoom X/Y**, **Zoom X** and **Zoom Y**. The default edit toolbar includes the **Slide** and **Zoom X/Y** tools. When one of these tools are selected, you can slide/zoom either by using the mouse wheel or by clicking and dragging. The position where you place the mouse cursor will be the fix point for the zoom.

Instead of selecting a slide/zoom tool in the edit toolbar, you can temporarily activate a slide/zoom tool by holding down combinations of the Ctrl, Shift and Alt key modifiers. When releasing the keys the previously selected tool will become active again.

*   Shift+Alt: Slide tool.
*   Ctrl+Shift+Alt: Zoom X/Y tool.
*   Ctrl+Alt: Zoom X tool.
*   Ctrl+Shift: Zoom Y tool.

As you may notice, the orientation of the key combinations on the keyboard matches the direction of the zoom. When the slide tool is activated, the mouse cursor turns into a hand cursor. When a zoom tool is activated, the mouse cursor shows a magnifying glass with small + and - symbols aligned in the direction of the zoom. You can use those small + and - symbols as a hint for which direction to drag the mouse, in order to zoom in or out.

If you are dragging with the mouse to slide/zoom, you can always cancel the drag operation by right-clicking while still holding the left mouse button down. This will reset the zoom range to the state it was before you started the drag operation. This can be useful if you for example want to temporarily zoom out for an overview.

### <a name="toc.slidezoomkeyshortcuts"></a>4.7.4. Slide/Zoom Key Shortcuts

Pressing the arrow keys without other key modifiers will navigate the event selection. The timeline area will automatically slide if focus is moved to an event outside the currently displayed range.

To slide/zoom with the arrow keys, you use the same Ctrl+Shift+Alt key combinations that you use to temporarily invoke the mouse slide/zoom tools. This has the advantage that the mouse cursor turns into the slide/zoom cursors, as described in the previous section. The + and - symbols in the zoom mouse cursors can be used as a hint for which arrow key to press, in order to zoom in or out. Holding down an arrow key will repeatedly slide/zoom until you release the key.

In addition to the arrow keys, there are several other slide/zoom key shortcuts. Below is a summary of all the key shortcuts:

*   Shift+Alt+ArrowKeys: Slide.
*   Shift+Home/End: Slide to the top/bottom.
*   Alt+Home/End: Slide to the start/end.
*   Home: Center the timeline on the current selection.
*   End: Center vertically on the current selection.
*   Ctrl+Shift+Alt+ArrowKeys: Zoom in/out.
*   Ctrl+Shift+End: Set vertical zoom to default.
*   Ctrl+Home: Set timeline zoom to full range.
*   Ctrl+End: Set timeline zoom to the current selection.

## <a name="toc.arrangement"></a>4.8. Arrangement

An arrangement consists of tracks on which you assign input, output, effect and instrument devices. You organize the tracks in a hierarchy to set up how audio is routed through the tracks. On the track timeline lanes you can place sound, note and curve sequences as sequence events. Sounds will output audio into the audio routing at the track. Note and curve sequences will control the device mapping assigned to the track.

You can create the sequence events manually using the editor tools or by recording the MIDI and audio input mappings you have assigned to the tracks. You access the editors for the sound, note and curve sequences by selecting the sequence events on the tracks. You can use the sequence editor that is embedded in the arrangement editor, or you can open new editor windows.

Events in note and curve sequences do not have device specific properties. Curve sequences output relative values that are converted to true parameter values using the parameter object assigned to the track. This allows you to reuse note and curve sequences on multiple tracks with different device mappings and parameters.

### <a name="toc.arrangementproperties"></a>4.8.1. [](#dialog.arrangement)Arrangement Properties

![](images/dialog_arrangement.png)

The [](#dialog.newarrangement)**New Arrangement Properties** dialog can be opened if you enable the **Open properties dialog for new arrangement** option on the **New Project** panel. It can also be opened with the **New Arrangement...** command in the **Content** menu on the project page.

Once an arrangement has been created, you can open the **Arrangement Properties** dialog with the **File** menu in the arrangement editor, or from the arrangement right-click menu on the project page. This dialog contains a subset of the settings from the **New Arrangement Properties** dialog.

*   **Time resolution**: You can choose between using **Musical (Time signature/tempo)** time resolution or using **Linear (Sample rate)** time resolution. If you intend to arrange non-musical material or prefer to work without the restraints of time signatures, choose the linear resolution. This setting cannot be changed once the arrangement is created.
*   **Sample rate**: If you are going to use audio in your arrangement, select the sample rate that you want your audio interface to use. This setting will by default be set to the **Default sample rate** that you can specify in the **[Interfaces](#toc.interfaces.audio)** dialog.
*   **Mono panning**: If you are using mono audio sources then this setting defines the gain scaling applied to the mono signal when panned into the stereo stream. The indicated dB value is the amount that a mono signal will be dampened when panned dead center. The dampening will decrease towards 0 dB when panned full left or right. For music production a setting of -3 dB is appropriate. Without this center dampening the human ear will perceive a signal panned from side to side to be louder at the center.
*   **RMS meter scale** & **RMS meter window**: The meters on each individual audio track can be switched to show RMS meters in addition to the standard peak meters. These two settings control the RMS meter behaviour. The meter scale has options for the K-System scales **K-12**, **K-14** and **K-20**, in addition to **Peak scale (0 dB)** and **Peak scale (+3 dB)**. The meter window defines the response time of the RMS meters.
*   **Audio tracks**: Enter a number here if you want to automatically create a number of audio enabled tracks when the arrangement is created. If this is left at zero then only a master track is created. This setting is not available after the arrangement has been created.
*   **Bus sends per audio track**: If you specified to create a number of audio tracks then this setting defines how many bus sends you want to set up on each audio track. For each send, an additional bus return track will also be created.

### <a name="toc.arrangementeditor"></a>4.8.2. Arrangement Editor

![](images/intro_arrangement.png)

The default arrangement editor layout is from top to bottom: Edit toolbar, timeline ruler, marker region, tempo and time signature region, tracks region, mixer, transport toolbar.

The main part of the arrangement editor is the tracks region. At the left edge is the track inspector which shows the properties of the focus track. At the bottom edge is a resizable embedded editor which shows the editor for the last selected sequence event.

The track inspector, embedded editor and mixer can be collapsed allowing you to optimize the available screen space when arranging events on the tracks. Information about tracks and the track inspector can be found in the [tracks](#toc.tracks) chapter. Information about how to work with sequence events, automation, mixing and recording can be found in the [arranging](#toc.arranging) chapter.

The height of tracks that are neither minimized nor collapsed are defined by a combination of the vertical zoom slider position and a height scale of each individual track. Drag the zoom slider to scale the height of all tracks. The relative height scale of a track can be set by dragging the bottom of the track header or by using the zoom y or zoom x/y tool on the track header.

#### [](#embedded.region)Embedded Editor Region

*   Click+drag the title bar to adjust the height.
*   Double-click the title bar or press F8 to restore/minimize.

### <a name="toc.markers"></a>4.8.3. [](#dialog.markerevent)Marker Properties

![](images/dialog_marker.png)

Marker events can be used to identify and divide timeline sections of your arrangement. In a typical song for example, you could use marker events to indicate where the different verses and choruses begin. Marker events are shown on the lane just below the timeline ruler. Each marker is displayed as a tag where the left edge is aligned at the event time position. The name of the marker that is placed at or before the start of the displayed timeline range is shown at the left edge of the lane.

Right-clicking a marker event shows a context menu with options for the clicked event. There are commands for selecting all marker events and setting the segment, punch and loop ranges between the clicked marker and the next marker on the timeline. Right-clicking on an empty area on the timeline shows a context menu with options for inserting a new marker either at the clicked position or at the play cursor position (key shortcut Alt+M). The editor snap mode and quantize value will affect the insert positions. See the [marker menu](#toc.markermenu) section for more information.

New marker events can be inserted by double-clicking with the select tool or clicking with the pencil tool on an empty area in the timeline. Use the scalpel tool if a previous marker tag overlaps the position where you want to insert a new event.

If you have selected a marker event, press Left/Right to navigate the marker events. Press Ctrl+Left/Right to move selected events in steps of the editor quantize value. Press the Enter key to open the **Marker Properties** dialog.

Press Q/W or Numpad 7/9 to move the edit cursor to the previous or next marker event, or to the previous or next edge of the segment selection, punch or loop ranges, whichever comes first. Press Alt+J/K/L to set the segment, punch and loop ranges between the two marker events surrounding the edit cursor position.

Use the mouse wheel over the marker event lane to scroll the timeline so that it starts at the previous or next event on the lane.

### <a name="toc.timesigtemposcale"></a>4.8.4. [](#dialog.tempoevent)Tempo Event Properties

![](images/dialog_tempo_event.png)

Arrangements created with musical time resolution use tempo events to define time signature and tempo changes on the timeline. Tempo events are shown on the lane below the marker lane. The time signature and bpm value that is active at the start of the displayed timeline range is shown at the left edge of the region.

Right-clicking a tempo event shows a context menu with options for the clicked event. Right-clicking on an empty area on the timeline shows a context menu that allows you to select all tempo events, insert new tempo events and adjust tempo events so they align with an audio recording. The editor snap mode and quantize value will affect the insert positions. See the [tempo menu](#toc.tempomenu) section for more information.

As an alternative to editing tempo events in the timeline, you can double-click the tempo indicator in the transport toolbar to access the properties of the last tempo event before the current play cursor position.

If a tempo event with a time signature change is not placed on a bar line then the time signature will be in effect from the next bar. The bar and beat divisions of the time signature is visualized both by the numerals shown in the timeline ruler and by the vertical grid lines drawn in the editor.

If you have any sound events on the tracks and you insert a tempo change, you may notice that the waveform shown inside the events will compress or expand accordingly. Sounds are played at the arrangement sample rate, so changing the tempo causes the waveform to shift in relation to the bar/beat positions. If you have dragged a sound file onto a track, the event will be resized so that the entire sound still plays. If you have resized the sound event or created it with the pencil tool, the event will not be resized as the size of the event will be locked to the bar/beat positions.

If you want to extract the tempo from an imported loop file, simply insert a tempo event at the start of the loop, select the loop sound event, use the timeline ruler **Set Cursor At Selection End** command, and finally use the **Adjust Tempo to Align Grid at Cursor** command. The tempo event should now be set to the loop tempo and the position you marked with the edit cursor should be aligned on a bar/beat grid line.

To tempo map a recording of a longer live performance with tempo variations:

Align the sound event so that the first bar/beat in the recording is on a bar/beat grid line. If this position is not at the start of the recording, then also insert a tempo event at the first bar/beat position. Now move the edit cursor to the next noticeable bar/beat position in the sound and use the **Adjust Tempo to Align Grid at Cursor** command.

You now have a tempo indication of the recording. If this tempo is general for the song, and you had a pause before the recording started, you could replace the default tempo event at the start of the arrangement with this tempo, and then realign the sound event to the new bar/beat grid positions.

Repeat this procedure from start to end of the recording. Find the next position where the tempo is changing, insert a tempo event at this position, move the edit cursor to the next bar/beat position in the recording, and use the **Adjust Tempo to Align Grid at Cursor** command.

### <a name="toc.tracktags"></a>4.8.5. [](#dialog.tracktags)Track Tags

![](images/dialog_track_tags.png)

The **Track Tags** dialog is opened by clicking the **Tags** button in the track toolbar. The tags configured in this dialog are shown as tag buttons in the track toolbar.

Tags can be used to organize tracks into categories such as: instrument type, microphone placement, performer, and whatever groupings you may find useful. Selecting tag buttons in the track toolbar will show only the tagged tracks in the tracks and mixer regions.

Each track can have several tags applied. As an example, you may have a general tag group that groups your tracks into drums, guitars and vocals. Another tag group can organize tracks according to whether they were recorded with close mics or ambient mics. Depending on what you're doing in your mix, you can select the drums tag when you want to do overall work on your drum tracks, and you can select the ambient mics tag when you want to adjust the sound of all your ambient microphone recorded tracks.

*   **Tag list**: Shows the list of tags created for the arrangement. Up to 32 tags can be created for each arrangement. The buttons to the right of the list can be used to organize the list. There are key shortcuts for all the buttons, so for example Alt+A will add a new tag to the end of the list.
*   **Tag name**: The tag name is displayed on the button in the track toolbar.
*   **First tag in a mutually exclusive group**: When this is enabled on a tag, it marks the end of a previous tag group, and the start of a new tag group. Tags that are grouped will be shown as joined buttons in the track toolbar. Clicking a tag button in the group will automatically deselect other selected tags in the group. Shift+clicking a tag button allows you to select the tag without deselecting other tags.
*   **Include child tracks of tagged group tracks**: When enabled, all child tracks of a tagged group track will behave as if they were tagged as well. An example of when this option should not be selected, is the **Master** tag that is created by default in new arrangements. This tag will toggle display of the master track but not all other tracks under the master group.
*   **Tagged tracks**: Shows a list of all source and parameter tracks in the arrangement. Click the checkmark boxes to select which tracks should be tagged with the currently selected tag in the **Tag list**. If the **Include child tracks of tagged group tracks** option is enabled, then child tracks of tagged group tracks are shown with translucent checkmarks. Note that parameter tracks are always automatically included if their source track is tagged. You can however tag a parameter track without tagging its source track. The checkmarks correspond to the check buttons inside the tag buttons on the track toolbar.

## <a name="toc.sound"></a>4.9. Sound

Podium supports the Wave sound file format with 8 to 32 bit fixed point resolution and 32/64-bit floating point resolution. The multichannel extension to the Wave file format is also supported, which enables you to configure a sound to use up to a 10.1 speaker configuration or up to 32 mono channels. Normal Wave files can only be up to 4GB in size. When you save a Wave file that is larger than 4GB, Podium will use the extended RF64 Wave file format. Note that many applications that can read Wave files may not be able to read RF64 Wave files.

In addition to the Wave file format Podium also supports the AIFF/AIFF-C sound file format. If you are working with multichannel files it is recommended to use Wave files, since AIFF files don't store the speaker configuration specified in the sound properties dialog. Also, AIFF files can't be larger than 4GB. Podium saves AIFF-C files using the Intel byte-order storage implemented by Apple. This means that AIFF files saved in Podium may not load in other applications that aren't updated for the latest AIFF format extensions.

On the **[Engine](#toc.preferences.engine)** preferences tab you can select the default format used when you create new sounds in Podium. When you save a sound file with the file dialog, it will by default use this format, but you can override it by entering the proper file name extension. Wave files use the ".wav" extension, and AIFF files use either ".aif" or ".aiff".

When working with large sound files all sample data cannot be loaded into memory at once. Podium only loads the sample data when it is needed, which means when playing the sounds or when zooming in on the waveform in the editors. When the waveform is shown zoomed out beyond a certain point, Podium uses a cached image of the waveform which takes up much less memory than the real sample data. All cached images are stored in a database file named "WaveformImageCache.db" which Podium saves in the Projects folder.

After importing a sound file that does not yet have a cached image, Podium will start to create the image in a background thread. Thus when you import sound files you don't have to wait for the image to be created. As a consequence, if you enter the sound editor for a recently opened sound file, you may see the text "Profiling waveform..." in the upper left corner of the waveform display while the waveform gradually is being rendered. This does not prevent you from playing the sound or zooming in on the waveform in which case the real waveform samples at some point will be displayed.

When Podium is started it will erase any images in the WaveformImageCache.db database that have not been accessed for a year. Still, if you browse a lot of audio files the database can grow quite large. When Podium is not running, you can safely delete the WaveformImageCache.db file. The next time Podium is started it will then recreate the database file and the images will gradually be regenerated as you access the sound files.

When recording audio or editing the waveform in the sound editor the changes are stored in temporary cache files. The sound file will not be touched until you choose to save the sound. The location of the temporary cache file folder can be configured on the **[Engine](#toc.preferences.engine)** preferences tab.

If a sound object references a file that could not be found, the sound object icon shown in the project and browser windows is colored red.

### <a name="toc.soundproperties"></a>4.9.1. [](#dialog.sound)Sound Properties

![](images/dialog_sound.png)

If the sound object is created by importing a sound file then the **Filename** field shows the referenced folder and filename. If the sound object is created as a new object in the project, it initially is not linked to a sound file. When you save the project file, all unsaved sounds are assigned filenames based on the sound object names and are placed in the same folder as the project file. You can also use the sound editor **File** menu to save the sound in any folder and with any filename you desire.

The Podium project file only stores the sound object as a sound file reference. All the settings specified in the sound properties dialog, along with the wave data and any marker events, are stored in the wave file. Thus if you open a project that fails to locate the referenced sound files, the **Sound Properties** dialog will show default values and a red background in the **Filename** field. The **Relink File...** button opens a file dialog which allows you to relink the sound object to a sound file.

If the sound file is located under the same folder as the project file, then the **Relative to project path** option can be selected. This will store the sound filename with a relative path reference in the project file, which enables you to move the project folder together with the sound files to another folder location without breaking the links to the sound files.

The **Sample rate** setting shows the sample rate specified in the wave file. Changing the sample rate will not resample the wave data.

The **Speaker** combo-box can be used to set the channels and speaker options to mono, stereo or common surround configurations. You can create a custom setup by toggling individual speakers or adjusting the number of **Channels**. Selecting speaker locations are optional. You can choose to assign all channels as mono by clearing all speaker check boxes and entering the number of mono channels.

Changing the **Bit resolution**, wave length or channels/speaker configuration settings will convert the wave data when accepting the changes with the dialog **OK** button. This will reset the sound edit history. The sound file is not affected until you choose to save the sound.

### <a name="toc.soundeditor"></a>4.9.2. Sound Editor

![](images/editor_sound.png)

#### [](#channels.region)Channels Region

The sound editor shows the individual sample data channels in the sound. The channels are identified by labels in the channel headers. If the sound uses a surround speaker configuration, speaker placement miniatures are drawn beneath the channel labels.

If you accessed the sound object from the project window instead of from an arrangement, the sound is opened in a master sound editor. Compared to the slave sound editor used with arrangements, the master editor gives you a marker region, a transport toolbar, and punch and loop settings for the sound. Read more about [markers](#toc.markers) in the arrangement chapter. Marker events are saved in the wave file as a cue list, so that the markers are available if you edit the wave file in other sound editor applications. The sound punch and loop settings are saved in the Podium project file.

Clicking the particle zoom button next to the tool buttons will set the timeline zoom so that one pixel covers one sample. This is useful when doing precision editing of the waveform with the pencil tool. The pencil tool is mostly used for removing unwanted clicks in recordings. To draw silence you can alternatively use the eraser tool.

When you have made a segment selection, you can access various editing commands either from the **Edit** menu or from the timeline context menu. Use the select or segment tools to drag a segment selection. Drag the segment handles in the timeline ruler to adjust the segment selection.

Clicking the channel headers will toggle channel selection. The curtain that is drawn for a segment selection will only be drawn on selected channels. When performing an edit on a segment selection only the selected channels will be affected. This allows you for example to copy sample data from one channel, toggle channel selection and paste into another channel.

The vertical scrollbar and zoom slider control the amplitude range of the waveform displayed inside all the channel lanes. To change the relative height of the individual channel lanes you can use the zoom y or zoom x/y tool. Click and drag upwards on one of the channel headers to increase its height relative to the other channels. The height of the other channels will shrink so that all channels are always visible in the editor.

#### [](#channels.select)Select Channel

Click to toggle this channel on/off in a segment selection.

*   Shift+Click to select this channel and deselect all the other channels.

### <a name="toc.exportsoundfile"></a>4.9.3. Export to Sound File

![](images/dialog_export_to_sound_file.png)

The **Export to Sound File** dialog will appear when you select one of the export commands in the sound editor file menu, the arrangement editor file menu or the track bounce menu. Exporting allows you to quickly save the sound to a file format that you need for other applications and tools such as mp3 encoders. Exporting a sound will not affect the source sound used in the project.

The options in the dialog are:

*   **&Bit resolution:** You can select among 8 to 32 bit fixed point and 32 or 64 bit floating point formats. The bit resolution of the source sound is shown in parenthesis.
*   **&Normalize**: Enabling this option will normalize the sound before it is exported. Use this if you are exporting a single instrument recorded at a low level. You should not use the normalize option on arrangement mixes as this can degrade the quality and disturb any dithering that may have been applied in the master effect chain.

**Export...**: Once you have set the desired export options you can click this button to open a file save dialog. In the file save dialog you can specify either wave or aiff file format by selecting the corresponding file extension.

## <a name="toc.notesequence"></a>4.10. Note Sequence

Note sequences contain note events. The properties of each note event are: start time, duration, note number, attack and release velocities. Note properties are defined according to the MIDI specification, so note number and velocities are values in the range of 0 to 127.

Note sequences are placed as sequence events on tracks in an arrangement. The instrument that is active on the track will be used for playback of the note sequence and for auditioning edited notes in the note editor.

A note sequence can be phantom copied to multiple tracks and thus you can control different instruments with the same note sequence.

Note sequences are edited with the note editor.

### <a name="toc.noteeditor"></a>4.10.1. Note Editor

![](images/editor_piano_roll.png)

The note editor will be shown in the embedded editor when a note sequence event is selected. Double-clicking a note sequence event will open the editor in a separate window.

#### [](#notes.region)Notes Region

The note editor is used for editing note events as well as for editing the note map. The note map can be configured to work in either piano roll or drum map mode.

The appearance and editing behaviour can be customized in the **[Notes Region](#toc.notesregion)** dialog, which can be opened with the menu: **View > Customize Region > Notes**.

Each track contains a customizable note map where individual notes can be disabled, soloed, muted, colored and renamed. Solo and mute are only available in drum map mode. By disabling notes you can hide unused note ranges from the editor. Disabled notes are muted during playback. This makes it possible to phantom copy a single note sequence to multiple tracks, and set up each track to play different note ranges with different instruments.

The note map properties are stored for the track where the note sequence is placed. Thus editing the note map will affect all note sequences that are placed on that track. The note map editing is integrated in the note editor for convenience, as the note map is only useful in relation to the note editor. Edits to the note map are stored in the note sequence undo history, and not the arrangement undo history.

At the left side of the note editor is a button panel for setting various editor options:

#### [](#notes.menu)Note Map Options Menu

Options for managing the note map on this track.

*   [](#cmd.notes.customizemap)**Customize Note Map...**: Opens the **Note Map** dialog for this track. The dialog can also be opened by right-clicking the piano keyboard or the drum map headers.
*   [](#cmd.notes.drummode)**Drum Map Mode**: Toggles between piano roll and drum map mode for this track.
*   [](#cmd.notes.enableall)**Enable All Notes**: Enables all 128 notes in the note map on this track.
*   [](#cmd.notes.enablegm)**Enable GM Drum Kit Notes**: Enables notes within the standard GM drum kit range (D#0 to D#5) and disables all notes outside the range.
*   [](#cmd.notes.enableused)**Enable Notes Used on Track**: Enables notes that already have note events and disables all other notes. As the note map affects all notes playing on the track, all sequence events placed on the track will be included in the search for used notes.
*   [](#cmd.notes.copymap)**Copy Note Map**: Copies the current note map to the clipboard. The properties copied include note enable/solo/mute state, color and name for each note, as well as the drum map mode option.
*   [](#cmd.notes.pastemap)**Paste Note Map**: Pastes the clipboard note map to the track where the current note sequence is placed.

#### [](#notes.auditionmode)Audition Event Mode

When you select an event either with the mouse or with cursor key navigation, the selected event will be auditioned on the instrument assigned to the track. Resizing an event also auditions the note. If you click an event with the mouse the audition will stop when the mouse button is released, even if the note event duration is longer.

#### [](#notes.widemode)Wide Event Mode

Widens the clickable frame of note events so that the frame width is minimum the same size as the zoomed line height. This makes it easier to click and edit short duration events.

#### [](#notes.ghostmode)Ghost Event Mode

Shows a ghost outline of note events from other non-hidden tracks. Only notes on tracks with the same drum map mode setting will be shown, to avoid having drum notes appearing in melodic instrument tracks, and vice versa. Only notes from tracks that are currently not hidden from the track view will be shown.

*   Alt+Click a ghost event to switch the editor to the sequence containing that event.

#### [](#notes.enablemode)Note Enable Mode

todo

Toggles display of disabled notes. When the option is selected all drum map headers show an enable/disable button. When the option is deselected, all disabled drum notes are hidden. This can be used to set up a compact drum map with only the drum sounds you intend to use. In piano roll mode it can be used to remove notes above and below the note range supported by the instrument assigned to the track. Notes within the valid range can also be disabled but in that case only full disabled octaves will be hidden to avoid cutting up the piano keyboard graphics. Disabling note ranges in piano roll mode can be useful for acoustic instrument emulations that only play within a limited note range.

Each track contains a note map where individual notes can be disabled. Disabled notes are muted during playback. This feature can be used to hide unused note ranges from the editor. It can also be used to set up multiple tracks for playing different note ranges of a single sequence object.

Select the note enable mode to show both enabled and disabled notes. Right-click the piano keyboard or drum map to enable/disable notes in the Note Map dialog.

Deselect the note enable mode to hide all disabled notes. In piano roll mode only full disabled octaves will be hidden.

#### [](#grid.panel)Grid Button Panel

Clicking the buttons in this panel can be used as a shortcut for setting the grid value, as an alternative to using the **Grid and Snap menu** in the edit toolbar.

*   Ctrl+Click a grid value button to quantize the start position of selected events.
*   Alt+Click a grid value button to set the duration of selected events.
*   Press Shift+D/F to step between the grid values.

#### [](#notes.enable)Enable/Disable Note

Disabled notes are hidden from the drum map editor when the note enable mode is deselected. Disabled notes will apply to all sequences playing on this track.

*   Shift+Click to toggle note and disable all other notes.

#### [](#notes.solo)Solo Note

Soloed notes will apply to all sequences playing on this track.

*   Shift+Click to toggle solo and reset solo on other notes.

#### [](#notes.mute)Mute Note

Muted notes will apply to all sequences playing on this track.

*   Shift+Click to toggle mute and reset mute on other notes.

### <a name="toc.pianorolldrummap"></a>4.10.2. Piano Roll and Drum Map

![](images/editor_drum_map.png)

The primary difference between piano roll mode and drum map mode is the layout of the note lines. In piano roll mode the area to the left of the timeline shows a picture of a piano keyboard that is resized to align with the zoomed note line height. In drum map mode the piano keyboard is replaced with drum line headers that show the name of the note along with buttons for soloing and muting individual notes.

By default the drum map headers will show the drum names defined by the standard GM format, which is the primary format supported by most drum capable instrument plugins. If note names have been customized in the note map, then these names are shown instead of the GM names. This also applies to the piano keyboard, provided that the vertical zoom is large enough to show the names overlaid on the black and white keys.

If a VST instrument plugin supports custom note names, the plugin supplied note names will be displayed on the drum map headers and on the piano keyboard, unless the note map already has a customized note name.

The actions that occur when you click the piano keyboard or drum map headers can be customized in the **Notes Region** dialog. The following describes the default actions:

Clicking on the piano keyboard or the drum map headers will audition the note. The note will sound until the mouse is released. The mouse can be dragged up and down to play other notes. Clicking towards the left edge will audition at low velocity and clicking towards the right edge will audition at high velocity.

Click with the select tool on a note to select all events on that note and deselect all other events. Shift+click to select all events on the note and keep the selection state of other events. Ctrl+click to toggle the selection of the events on the note. Alt+click to audition the note without affecting event selection.

Click with the pencil tool on a note to add an event at the edit cursor and advance the edit cursor to the next grid line. Shift+click to advance the edit cursor without adding an event. Ctrl+click to add an event without advancing the edit cursor. Alt+click to audition the note without adding an event. If loop is enabled then the edit cursor will move back to the loop start if it is advanced to the loop end.

If you add events while playback is in progress, then the **Link Edit Cursor to Play Cursor** mode affects how events are added. This mode can be toggled with the timeline ruler right-click menu or with the Ctrl+E key shortcut. If the mode is disabled then edit cursor behaves as described above. If the mode is enabled then clicking a note works as realtime recording of events at the play cursor position. The event duration will be set according to how long you keep the mouse button pressed.

### <a name="toc.editingnoteevents"></a>4.10.3. Editing Note Events

Note events are displayed and edited almost identically in piano roll mode and drum map mode.

Note events are displayed on the timeline as blocks that are colored according to the note attack velocity. The color gradation can be defined in the **Colors** dialog. The **Notes Region** dialog also has an option for whether the track color should be applied to the note events. In drum map mode the height of the events are furthermore scaled according to the attack velocity. This makes it easier to see the velocity progression of a single drum line.

The vertical zoom resolution can be adjusted with the zoom slider in the right side panel, as well as with the standard zoom shortcuts. The note editor remembers the zoom setting separately for piano roll mode and drum map mode.

With the select tool you can double-click an empty spot to create a new note event. The new event will have a default velocity and a duration set to the editor grid value. When you single-click an empty spot with the pencil tool, the new event will take on the velocity and duration properties of any currently selected event. The note start time will be snapped if **Snap** is enabled. You can adjust the note duration by dragging the mouse before releasing the button.

With the select and pencil tools you can double-click an event to delete it. With the eraser tool you can delete an event with a single click, or by holding the shift key to drag a marquee deletion.

When you click and drag events, the default action is to move the events. Hold the Ctrl key to create copies instead. Hold the Alt key after starting the drag action to lock either the x or y position of the events depending on the drag direction. Hold the Shift key after starting the drag action to override snap.

Note events can be added by dragging MIDI files directly onto the note editor timeline. This will merge the notes from the MIDI file into the current sequence, in contrast to dropping the MIDI file on a track, which will create a new sequence object. Dropping MIDI files onto the note editor timeline enables you to build a sequence using simple elements, such as chords, arpeggios, single drum patterns, and so on. You can create your library of MIDI file elements by using the **Export to MIDI File** command in the note editor **File** menu. When you move a MIDI file over the timeline, you'll notice that the drop highlight is cut at the note under the mouse cursor. This indicates that all the notes in the MIDI file will be offset to this root note. For example, if you have a MIDI file containing a C major chord, dropping the file on a D note will create a D major chord. Holding the Alt key will override the root note offset. Holding Shift will override snap mode.

The Insert key can be used as a quick shortcut to append duplicates of selected events. The duplicates will be placed starting at the end of the last selected event. The original events will be deselected and the duplicated events will be selected, so that pressing the Insert key repeatedly will continue to append duplicates. A duplicate event will not be created if an existing event is already positioned at the place where the duplicate should be placed. If snap mode is enabled, pressing Insert will snap the duplicates relative to the next editor grid line. Press Shift+Insert to override snap. Press Ctrl+Insert to snap to the next bar, no matter what the editor snap settings are.

Press Ctrl+Left/Right to move the selected events in steps of the editor grid value. Press Ctrl+Plus/Minus to adjust note durations. Press Ctrl+Up/Down to transpose semitones. Press Shift+Up/Down to transpose octaves when using the piano roll mode. If notes in the note map are disabled/hidden in the editor then the transpose will skip past the hidden notes. Press Plus/Minus keys to adjust the attack velocities of selected events in steps of 1/16.

If multiple events are selected, any edit action will be applied to all selected events.

### <a name="toc.noteeventhotspots"></a>4.10.4. Note Event Hotspots

You can edit note events with both the select tool and pencil tool. The select tool is convenient for quickly selecting and moving events by dragging, while the pencil tool provides more ways to edit note event properties with single click and dragging.

When the pencil tool is selected, each event has up to four drag hotspots depending on the size of the event: move, resize start, resize end, and velocity.

The layout of the hotspot areas are utilizing the full available note line height. The visual frame of the events may be smaller depending on the zoom setting. The velocity dependent height of events in drum map mode will also not affect the layout of the hotspot areas. The event will be highlighted when the mouse cursor is over the clickable area of the event, and the mouse cursor will change to a resize cursor when it is over the resize or velocity hotspots.

![](images/editor_note_event_hotspots.png)

The width of the resize hotspots are 4 pixels, and the height of the velocity hotspot is 4 pixels. When the event width is less than 16 pixels the resize hotspots are cut off at the middle, and when the event height is less than 12 pixels, the velocity hotspot is not available. This is to ensure that the move hotspot does not become too small. If you are trying to edit short duration events then you can use the **Wide event mode** to have a wider clickable hotspot layout.

In addition to the pencil tool hotspots, the event can also be resized or velocity adjusted by holding the Alt key when clicking and dragging. This will work with the select tool as well. The configuration of the Alt key behaviour can be customized in the **Notes Region** dialog. By default, the Alt key will start a resize start/end action, depending on which half of the event you click. Double-clicking with the Alt key pressed will start a proportional resize action, where all selected events will resize proportional to their original size.

### <a name="toc.editingvelocity"></a>4.10.5. [](#velocity.region)Velocity Region

The velocity region provides detailed visualization and editing of note attack and release velocities. Each note event is shown as a bar where the height is the velocity and the width is the note duration. If you are using the default editor profile the height of the region can be resized by dragging the horizontal bar above the velocity region.

*   Click+Drag over note bars to set velocities.
*   Alt+Click+Drag over note bars to offset velocities. Offset amount is controlled by dragging up/down. A horizontal line is drawn along the timeline at the clicked velocity value which acts as a guide to how much offset you are applying.
*   Ctrl+Click+Drag to adjust velocities of all selected events. Up/down offsets velocities. Left/right compresses/expands dynamic range centered around the clicked velocity value.
*   Shift+Click to start dragging a marquee selection of note events within a velocity range. Note events where the top of the bar is within the marquee will be selected.

At the left side of the region there are three editing mode buttons:

*   [](#velocity.selected)**Edit Only Selected Events**: Only selected note events will be affected when dragging over note bars. Events that are not selected are drawn as dimmed bars. This option is useful for editing a single selected note event that overlaps with other events in a chord, or when editing the events on a single drum line selected by clicking a drum line header.
*   [](#velocity.attack)**Note Attack Velocity**: Shows note attack velocities and edits affect the attack velocity of note events.
*   [](#velocity.release)**Note Release Velocity**: Shows note release velocities and edits affect the release velocity of note events.

The following shortcuts will appear in the timeline context menu if the preferences option to include tool shortcuts in context menus is enabled:

*   [](#cmd.velocity.selected)**Edit Only Selected Events**: Edit only selected events.
*   [](#cmd.velocity.attack)**Note Attack Velocity**: Edit note attack velocities.
*   [](#cmd.velocity.release)**Note Release Velocity**: Edit note release velocities.

### <a name="toc.notemap"></a>4.10.6. [](#dialog.notemap)Note Map

![](images/dialog_note_map.png)

The **Note Map** dialog is opened with the **Customize Note Map...** command in the note editor note map options menu. The dialog can also be opened by right-clicking the piano keyboard or the drum map headers, in which case the dialog is opened with focus set to the clicked note number.

*   **Note list**: Lists all 128 notes with information on note/octave, assigned color and note name. Each note has a checkbox for enabling/disabling the note. If the drum map mode is enabled on the track, then the standard GM drum note names are written dimmed, unless a custom name has been entered for the note. The list supports multi selection of notes, using the standard Windows key and mouse shortcuts. The Ctrl key can be used to toggle selection. The Shift key can be used to select the range of notes between two clicked notes.
*   **Note name**: Shows the name of the first selected note in the note list. Editing the name will be applied to all selected notes.
*   **Edit next**: Moves the selection in the note list to the next note. The button can be activated with the Alt+E key shortcut. This allows you to quickly edit the names for a range of notes.
*   **Select color**: Opens the standard Windows color dialog for selecting a color for all selected notes.
*   **Reset color**: Resets any color assignments for all selected notes.
*   **Reset entire note map**: All notes are enabled, and all color and name customization is removed. Solo and mute states for drum map mode are also reset. The reset is only executed if you press **OK** when closing the dialog.
*   **Import note map file...**: Opens a file dialog which lets you select a note map file you have previously exported. By default the file dialog will open in the "Note Maps" subfolder to the Podium setup folder. Use the **Setup > Explore Setup Folder** menu command to open a Windows file explorer for managing the note map files you have saved. The note map files are plain .ini files that can be edited with a standard text editor.
*   **Export note map file...**: Opens a file dialog for saving the current note map to file.

## <a name="toc.curvesequence"></a>4.11. Curve Sequence

Curve sequences are used to automate parameters in devices or in the Podium mixer. They consist of a series of point events that connect to form a continuous curve.

Each point event can be configured as either a bar, line or spline type. A bar point maintains its value until the next point event, resulting in a stepped value curve. A line point connects to the next event in a straight line. A spline point also connects to the next event but the line can be twisted with the spline handles.

Each point event defines a relative value within an unspecified value range. When a curve sequence is placed on a track a link is established to the parameter object assigned on the track. The relative curve values are converted to true parameter values using the value range properties of the parameter object. This enables you to use a curve sequence for any kind of parameter.

During playback of line or spline point events that controls a mixer parameter, the curve values will be calculated for each sample. When controlling MIDI or plugin device parameters, a series of parameter messages are output to approximate the curve. The density of these messages depends on factors such as the parameter value range and the slope of the curve.

### <a name="toc.curveeditor"></a>4.11.1. Curve Editor

![](images/editor_curve.png)

#### [](#curve.region)Curve Region

The curve body is painted with the parameter color range as configured in the **Colors** dialog. The base line of the curve body is normally at the bottom of the editor. If the parameter uses both negative and positive values then the base line is placed at the zero value. This is the case for example with pitch bend and pan parameters. The opacity of the curve body can be configured in the editor profile.

Bar and line point events are shown with rectangular handles. Spline point events are shown with circular handles. Selected events are highlighted with the select color, both in the point event handles and the part of the curve body that is affected by the event.

The left panel shows a parameter value scale. If a single event is selected then a translucent box with its value is displayed next to the event handle.

The background of the curve editor shows an outline of the sequences placed on the parent track, which can be either notes or sound waveforms. This is helpful when aligning point events to the source material.

The select tool follows the standard behavior with a few exceptions. Click an empty area and drag to select all events on the timeline that you drag across. Hold the Shift key to start a marquee selection instead. Double-click an empty area to insert a new event. Hold down the button on the second click to drag the new event. Double-click an existing event to delete it.

With the pencil tool, click on an empty area and drag to draw a series of new point events. Existing events that you drag across will be deleted. The type of the new point events are determined by the draw mode set with the three buttons at the left edge or with the context menu. The spline draw mode will initially draw line point events but once the mouse is released the drawn curve will be digitized into a spline curve. The interval between new events will depend on how fast you drag. You can activate editor quantize snap and set the quantize value to restrict the interval.

With the eraser tool, click on an event to delete it. Click on an empty area and drag to delete all events on the timeline that you drag across. Hold the Shift key to start a marquee deletion instead.

Selected point events can be transformed to bar, line or spline types with the **Edit** menu or the context menu.

When you drag a single event, it will be dragged in real-time and restricted to the timeline between its two neighbor events. If you drag a multiple event selection, there is no timeline restriction and you can hold down the Ctrl key when dropping to create copies. Press and hold the Shift key after you have started dragging a single or multiple events, to lock either the x or y position depending on the drag direction.

Press and hold the Ctrl key when dragging or drawing new events to set the events to the default value as defined in the parameter object. Use this to reset for example pitch bend or pan parameter curves to their center position.

Press Ctrl+Left/Right to move the selected events in steps of the editor quantize value. Press Plus/Minus to adjust the value of selected events in steps of 1/32. If you have selected a single spline event, press Ctrl+Plus/Minus to adjust the tangent length, and press Alt+Plus/Minus to adjust the slope.

At the left side of the region there are three editing mode buttons:

*   [](#curve.bar)**Bar Draw Mode**: Drawing with the pencil tool will create bar point events.
*   [](#curve.line)**Line Draw Mode**: Drawing with the pencil tool will create line point events.
*   [](#curve.spline)**Spline Draw Mode**: Drawing with the pencil tool will create line point events. When the mouse is released the drawn curve will be transformed into a spline curve.

The following shortcuts will appear in the timeline context menu if the preferences option to include tool shortcuts in context menus is enabled:

*   [](#cmd.curve.bar)**Bar Draw Mode**: Drawing with the pencil tool will create bar point events.
*   [](#cmd.curve.line)**Line Draw Mode**: Drawing with the pencil tool will create line point events.
*   [](#cmd.curve.spline)**Spline Draw Mode**: Drawing with the pencil tool will create spline point events.

### <a name="toc.splines"></a>4.11.2. Splines

Spline point events specify a spline going through the point. Changes to a spline event may affect the curve drawn from the previous event if that event is a spline too.

If you have a series of bar or line point events you can digitize their curve to replace them with spline point events. Either select a segment or select multiple connecting events and use the **Digitize Spline Curve** command found on the **Edit** and context menus.

If you select a single spline event the editor will show a line representing the tangent length and slope. You edit the spline by dragging either of the two tangent handles or by using key shortcuts.

The length of the two parts of the tangent can be adjusted individually. Extending the length of a tangent will widen the curve at the point event and compress the curve at the neighbor event. Likewise a shorter tangent length will create a sharper bend in the curve. Use the **Reset Backward Tangent** and **Reset Forward Tangent** commands on the **Edit** and context menus to set the length of the tangent parts to zero.

Depending on the tangent lengths and the zoom setting, the tangent handles may overlap the event handle. To drag the event handle instead of the overlapping tangent handles, hold the Alt key while clicking the event.

If the tangent handles extend beyond the editor area you will not be able to grab them with the mouse. In this case you must use the keyboard shortcuts to edit the spline, or use the reset tangent menu commands.

## <a name="toc.editactions"></a>4.12. Edit Actions

### <a name="toc.adjusttiming"></a>4.12.1. [](#dialog.adjusttiming)Adjust Timing

![](images/dialog_adjust_timing.png)

Event timing adjustments applied with the **Quantize** and **Adjust Timing...** edit commands are stored for each event and is saved in the project file. This means you can at any point go back to the original timing if you later on regret your adjustments. When the timing has been adjusted, two new commands will appear in the **Edit** menu:

*   **Revert Timing Adjustments**: Will discard any timing changes and restore the original timing as it were created/recorded.
*   **Commit Timing Adjustments**: Will overwrite the original timing with the current timing, so that future adjustments and use of the revert command will revert to this point.

The timing adjustments are stored as offsets to the event start and length. This means that manually moving events in the editor timeline will move the original timing as well. This allows you to for example move and copy events between bars, but still be able to revert to the original relative timing.

The **Adjust Timing** dialog is opened with the **Adjust Timing...** command in the edit menu. It is available in the arrangement, note and curve editors, for arrangements that use musical time resolution.

The dialog offers three different ways to affect the timing: First the events can be gradually quantized to the grid, followed by randomization and finally swing.

*   **Grid**: Selects the grid size that is used as basis for all adjustments. Value input fields in the dialog are percentages relative to this grid size. The default option is **Editor snap grid: x**. This uses the grid value currently selected in the editor snap menu in the editor where you invoked the **Adjust Timing...** command.
*   **Quantize mode**: The selected mode will define how the strength, randomize and swing settings are applied to the start position, end position or length of events. There are five modes:  
    *   **Quantize start**: The start position is quantized, and the event lengths are not changed.
    *   **Quantize start - Quantize length**: The start position and length are quantized independently.
    *   **Quantize start - Set length**: Compared to the quantize length mode, this mode will set the event length to the grid value instead of quantizing it to the nearest multiple of the grid value.
    *   **Quantize start - Quantize end**: The start and end positions are quantized independently. This means that event lengths may change if start and end are adjusted differently.
    *   **Quantize end**: The end position is quantized, and the event lengths are not changed. This means that event start positions may change. This mode can be useful if you for example have some intro/reverse sounds that you want to align to other sounds starting on a grid line.
*   **Strength**: Sets the percentage strength of the quantization. 0% means no quantization and 100% means full quantization to the grid lines.
*   **Sensitivity**: Defines the minimum/maximum range that are quantized. Events with a position/length falling outside this range will not be quantized. Raising the minimum value allows you to keep the timing of events close to the grid line, while quantizing events that are far off the grid line. Lowering the maximum value has the opposite effect.
*   **Randomize**: Adding some randomization can be used to "humanize" notes that have a timing that sound too rigid. This is useful if you are using the mouse to add notes in the editor, rather than recording the notes.
*   **Regenerate random numbers**: Each time you open the dialog a new set of random numbers are generated. These numbers do not change as you adjust the randomize settings. Use this button to generate a new set of random numbers if you aren't satisfied with the current randomization.
*   **Swing**: Swing involves adjusting the relative timing between pairs of grid intervals. The normal use of "swing" is to slightly slow down the downbeat, and speed up the upbeat. This results in a less rigid timing that is widely used in some musical genres. Swing is often applied to 1/16 note intervals, but you can experiment with other grid settings. The swing value can be set from -90% to +90%, but normal use of swing uses the values from 0% to about +50%. If the **Quantize start** quantize mode is selected then swing is only applied to the start position and not the lengths of the events. This is useful if you are applying swing to a beat-sliced drumloop, in which case you don't want the individual drum hit slices to be resized.
*   **Calculate adjustments from original timing**: Selecting this option will disregard any previous timing adjustments, and instead redo the adjustments based on the original timing as the events were created/recorded.
*   **Apply**: Clicking the button will apply the current settings, so that further adjustments can be made iteratively without having to press **OK** and reopen the dialog. The **Calculate adjustments from original timing** option will be deselected when you click this button. Applying adjustments iteratively can be useful if you for example want to quantize the start position to 1/4 notes and quantize lengths to 1/8 notes. Note that if you have enabled **Preview**, then applying adjustments may show further changes to the events, depending on the settings.
*   **Preview**: Selecting this option will update the editor in real time when any of the settings in the dialog are changed.

### <a name="toc.adjustsoundevents"></a>4.12.2. [](#dialog.adjustsoundevents)Adjust Sound Events

![](images/dialog_adjust_sound_events.png)

### <a name="toc.adjusttransposition"></a>4.12.3. [](#dialog.adjusttransposition)Adjust Transposition

![](images/dialog_adjust_transposition.png)

### <a name="toc.adjustvelocities"></a>4.12.4. [](#dialog.adjustvelocities)Adjust Velocities

![](images/dialog_adjust_velocities.png)

### <a name="toc.adjustpoints"></a>4.12.5. [](#dialog.adjustpoints)Adjust Points

![](images/dialog_adjust_points.png)

### <a name="toc.beatslice"></a>4.12.6. [](#dialog.beatslice)Beat Slice

![](images/dialog_beat_slice.png)

The most common use of beat slicing is for manipulating drum loops. Beat slicing a drum loop does not by itself change the sound, but once you have sliced the individual beats you can quantize or manually move the beats around to change the timing of the loop. Having the beats split up also allows you to move for example kick, snare and hihats to separate tracks with individual effects processing.

Beat slicing can be performed on sound events in the arrangement editor. See the [Sound Event Properties](#toc.soundeventproperties) section for more information about the fade properties which is used by the beat slicing.

The **Beat Slice** dialog is opened with the **Beat Slice...** command in the sound event context menu or in the **Edit** menu when a sound event is selected.

*   **Transient sensitivity**: Use this to control how many slices you want. Decreasing the sensitivity will result in fewer slices.
*   **Minimum crossfade time**: Sets the minimum fade-in and fade-out time that is set up on each slice. Applying fades will prevent clicks in the sound if you later on move the slices around. The resulting slice crossfade can be longer than the specified minimum if the transient has a slow attack.
*   **Preview**: Selecting this option will update the editor in real time when any of the settings in the dialog are changed.

* * *

# <a name="toc.tracks"></a>5. Tracks

The properties of a track can be modified in the **Track Properties** dialog, on the track headers, and the [track inspector](#toc.trackinspector) in the arrangement editor.

There are no distinctly separate tracks for processing of audio and MIDI data. Instead, this is determined by the device objects assigned to a track.

## <a name="toc.trackhierarchy"></a>5.1. Track Hierarchy

Audio, MIDI, and parameter automation signals flow upwards from tracks into parent group tracks, and, depending on the signal type, thus become affected by device mappings on the group track, as well as the group track's gain and pan settings. Group tracks can be nested, meaning groups can be placed inside another group, and due to this, group tracks can also be child tracks of another parent group track. This allows for flexible solutions to routing and sub-mixing, with the signal flow arrows displayed at the left edge of track headers and at the top of mixer strips additionally providing visual confirmation of how tracks are routed.

_Tip:_ When an instrument is assigned to a group track, all note sequences placed on its child tracks will trigger the instrument - this can be especially useful for drum samplers.

When working on an arrangement, you might want to split it up into sections such as drums, vocals, and synths for pop songs, or violins, violas, cellos, basses for classical music. You may also create sub-sections in each section. This allows mixing on different levels: sections, sub-sections or individual tracks within a section. When mixing sections, it can be useful to collapse the section group tracks, so that the individual tracks within the section are not taking up space on the screen.

_Tip:_ You can set up track tags to filter or organize the track list further, and hide tracks you are not currently working on. See the [track tags](#toc.tracktags) section for more information.

## <a name="toc.trackcontrols"></a>5.2. Track Controls

![](images/editor_track_controls.png)

Track controls can be found in the track inspector, the tracks region headers and the mixer strips. The visibility and appearance of the controls can be configured with the track properties dialogs, the inspector options menu, the **Tracks Region Properties** dialog and the **Mixer Region Properties** dialog.

_Note:_ The positions of the gain/pan controls and meters can be set either before (pre) effects, after (post) effects, after bus sends, or can be manually set at any point inside the signal chain on each track by using the options on the **Fader** and **Meter** submenus of the track context menu, or the **Fader & Meter Grid** on the mixer strips. See the [track menu](#toc.editortrackmenu) and [mixing](#toc.mixing) sections for more information.

Tracks configured for audio processing display a level meter on the right side of the track header. Depending on track height and vertical zoom settings, indicator lines are shown on the meter, at -6, -12, and -24 dB. You can choose to use horizontal meters, or no meters at all, using the **Tracks Region Properties** dialog.

The following sections describe each control in detail:

#### [](#track.select)Device/Track Select

*   Click to select the device/track to be edited with the object lists.

#### [](#track.embeddededitor)Embedded Plugin Editor

*   Show/hide the embedded plugin editor.

#### [](#track.outputselector)Output Selector

Opens the output menu for selecting the audio output device mapping. This selector is only available on a top-level master track. Multiple master tracks can be created by dragging an output device mapping from the inspector device list onto the bottom empty area of the track list.

*   Click to open the output menu.
*   Right-click to open the output track menu.

#### [](#track.bounceselector)Bounce Selector

This selector is only available on bounce enabled tracks.

*   Click to open the bounce menu, also available as a submenu of the track menu.
*   Right-click to open the bounce track menu.

#### [](#track.effectselector)Effect Selector

To change the order of effects on a track, simply rearrange the effect selectors by drag-and-drop.

When a send mapping is selected a send level control will appear below the selector.

*   Click, when the selector is unassigned, to open the effect menu.
*   Click, when a plugin is assigned, to open/close the plugin editor window.
*   Click, when a bus send is assigned, to show/hide all send controls. This applies only to the selectors shown in the rack.
*   Right-click to open the effect track menu.
*   Shift+Click to toggle bypass of the effect.
*   Alt+Click to unassign the effect.
*   Click+Drag up/down to move the effect in the effect chain.

#### [](#track.neweffectselector)New Effect Selector

*   Click or Right-click to open the effect menu.

#### [](#track.sourceselector)Source Selector

*   Click, when the selector is unassigned, to open the source menu.
*   Click, when a plugin is assigned, to open/close the plugin editor window.
*   Right-click to open the source track menu.
*   Shift+Click to toggle bypass of the source.
*   Alt+Click to unassign the source.
*   Click+Drag to another track, to assign the source.

#### [](#track.paramselector)Parameter Selector

Opens the parameter menu. This selector is only available on parameter tracks. There is no bypass button next to parameter selectors, but you can mute the parameter track to disable reading automation data.

*   Click or Right-click to open the parameter menu. Select an unassigned parameter to create a new parameter track. Select an already assigned parameter to move focus to that parameter track.
*   Shift+Click or Shift+Right-click to open the parameter menu for replacing the currently assigned parameter.
*   Click+Drag to another compatible track to create a new parameter track.

#### [](#track.inputselector)Input Selector

*   Click or Right-click to open the input menu.
*   Shift+Click to toggle bypass of the input.
*   Alt+Click to unassign the input.
*   Click+Drag to another track, to move the input.

#### [](#track.collapse)Collapse

Collapses/expands all child tracks of group tracks and tracks with parameter automation. The child tracks by default collapses to thin track lanes and thin mixer strips to preserve an overview of the track hierarchy. Alternatively the child tracks can be completely hidden to save space in the editors.

*   Click or press G to collapse/expand child tracks.
*   Ctrl+Click or press Ctrl+G to hide/expand child tracks.

#### [](#track.bounce)Bounce

When track bounce mode is set to offline rendering:
*   Click or press B to toggle bounce playback. The bounce will be rendered offline when activating bounce playback.
*   Alt+Click or press Alt+B to render only within the punch range.
*   Ctrl+Click or press Ctrl+B to toggle bounce playback without rendering. Use this to compare an older bounce with changes made to the track.

When track bounce mode is set to realtime recording:
*   Click or press B to toggle bounce playback.
*   Ctrl+Click or press Ctrl+B to toggle bounce recording. Start recording/playback in the transport toolbar to record the bounce in realtime.

#### [](#track.solo)Solo

Soloing a track will ghost solo all parent tracks as well as any child tracks. Enabling the automatic solo mode will solo the track when solo is activated on other tracks.

*   Click or press S to toggle solo mode.
*   Shift+Click or press Shift+S to toggle solo mode and reset solo mode on other tracks.
*   Alt+Click or press Shift+Alt+S to toggle automatic solo mode.

#### [](#track.mute)Mute

Muting a track will ghost mute any child tracks.

*   Click or press M to toggle mute mode.
*   Shift+Click or press Shift+M to toggle mute mode and reset mute mode on other tracks.

#### [](#track.recordarm)Record Arm

*   Click or press R to toggle record arm mode.
*   Shift+Click or press Shift+R to toggle record arm mode and reset record arm mode on other tracks.
*   When the track is record armed, and an audio input is assigned on the track, the meter will show the input level instead of the track output level.

#### [](#track.minimizelane)Minimize Lane

*   Click or press H to minimize/restore track height.
*   Ctrl+Click to hide track lane (for effect tracks).

#### [](#track.bypassinput)Bypass Input

Bypassing the input turns off live monitoring of the input. Bypassing the input will not disable recording of the input.

*   Click or press X to toggle bypass of the input.

#### [](#track.bypassdevice)Bypass Device

Bypassing an instrument or effect renders the device inactive.

*   Click to toggle bypass of the device.
*   Press X to toggle bypass if no input is assigned.

#### [](#track.plugineditor)Plugin Editor

*   Click or press E to open/close the plugin editor window.

#### Output Gain

Adjusts the audio output gain of the track.

*   Double-click to open the track properties dialog with focus set to the output gain value field.
*   Shift+Click for fine-tune adjustments.
*   Ctrl+Click to reset to the default value.

#### Output Panning

Adjusts the audio output panning of the track.

On tracks with mono sources, panning is defined by the **Mono panning** setting in the **Arrangement Properties** dialog.

*   Double-click to open the track properties dialog with focus set to the output panning value field.
*   Shift+Click for fine-tune adjustments.
*   Ctrl+Click to reset to the default value.

#### Send Gain

Adjusts the send gain of the track. The send control appears when a send mapping is assigned on the track. This can be a bus send mapping or a sidechain input mapping for a plugin assigned on another track.

*   Double-click to open the track properties dialog with focus set to the send gain value field.
*   Shift+Click for fine-tune adjustments.
*   Ctrl+Click to reset to the default value.

## <a name="toc.trackproperties"></a>5.3. [](#dialog.track)Track Properties

![](images/dialog_track.png)

![](images/dialog_effect_track.png)

![](images/dialog_parameter_track.png)

There are three types of properties dialogs that are specific to the track type:

*   **Track Properties**
*   [](#dialog.effecttrack)**Effect Track Properties**
*   [](#dialog.paramtrack)**Parameter Track Properties**

The dialogs can be opened using any of the following ways:

*   Selecting **Track Properties** from the **Track** menu or the source options menu.
*   Double-clicking the track header.
*   Pressing Alt+Enter when the track has focus.
*   Clicking the **...** button in the track panel in the [track inspector](#toc.trackinspector).

The **Effect Track Properties** dialog can furthermore be opened by choosing **Effect Track Properties** from the **Effect** selector context menu.

#### [](#track.settings.label)Settings

*   [](#track.name.label)**Track &name:** If the **Use name of ...** option is enabled this field is read-only and displays the name of the currently assigned mapping or parameter.
*   [](#track.devicename.option)**Use name of device &assigned to track**: The name of any device mapping assigned to the track is automatically used wherever the track name is displayed in the [arrangement editor](#toc.arrangementeditor), mixer, or rack.
*   [](#track.paramname.option)**Use name of parameter &assigned to track**: The name of any parameter assigned to the parameter track is automatically used wherever the track name is displayed.
*   [](#track.group.option)**Use as g&roup track**: Enables the track to be used as group track. See the [track hierarchy](#toc.trackhierarchy) section for information on group tracks.
*   [](#track.comp.option)**Use as composite track**: Enables the track to be used for the specific purpose of multi-take recording and compositing, or 'comping'. See the [multi-take recording and compositing](#toc.multitakerecording) section for more information. Note that, depending on the settings in the **[Preferences](#toc.preferences)** dialog, record enabled tracks may be automatically used as composite tracks.
*   [](#track.color.option)**Track co&lor**: Setting a color will paint the track header, as well as sequences on the track with the selected color instead of the default track color. Track colors can also be selected using the [color picker](#toc.colorpicker) in the track inspector. When a group track is colored, the color will be applied to any child tracks as well, unless they are assigned a color of their own. See the [colors](#id.3m8pl9do09kz) chapter for more information on track color options.

#### [](#track.midi.label)MIDI

*   [](#track.transpose.option)**&Transpose notes:** Will transpose notes as they are sent to the instrument. This can be used to audition alternative transpositions or to create doubled tracks using the same note sequence, but with different transpositions.
*   [](#track.notetiming.option)**Randomize note timing:** Specify a randomization period for note events.
*   [](#track.notevelocity.option)**Randomize note velocity:** Specify a randomization strength of note event velocity values.

The two randomize options are applied to note events during playback, but not to notes played live on MIDI inputs. These options can be used to simulate 'human' inaccuracy, which is useful, for example, for creating an ensemble effect with multiple instruments playing the same sequence. The specified timing interval is the total time, so a note can be played from half the interval early to half the interval late. The timing randomization is furthermore influenced by note length, attack velocity and the previously randomized note start. Notes shorter than quarter notes will reduce the interval according to the note length. Attack velocities above 64 will reduce the interval with up to 50% at full velocity, simulating a more accurate timing when striking strong notes on an instrument. The note release time will be set to compensate slightly for the randomized start time. If, for example, the note start is set to be early, then the note length will be extended with half the randomized start offset. Using randomized timing requires that repeated notes have silence between them. Otherwise the start and stop of two notes may intersect, causing notes to be dropped.

_Tip:_ The track panel in the inspector provides controls for quick access to the MIDI options enabled on the track.

#### [](#track.audio.label)Audio

*   [](#track.gain.option)**Output &gain:**
*   [](#track.pan.option)**Output &panning:** These options determine whether controls for gain and panning should be displayed for the track. The value fields to the right of the options allow you to enter precise values that may otherwise be difficult to set with sliders.
*   [](#)**Bus/sidechain send gain:** The value field is only available for effect tracks assigned with a send mapping, such as a bus send or a sidechain send to an effect plugin. See the [busses](#toc.busses) section for more information.
*   [](#track.metermode.label)**&Meter mode:** The available options are: [](#track.metermode.disabled)**Disabled**, [](#track.metermode.peak)**Peak**, [](#track.metermode.rms)**RMS**, [](#track.metermode.peakandrms)**Peak + RMS**. Each track can be configured to show **Peak** and/or **RMS** meters on the track header and the mixer strip. Clicking the meter on any mixer strip will toggle RMS metering on/off. The meter options can also be set with the options on the **Meter** submenu of the track context menu. You can select to use a different RMS meter scale, such as the K-System, in the **Arrangement Properties** dialog.

## <a name="toc.tracktemplates"></a>5.4. Track Templates

Track templates can reduce repetitive work by allowing you to store tracks complete with all track properties, device object assignments, and plugin presets. Sound events, sequences, and automation data present on a track may also be included in a template. A new track created from a track template can be edited like any other track in the arrangement, as it is a unique track and not connected to the template.

To create a template from a track, open the **Track** menu by clicking the **Track** button on the toolbar, or right-clicking the track header, and choose **Save Track As Template...** (**Save Group Track As Template...** for group tracks) from the **Templates** submenu. This will open the **New Track Template** dialog, in which you can edit the name for the new template, and choose whether sounds and sequences present on the track should be included in the template, by enabling **Copy track timeline events to the template**.

Effect chains can be saved as a template by choosing **Save Effect Chain As Template...** from the **Templates** submenu on the track context menu. A single effect track can be saved as a template by right-clicking it and selecting **Save Effect Track As Template...** from the **Templates** submenu.

![](images/dialog_new_track_template.png)

A track can be created from a template by any of the following ways:

*   Selecting a template from either the **Insert New Track**, **Replace Effect Chain**, or **Insert Effect Chain** submenus of **Templates** on the track context menu.
*   Opening the context menu for the **Add new track**button on the [track toolbar](#toc.tracktoolbar), and selecting a template.
*   Selecting a template from the track list context menu.

Saving a track template will create a Podium project file containing only the device objects used by the track(s), and a single arrangement with the actual template tracks.

_Note:_ You can open a track template file like a normal project if you want to edit the template.

The default location of track templates is inside the "Zynewave Podium\Library\Track Templates" folder in your documents folder. The location of track templates can be changed on the **[Projects](#toc.preferences.projects)** preferences tab. Use the **Explore Templates Folder** command on the **Templates** submenu to open a Windows file explorer window directed to the templates folder.

If you organize your track template files in subfolders, Podium will show the files on submenus named after the folders. Changes made to the track templates folder structure will be reflected in the menus upon restarting Podium, or by using the **Update Templates List** command on the **Templates** submenu of the track context menu.

## <a name="toc.trackinspector"></a>5.5. [](#inspector.page)Track Inspector

![](images/window_inspector.png)

The track inspector is used to view detailed information about the focus track, as well as to assign device objects such as inputs, plugins, or plugin presets to tracks.

The toolbar at the top has a button for the inspector options menu as well as toggle buttons that are shortcuts to the main elements in the options menu:

*   [](#inspector.showcolorpicker)**Color Picker**: Shows the color picker.
*   [](#inspector.showrack)**Rack**: Shows the rack.
*   [](#inspector.showeditors)**Editors**: Shows embedded plugin editors in the rack.
*   [](#inspector.showlists)**Lists**: Shows the object lists.

The five object lists, namely, the **Track**, **Device**, **Preset**, **Parameter**, and **Input** panels can be opened and closed by clicking their respective panel headers, or by using key shortcuts F2-F6. If the inspector is hidden upon accessing a panel via a key shortcut, this will open the inspector and set focus to the corresponding panel. While the inspector is open, pressing F2-F6 with focus already set on the corresponding panel will close the inspector.

All object lists show information relevant to the currently selected track in the track list. To use the list panels for effect tracks, the track selection can be changed using the **Device/track select** check buttons in the rack.

Common control actions for the list panels are single-clicking to select an object, and double-clicking, choosing **Assign to Track** from the context menu, or pressing Return to assign the object to the focus track. The assigned object will be highlighted in the list by a pin icon, and the name of the object will be displayed on the panel header. If a track does not have an object assigned, it may inherit an object assigned to a parent track, in which case the name of the parent object will be shown dimmed on the panel header. Right-clicking a panel header opens the panel options menu, which gives you a shortcut to the menu without first having to open the panel.

If the focus track is unsuitable for the device mapping you want to assign, the mapping will instead be assigned to the first appropriate track in the track chain. For example, double-clicking an effect plugin mapping while the focus track has an instrument assigned will add the plugin on an effect track.

### <a name="toc.inspectoroptionsmenu"></a>5.5.1. [](#inspector.menu)Inspector Options Menu

*   [](#cmd.inspector.showcolorpicker)**Show Color Picker**: Shows the color picker in the inspector.
*   [](#cmd.inspector.showrack)**Show Rack**: Shows the rack in the inspector.
*   [](#cmd.inspector.showeditors)**Show Rack Embedded Editors**: Shows embedded plugin editors in the rack.
*   [](#cmd.inspector.showlists)**Show Object Lists**: Shows the object lists in the inspector.
*   [](#cmd.inspector.rackoptions)**Rack Options:**
*   [](#cmd.inspector.showmaster)**Show Master Chain**: Shows master chain tracks in the rack.
*   [](#cmd.inspector.showneweffect)**Show New Effect Buttons**: Shows buttons for inserting effects in the rack.
*   [](#cmd.inspector.showgain)**Show Gain Controls**: Shows gain controls in the rack.
*   [](#cmd.inspector.showpan)**Show Pan Controls**: Shows pan controls in the rack.
*   [](#cmd.inspector.showsend)**Show Send Controls**: Shows send controls in the rack.
*   [](#cmd.inspector.smallsizerack)**Small Size**: Uses smaller size font, buttons and controls in the rack.
*   [](#cmd.inspector.controltype)**Control Type**:
    *   [](#cmd.inspector.selectdial)**Dial**: Selects dial type for all controls in the inspector.
    *   [](#cmd.inspector.selectslider1)**Slider**: Selects slider with value display for all controls in the inspector.
    *   [](#cmd.inspector.selectslider2)**Slider with Value Popup**: Selects slider with value popup for all controls in the inspector.
    *   [](#cmd.inspector.selectslider3)**Slider with Value on Knob**: Selects slider with value readout on the knob for all controls in the inspector.

### <a name="toc.colorpicker"></a>5.5.2. [](#inspector.colorpicker)Color Picker

The color picker has two fields for adjusting colors in the HSL color space. The large upper field has hue mapped to the x-axis and saturation mapped to the y-axis. The bottom field has luminance mapped to the x-axis. The color picker can be used to change the colors of tracks as well as Podium user interface colors. Use the context menu to select which color is adjusted.

The **[Colors](#toc.colors)** dialog contains a group of settings that affect how track colors are applied different places in the editors. Colors assigned to group tracks will be applied to child tracks as well, unless the child tracks have a color setting of their own. Group tracks will, by default, be drawn with a luminance offset of -20 to visually separate them from child tracks inside the group. This also applies to parameter tracks, which are drawn with a luminance offset of +20.

Right-clicking opens the context menu:

*   [](#cmd.colorpicker.enable)**Enable Track Color**: Toggles the color on/off for the selected track. When deselected the default track color specified in the **[Colors](#toc.colors)** dialog is used for the track.
*   [](#cmd.colorpicker.copy)**Copy Color**: Copies the current color to the clipboard.
*   [](#cmd.colorpicker.paste)**Paste Color**: Pastes the clipboard color to the current color.
*   [](#cmd.colorpicker.adjust)**Adjust Color Of:** This label is followed by the list of colors.
*   [](#cmd.colorpicker.track)**Track**: Adjust color of the focus track.
*   [](#cmd.colorpicker.panelbackground)**Panel Background**
*   [](#cmd.colorpicker.listbackground)**Listbox Background**
*   [](#cmd.colorpicker.button)**Button**
*   [](#cmd.colorpicker.sliderknob)**Slider Knob**
*   [](#cmd.colorpicker.text)**Text**
*   [](#cmd.colorpicker.select1)**Active Selection Fill**
*   [](#cmd.colorpicker.select1text)**Active Selection Text**
*   [](#cmd.colorpicker.select2)**Inactive Selection Fill**
*   [](#cmd.colorpicker.select2text)**Inactive Selection Text**
*   [](#cmd.colorpicker.timelinefill)**Timeline Fill**
*   [](#cmd.colorpicker.timelinetext)**Timeline Text**
*   [](#cmd.colorpicker.timelinegrid)**Timeline Grid**
*   [](#cmd.colorpicker.defaulttrack)**Default Track Color**
*   [](#cmd.colorpicker.playandpower)**Play and Power**
*   [](#cmd.colorpicker.plugineditor)**Plugin Editor**
*   [](#cmd.colorpicker.bounce)**Bounce**
*   [](#cmd.colorpicker.solo)**Solo**
*   [](#cmd.colorpicker.mute)**Mute**
*   [](#cmd.colorpicker.record)**Record**
*   [](#cmd.colorpicker.overload)**Level Meter Overload**
*   [](#cmd.colorpicker.paramlo)**Parameter Gradation Lo**
*   [](#cmd.colorpicker.paramhi)**Parameter Gradation Hi**
*   [](#cmd.colorpicker.meterlo)**Level Meter Gradation Lo**
*   [](#cmd.colorpicker.meterhi)**Level Meter Gradation Hi**

### <a name="toc.rack"></a>5.5.3. [](#inspector.rack)Rack

![](images/inspector_rack.png)

The rack can be used to show and manage track effect chains, as well as to control plugin parameters without the need to open plugin editor windows.

Devices and tracks in the rack follow the track hierarchy concept, meaning signals flow from bottom to top, as indicated by the signal flow arrows on track divider lines. The rack always presents the complete signal flow starting from the focus track, up to the master track. For example, selecting a child track will also show its parent group track, along with effects on the group track.

The rack uses the same selector buttons also present on track headers and mixer strips. See the [track controls](#toc.trackcontrols) section in the tracks chapter for more information on using selectors. Gain and pan sliders are shown before (pre), after (post) effects, after bus sends, or at the point which they are set at in the track effect chain. Send effects additionally show a slider to adjust the send level.

_Note:_ The control type can be changed from default sliders with popup value display to other types on the **Control type** submenu of the inspector options menu.

Device objects, such as VST plugins, plugin presets, parameters, or input mappings, can be dragged from the object lists to appropriate selectors, or empty regions in the rack. New effects can also be added with the **+** new effect buttons, and effect tracks can be rearranged by drag-and-drop.

Select which track to edit with the object lists using the **Device/track select** check buttons to the left of selectors. These buttons are not shown when the list panels are hidden from the inspector.

A vertical scrollbar will appear in the rack if the vertical size exceeds the defined rack height, which can be adjusted by dragging the divider between the rack and the object lists. You can also hide the color picker and object lists to gain additional space for the rack.

#### Embedded Plugin Editors

Embedded plugin editors can be enabled by clicking the **Editors** button at the top of the inspector, or selecting **Show Rack Embedded Editors** from the inspector options menu.

When embedded plugin editors are enabled, a show/hide button appears to the right of each selector that holds a VST plugin. You can use these buttons to show/hide individual embedded plugin editors. Click inside the empty embedded plugin editor region, or select **Add All Rack Editor Parameters** from the device selector button right-click menu to add all available plugin parameters to the editor. A confirmation dialog will appear if there are more than 64 parameters. To manually add or remove parameters from the embedded plugin editor, enable or disable parameters from the **Add/Remove Rack Editor Parameter** submenu of the selector button context menu. These menu options are only available if embedded plugin editors are enabled.

Alternatively, you can use the parameter list in the **Parameter** panel to configure parameters to be embedded. Click the **Embedded editor parameters** button in the **Parameter** panel to show checkboxes next to each parameter in the list. The first checkbox for each parameter is used to show/hide the parameter in embedded plugin editors in the rack, and the second checkbox is for embedded plugin editors in the mixer. See the [mixing](#toc.mixing) chapter for more information on embedded editors in the mixer.

The parameters inside embedded plugin editors are displayed in list form, with a value readout and a dial to the right of each parameter. Changes made to parameters can be recorded in the same way as recording adjustments made to controls inside plugin editor windows. See the [parameter automation](#toc.parameterautomation) chapter for more information.

Zynewave plugins - zPEQ, zPitch, zReverb - are all presented using their familiar UI, integrated in the rack. The embedded zPlugin editors are automatically resized to fit the inspector width, and depending on its size, less important controls (diffusion delay times, tuning pad) may become hidden from the zReverb editor UI. See the [zPlugins](#toc.zplugins) chapter for more information.

_Note:_ Embedded plugin editor configurations are stored in the project file, and apply to all arrangements in the project.

### <a name="toc.trackpanel"></a>5.5.4. [](#inspector.trackpanel)Track Panel

![](images/inspector_panel_track.png)

The **Track** panel is accessible by key shortcut F2. The panel header displays the name of the focus track. The panel always displays the source track, even if an effect track is selected with the select buttons in the rack.

The panel contains the following buttons:

*   [](#inspector.trackmenu)**Track Menu**: Opens the track menu which is identical to the **Track** menu in the editor toolbar.
*   **B**, **S**, **M**, **R**: Used to enable or disable bounce (if available), solo, mute modes, or record arm the track.
*   [](#inspector.trackproperties)**Track Properties**: Opens the **Track Properties** dialog. Can also be opened by double-clicking the track header in the tracks and mixer regions, or by pressing Alt+Enter when the track has key focus.
*   [](#inspector.trackstickienote)**Stickie Note**: Opens the stickie note window. The contents of a note can be displayed by moving the mouse cursor on the stickie note button.

Depending on the options enabled in the **Track Properties** dialog, the **Track** panel will additionally show sliders for controlling MIDI track functions: transpose, randomize timing, and randomize velocity. See the [tracks](#toc.tracks) chapter for more information.

Located below these controls is a list of all sound events, note, or curve sequences present on the track - you can drag these directly from the list to tracks. The list also provides an alternative method for selecting and accessing properties of events on the track by use of key shortcuts. If the track contains [parameter events](#toc.parametereventautomation), dials for adjusting their value will appear alongside them in the list.

### <a name="toc.devicepanel"></a>5.5.5. [](#inspector.devicepanel)Device Panel

![](images/inspector_panel_device.png)

The **Device** panel is used for assigning devices such as VST and ReWire plugins, [hardware device definitions](#toc.hardwaredevices), bus mappings, as well as audio outputs to tracks, and is accessible by key shortcut F3. The panel header displays the name of the device mapping assigned to the focus track.

The panel contains the following buttons:

*   [](#inspector.devicemenu)**Device Menu**: Opens the device menu.
*   **Editor**: Opens the plugin editor window for the assigned plugin. Also available by pressing E when the track has key focus.
*   **Bypass**: Bypasses the device mapping. Also available by pressing X when the track has focus and has no input mapping assigned.

The device list contains all device mappings available in the current project, save for inputs. Device mappings can be dragged from the list and dropped on track headers, mixer strips, or in the rack. Dropping a device mapping on an empty region of the track list will create a new track with the mapping assigned. You can also assign devices by selecting **Assign to Track** from the list context menu, or by pressing Return when the list has key focus.

_Tip:_ You can drag a folder from the device list to an empty region of the track list to create a group track along with child tracks for each device mapping inside the folder. This can be useful to quickly set up multitimbral or multiple IO instruments.

See the [devices](#toc.devices) chapter for more information.

### <a name="toc.presetpanel"></a>5.5.6. [](#inspector.presetpanel)Preset Panel

![](images/inspector_panel_preset.png)

The **Preset** panel is accessible by key shortcut F4. The panel header displays the name of the preset assigned to the device on the focus track.

The panel contains the following buttons:

*   [](#inspector.presetmenu)**Preset Menu**: Opens the preset menu.
*   [](#inspector.presetload)**Load...**: Opens a file dialog where fxb or fxp files can be loaded into the plugin. This button is only shown if a plugin is loaded on the track.
*   [](#inspector.presetname)**Name...**: Opens the **Edit Program Name** dialog for editing the name of the current plugin program. This button is only shown if a plugin is loaded on the track.
*   [](#inspector.presetpin)**Auto-Assign Preset**: Enables automatic preset assignment when using cursor keys to navigate in the list or when clicking a preset in the list. This is useful when you want to quickly audition different presets in an instrument.

The preset list shows the available presets for the device on the focus track. You can assign a preset by double-clicking it in the list (single-clicking if **Auto-assign preset** is enabled), dragging a preset from the list to a track with a compatible device mapping, selecting **Assign to Track** from the list context menu, or pressing Return when the list has key focus. Note that some VST plugins use their own proprietary preset handling systems, and plugin presets thus may be unavailable in the **Preset** panel.

_Note:_ The **Preset** panel can only display actual preset names when the arrangement is powered on, and the plugin on the focus track has not been disabled.

See the [presets](#toc.presets) chapter for more information on presets.

### <a name="toc.parameterpanel"></a>5.5.7. [](#inspector.parampanel)Parameter Panel

![](images/inspector_panel_param.png)

The **Parameter** panel is accessible by key shortcut F5. The panel header displays the name of the parameter assigned to the focus track.

The panel contains the following buttons:

*   [](#inspector.parammenu)**Parameter Menu**: Opens the parameter menu with options for enabling MIDI and SysEx parameters.
*   [](#inspector.paramdevice)**Device**: Shows VST and MIDI parameters in the parameter list. The button is only visible if the assigned device has VST or MIDI parameters.
*   [](#inspector.parammixer)**Mixer**: Shows the **Level**, **Pan** and **Send** audio mixing parameters in the parameter list. Mixer parameter tracks controls the closest parent track that is audio enabled.
*   [](#inspector.parameditor)**Embedded Editor Parameters**: Shows two checkboxes next to each plugin parameter in the list. Use the checkboxes to select which parameters you want to show in the embedded plugin editors. The first checkbox is for the rack editors and the second checkbox for the mixer strip editors. See the [rack](#toc.rack) section and [mixing](#toc.mixing) chapter for more information. The button is only visible if the assigned device has VST or MIDI parameters.

You can set up parameter automation by double-clicking a parameter in the list, dragging a parameter from the list to a compatible track, selecting **Assign to Separate Track** from the context menu, or pressing Return when the list has key focus - this will create a new parameter track with the parameter assigned. To replace the parameter assigned to the focus track, either select **Assign To This Track** from the list context menu, or Shift+click the **Parameter** selector and choose a parameter. In addition to the pin icon shown next to the parameter that is assigned to the focus track, dimmed pin icons are shown next to all parameters that have been assigned to parameter tracks belonging to the focus track.

See the [parameter automation](#toc.parameterautomation) chapter for more information.

### <a name="toc.inputpanel"></a>5.5.8. [](#inspector.inputpanel)Input Panel

![](images/inspector_panel_input.png)

The **Input** panel is accessible by key shortcut F6. The panel header displays the name of the input mapping assigned to the focus track.

The panel contains the following buttons:

*   [](#inspector.inputmenu)**Input Menu**: Opens the input menu.
*   **Bypass**: Bypasses the input mapping. Also available by pressing X when the track has focus.

An input mapping can be assigned to a track by double-clicking it in the list, dragging a mapping from the list to a track, using the **Assign/Move to Track** command on the list context menu, or by pressing Return when the list has key focus. When you assign an input mapping in any of these ways, this will remove the mapping from all other tracks it is assigned to. You can assign the same input mapping to multiple tracks by selecting **Assign/Copy to Track** from the context menu, or dropping the mapping on a track while holding the Ctrl key.

An input can alternatively be automatically assigned to the focus track by selecting **Auto-Assign to Focus Track**. The input mapping will thereby be automatically moved to the currently selected track, unless the track already has an input mapping. The name of an auto-assigned input will be shown dimmed on the **Input** selector and on the panel header.

_Note:_ The first MIDI input device detected by Podium is, by default, configured to be auto-assigned in newly created projects.

_Tip:_ As with device mappings, you can drag a folder from the input list to an empty region of the track list to create a group track along with child tracks for each input mapping inside the folder.

_Tip:_ You can configure both an auto-assigned MIDI and audio input mapping at the same time. Depending on whether there is an instrument assigned to the focus track, the appropriate input will be used.

## <a name="toc.usingpresets"></a>5.6. Using Presets

Assigning a preset to a track will recall the preset on the device. The recall is only done if the track is unmuted and if monitoring is activated. If a program preset is assigned, the device will recall the preset from the specified program location in the internal preset bank of the device. If a library preset is assigned, the preset data will be transferred to the device. In the case of external devices this is done by sending MIDI SysEx messages. Note that some plugins handle preset recall as part of the audio processing. This can lead to a momentary CPU overload and audio drop-out.

To avoid conflicts between presets, only a single library preset is allowed on tracks with mappings for a global device instance. Plugin program presets are also only allowed on a single track for a plugin instance. Program presets using MIDI program changes can be assigned to tracks with individual MIDI channel mappings. Any invalid preset assignments will be indicated by a red message popup button in the track inspector and on the strips in the mixer.

A single program or library preset can be assigned to multiple tracks with different instances of a plugin or external device. Changes to the preset will then be applied to all device instances assigned with the preset.

### <a name="toc.creatingpluginpresets"></a>5.6.1. Creating Plugin Library Presets

Assigning program presets to a plugin track is an efficient way to recall predefined factory presets in the plugin without storing the preset data in your Podium project. Some plugins require large amounts of memory for preset data, so the memory saved with program presets can be substantial.

If you want to store a preset you have edited with the plugin editor, you need to use library presets. You can create library presets containing the data for only the current program or for the entire bank of presets. Some plugins may require the use of bank presets. This can be the case with multitimbral instruments that store additional information such as global settings and channel setups in bank presets.

Library presets are created with the **New Program Library Preset** and **New Bank Library Preset** commands found on the preset panel menu and track context menu. The **Create Library Presets For All Programs** command will create a series of library presets for all programs found in the plugin. Creating library presets with these commands will place the presets in a separate "Library" subfolder within the device definition folder of the plugin.

When a new bank has been loaded in the plugin, either by assigning a bank library preset to a track or by using file load commands in the plugin, the program names in the plugin will likely not match the names of the preset objects. Use the **Update Programs List** command to update the list with the new contents of the plugin preset bank.

Assigned library presets are synced with the plugin settings when saving projects and unloading plugins etc. Library presets can be manually synced using the **Store Current Settings To Library Preset** command.

### <a name="toc.creatingsysexpresets"></a>5.6.2. Creating SysEx Library Presets

MIDI SysEx messages are used when storing preset data for external devices. Podium does not know the preset format for your external device and so cannot automatically request presets from the device. You have to record SysEx preset dumps from the device and then create the library presets from the recorded SysEx events.

Set up an arrangement to record from the device. Start the recording and use the menu system on the device to initiate a SysEx dump of the current preset. It is important that it is the current preset and not bank presets you transfer. Otherwise when Podium transfers the preset back to the device it would overwrite the bank preset rather than the current preset. Recall another preset and repeat the SysEx dump for each preset you want to transfer. When done, stop the recording and check the recorded events. There should be a series of stream events for each preset you transferred.

If the device only transmits one SysEx message for each preset you can select all the stream events, right-click the selection and choose the **Create Library Presets For Each Stream Event** command. This should create a series of generically named presets in the track inspector preset list. You can now choose to rename the presets to what their name was on the external device.

If the device transmits several SysEx messages for each preset you select the group of stream events for one preset, right-click the selection and choose **Create Library Preset From Combined Stream Events** command. Repeat this for each group of stream events for all the presets you recorded. The **Preset Properties** dialog will be displayed to let you specify the correct name for the preset.

After this procedure the new presets are found in the "Library" folder under the device definition folder associated with your device. You can now delete the SysEx messages you recorded.

* * *

# <a name="toc.arranging"></a>6. Arranging

The Podium mixing engine uses the track tree of an arrangement to control the routing of MIDI and audio. A track can generate MIDI or audio either through live device mapping objects or through recorded material contained in sequences on the tracks. The output of the tracks will be streamed through each parent track in the tree until arriving at a track with a device mapping that can use the streamed data.

As an example let's say we have a group of tracks containing note sequences and curve sequences for parameter automation. The output of these tracks will stream upwards to a parent track that has a device mapping for an external synth or a plugin synth. This track will then generate the audio output of this device and stream the audio upwards in the tree possibly passing through tracks containing effects plugins and eventually arriving at the master output track.

Bouncing is a feature that is useful when your system resources are low. It involves recording the audio output for example of a plugin and thus freeing the resources required by the plugin. In Podium you can enable bouncing on any track that streams audio. This enables you to bounce a single plugin track, a group of plugins on a parent track or the master output at the topmost track. Once your bounce tracks have been recorded you can use the **B** bounce button on a track to switch between bypassing the bounced sound or bypassing the subtree that produced the bounced sound.

## <a name="toc.sequenceevents"></a>6.1. Sequence Events

A sequence event refers to a segment of a sequence object. When you move, resize, or split events, you modify the start and end position of the segment that the event links to - the sequence object itself is not affected. There are four types of events used in the arrangement editor: [sound events](#toc.soundeventproperties), [note sequences](#toc.notesequence), [curve sequences](#toc.curvesequence), and [parameter events](#toc.parametereventautomation). New events can be created by recording, importing audio or MIDI files, or by using the select or pencil tools. The type of sequence created thereby depends on the track configuration.

The name of a note or curve sequence can be changed in the [](#dialog.sequence)**Sequence Properties** dialog, accessible from the sequence event context menu, or by pressing Alt+Enter when a sequence is selected. To change the name of a sound event, use the **Sound Event Properties** dialog, see the [Sound Event Properties](#toc.soundeventproperties) section.

Click+drag a sequence event to move it on the timeline, as well as across tracks. Hold the Shift key to lock either the x or y position of events, depending on the drag direction. Press Ctrl+Left or Ctrl+Right to move selected events in steps of the editor quantize value.

Sequence events can be resized using the bottom-most handles that appear at the event start and end points when the select or pencil tool is placed on an event. You can alternatively resize an event when the resize handles are not in view, by Alt+clicking the event. Whether the start or end of the event is resized thereby depends on the clicked position.

You can have multiple sequence events referencing the same sequence object. These phantom sequence events are indicated by a plus symbol next to the sequence name. All changes made to the notes, curve points, or sound data referenced by a phantom sequence event will be reflected in all phantom copies of the event. Phantom copies can be created from selected events by holding the Ctrl key before or while moving events. Releasing and holding the Ctrl key again while holding the mouse button will toggle between creating phantom and unique copies. The mouse cursor indicates whether a phantom or unique copy will be created. A phantom sequence can be made into a unique copy using the **Convert to Unique Copy** or **Convert to Unique Cropped Copy** commands on the **[Edit](#toc.editoreditmenu)** menu and the sequence event context menu.

The Insert key can be used to create phantom copies of all selected events, whereby the duplicated events will align to the grid according to the editor snap value, provided that snap is enabled. Press Ctrl+Insert to snap the start of the duplicated events to the next bar. Press Shift+Insert to align the duplicated events exactly at the end of the selected events.

### <a name="toc.gainandfades"></a>6.1.1. Gain, Fade-In/Out and Crossfades

![](images/editor_sound_event_fade.png)

Sound events can have gain, fade-in, and fade-out settings, which are applied in real-time during playback. The waveform displayed on sound events is scaled according to the fade length.

Placing the select or pencil tool on sound events will display four handles, as well as a horizontal gain handle at the top of the event. When the mouse cursor is placed on one of the fade handles or the gain handle, the fade curve is highlighted and the fade-in/out time or event gain value is displayed at the bottom of the event. Drag the gain handle up or down to adjust the event gain in 0.1 dB steps. Drag the upper left handle to adjust the fade-in time, and the upper right handle to adjust the fade-out time. Right-click a fade handle, or inside the fade range to display a menu used for selecting the fade curve shape. Double-clicking either fade handle or the gain handle opens the **Sound Event Properties** dialog, with key focus set to the appropriate value input field. See the [Sound Event Properties](#toc.soundeventproperties) section.

Moving a sound event so that it overlaps with another sound event will automatically create a linear crossfade on the overlapping sections. The crossfade is logged as a separate action in the edit history. Clicking the undo button, or pressing Ctrl+Z once will undo the crossfade, and clicking the undo button again will undo the event move.

When right-clicking within the crossfade range, the selected curve shape will be applied to both the overlapping events. If you have resized two or more crossfaded events, or edited the crossfade times, you can use the **Crossfade** command to restore the original crossfade times of the overlapped sections. This command is available on the **Edit** menu and on the sound event context menu when two or more selected sound events overlap.

Fade curves on sound events in the arrangement editor are applied non-destructively. You can bounce tracks, or use the sound editor to apply fades destructively. See the [sound editor](#toc.soundeditor) chapter for more information.

_Note:_ Fade curves on sound events will, by default, be shown at all times. To only show fade curves when moving the mouse cursor on an event, disable the **Show sound event fade curves** option in the **Tracks Region Properties** dialog. See the [editor profiles](#toc.tracksregion) chapter for more information.

#### Fade Curve Menu

*   [](#cmd.fade.in1db)**-1 dB**: Sets the fade-in curve to -1 dB at the center.
*   [](#cmd.fade.in2db)**-2 dB**: Sets the fade-in curve to -2 dB at the center.
*   [](#cmd.fade.in3db)**-3 dB (Equal Power)**: Sets the fade-in curve to -3 dB at the center.
*   [](#cmd.fade.in4db)**-4 dB**: Sets the fade-in curve to -4 dB at the center.
*   [](#cmd.fade.in5db)**-5 dB**: Sets the fade-in curve to -5 dB at the center.
*   [](#cmd.fade.in6db)**-6 dB (Linear)**: Sets the fade-in curve to -6 dB at the center.
*   [](#cmd.fade.in9db)**-9 dB**: Sets the fade-in curve to -9 dB at the center.
*   [](#cmd.fade.in12db)**-12 dB**: Sets the fade-in curve to -12 dB at the center.
*   [](#cmd.fade.in20db)**-20 dB**: Sets the fade-in curve to -20 dB at the center.
*   [](#cmd.fade.insofts)**Soft S-Shape**: Sets the fade-in curve to a soft S-shape.
*   [](#cmd.fade.inhards)**Hard S-Shape**: Sets the fade-in curve to a hard S-shape.
*   [](#cmd.fade.out1db)**-1 dB**: Sets the fade-out curve to -1 dB at the center.
*   [](#cmd.fade.out2db)**-2 dB**: Sets the fade-out curve to -2 dB at the center.
*   [](#cmd.fade.out3db)**-3 dB (Equal Power)**: Sets the fade-out curve to -3 dB at the center.
*   [](#cmd.fade.out4db)**-4 dB**: Sets the fade-out curve to -4 dB at the center.
*   [](#cmd.fade.out5db)**-5 dB**: Sets the fade-out curve to -5 dB at the center.
*   [](#cmd.fade.out6db)**-6 dB (Linear)**: Sets the fade-out curve to -6 dB at the center.
*   [](#cmd.fade.out9db)**-9 dB**: Sets the fade-out curve to -9 dB at the center.
*   [](#cmd.fade.out12db)**-12 dB**: Sets the fade-out curve to -12 dB at the center.
*   [](#cmd.fade.out20db)**-20 dB**: Sets the fade-out curve to -20 dB at the center.
*   [](#cmd.fade.outsofts)**Soft S-Shape**: Sets the fade-out curve to a soft S-shape.
*   [](#cmd.fade.outhards)**Hard S-Shape**: Sets the fade-out curve to a hard S-shape.
*   [](#cmd.fade.cross1db)**-1 dB**: Sets the crossfade curves to -1 dB at the center.
*   [](#cmd.fade.cross2db)**-2 dB**: Sets the crossfade curves to -2 dB at the center.
*   [](#cmd.fade.cross3db)**-3 dB (Equal Power)**: Sets the crossfade curves to -3 dB at the center.
*   [](#cmd.fade.cross4db)**-4 dB**: Sets the crossfade curves to -4 dB at the center.
*   [](#cmd.fade.cross5db)**-5 dB**: Sets the crossfade curves to -5 dB at the center.
*   [](#cmd.fade.cross6db)**-6 dB (Linear)**: Sets the crossfade curves to -6 dB at the center.
*   [](#cmd.fade.cross9db)**-9 dB**: Sets the crossfade curves to -9 dB at the center.
*   [](#cmd.fade.cross12db)**-12 dB**: Sets the crossfade curves to -12 dB at the center.
*   [](#cmd.fade.cross20db)**-20 dB**: Sets the crossfade curves to -20 dB at the center.
*   [](#cmd.fade.crosssofts)**Soft S-Shape**: Sets the crossfade curves to a soft S-shape.
*   [](#cmd.fade.crosshards)**Hard S-Shape**: Sets the crossfade curves to a hard S-shape.

### <a name="toc.timestretching"></a>6.1.2. Time-Stretching

![](images/editor_event_stretch.png)

Time-stretching can be used on note and curve sequences in the arrangement editor.

Placing the select or pencil tool on sequence events will display four handles, of which the top handles at the start and end of a sequence are used to adjust time-stretching. When a sequence is time-stretched, its play rate will be written in parentheses next to the sequence name.

Time-stretching is performed non-destructively. Sequences can be returned to their original play rate by selecting **Reset Time-Stretch** from the sequence event context menu. Creating copies of a time-stretched sequence will also copy the play rate setting for the sequence.

### <a name="toc.soundeventproperties"></a>6.1.3. [](#dialog.soundevent)Sound Event Properties

![](images/dialog_sound_event.png)

The **Sound Event Properties** dialog can be opened by selecting **Sound Event Properties** from the sound event context menu, or by pressing Shift+Enter. It can also be opened by double-clicking either of the fade handles or the gain handle on a sound event, in which case key focus will be set to the appropriate value field in the dialog.

In this dialog, you can enter a **Sound event name** to use in place of the sound file name, as well as adjust **Gain offset**, **Panning**, **Fade-in**, and **Fade-out** settings, which will be applied to the sound event in real-time during playback.

The fade curve displays can be used to precisely set the fade time and curve shape. To adjust the curve shape, click+drag horizontally inside the upper and lower halves of the curve display, or use the value input fields below the display. The segment of the waveform that is inside the fade range is shown underneath the curve.

## <a name="toc.parameterautomation"></a>6.2. Parameter Automation

![](images/editor_automation.png)

Automation in Podium is track based, with automation points enclosed in curve sequences, which are presented the same way as note sequences and sound events in the arrangement editor. Curve sequences can thus be moved, resized, split, and time-stretched, among other editing actions. It is also possible to create phantom copies of curve sequences.

Automatable parameters include MIDI parameters (for example, Control Change, Program Change, or SysEx), VST plugin parameters, and Podium mixer parameters (level, pan, send). Mixer parameter automation is applied as a relative offset to the track gain, pan and send settings. For example, you can adjust the track gain value to fit it into the mix, and any existing level automation on the track will automatically be offset to the new overall gain value. Level and send parameters range from minus infinity (off) to zero dB. Thus you need to set the gain and send track settings to the maximum peak value that you require, which then can be reached with the maximum 0 dB automation value.

Parameter tracks can be created manually by selecting parameters from a menu, or they can be created automatically by recording parameter changes made with the mouse in plugin editors or with connected MIDI controllers. See the [recording automation](#toc.recordingautomation) section for more information.

To manually create a parameter track, select a parameter from the **Parameter** submenu of the track context menu, or from the **Parameter** panel in the inspector. See the [track inspector](#toc.trackinspector) chapter for more information. This will create a parameter track, which appears as a child track of the track to which the automated device is assigned. To change the parameter object assigned to a parameter track, Shift+click the parameter selector. See the [track controls](#toc.trackcontrols) section in the tracks chapter for more information. When you create a new parameter track, a curve sequence spanning the length of the arrangement is automatically created on the parameter track.

_Note:_ To be able to record or edit MIDI parameters in a plugin or hardware device, it is required that the device definition contains parameter objects that define the MIDI messages. Not all MIDI messages are created by default when you for example import a plugin. Use the **Parameter** panel in the inspector to create and edit MIDI parameter objects. See the [parameters](#toc.parameters) and [track inspector](#toc.parameterpanel) chapters for more information.

### <a name="toc.mixerfaders"></a>6.2.1. Mixer Faders

Parameter tracks in the mixer appear with a fader representing the value of the curve sequence at the play/edit cursor position. If there is no curve sequence at the play cursor position, the fader knob is drawn dimmed.

The parameter selector shown in the mixer strip header will be vertically aligned to the source/effect selector that it belongs to, provided that the **Show Effect chains** mixer option is enabled. This provides a helpful visual clue, when you for example have automated the same parameter on two different effect tracks. This could be the send parameter automated for both "Send 1" and "Send 2", which will show up as "Send" in the mixer strip title for both parameter tracks. The track lane header does not have the same visual clue tying a parameter track to an effect, so it includes the controlled effect name in parentheses in the header title, such as "Send (Send 1)".

If you have created parameter tracks for multiple effects on a single track, the parameter tracks are sorted with the topmost effects appearing first. This top to bottom order cannot be changed, but you can rearrange parameter tracks that belong to the same source/effect selector. Use the parameter track **Move** submenu, or drag the parameter track lane header up/down in the track list.

The fader on a parameter mixer strip will use the full available height of the strip, with the exception of the level and send parameters. These parameters are automating dB gain values in the Podium mixer, and so the faders are aligned vertically to match the level markings of gain faders and meters on audio tracks.

### <a name="toc.recordingautomation"></a>6.2.2. Recording Automation

Parameter changes can be recorded with hardware MIDI controllers, by adjusting controls in VST plugin editor windows, or using the controls in embedded plugin editors in the rack or mixer. See the [mixing](#toc.embeddedplugineditors) and [track inspector](#toc.rack) chapters for more information on embedded plugin editors.

To record automation using a MIDI controller, the controls on VST plugin editors, or embedded editors, the respective track must be record armed, and recording mode enabled on the transport toolbar. When recording parameter changes to a device assigned to an effect track with a MIDI controller, the appropriate MIDI input must be assigned to the effect track by selecting the track in the [rack](#toc.rack), and assigning the input device from the **[Input](#toc.inputpanel)** panel in the inspector.

_Note:_ It is not required to enable recording mode or record arm a track when using parameter value faders on parameter tracks in the mixer to record automation.

When you record using the mouse on controls in VST plugin editor windows, embedded editors, or parameter faders in the mixer, automation will be recorded for as long as you keep a control active by holding the left mouse button.

Recording automation with MIDI controllers, VST plugin editors, or embedded editors will create a series of bar point events, to ensure that playback will reproduce the exact same series of parameter changes. Dragging the faders on parameter tracks in the mixer during playback will create a series of line point events, resulting in gradual value changes.

_Note:_ Changes to mixer parameters (level, pan, send level) can only be recorded using the faders on parameter tracks in the mixer.

_Tip:_ Changes made to a curve sequence by dragging a parameter fader in the mixer can be cancelled by right-clicking while dragging the fader.

To record only changes to specific parameters, you can record arm individual parameter tracks. Use punch mode to record only within a certain timeline range. See the [recording](#toc.punchmode) chapter for more information. Note that punch mode does not affect automation recording when using the faders on parameter tracks in the mixer.

### <a name="toc.editingautomation"></a>6.2.3. Editing Automation

Curve sequences are primarily edited with the curve editor, see the [curve sequence](#toc.curvesequence) chapter for more information.

Alternatively, the parameter value faders on parameter tracks in the mixer can be used to input parameter changes even when playback is stopped. Dragging a fader will edit the curve sequence at the edit cursor position - if the edit cursor is positioned at a point on an existing curve that uses line or spline points, a line point will be created. Otherwise a bar point will be created, resulting in an abrupt parameter value change. If there is no curve sequence at the edit cursor position, the previous sequence will be extended or a new one will be created automatically at the start of the drag action.

_Note:_ Adjustments made to parameter value faders are logged in the arrangement undo history.

### <a name="toc.parametereventautomation"></a>6.2.4. Parameter Event Automation

![](images/editor_parameter_event.png)

For MIDI parameters that only need to be set to a fixed value at a certain point on the timeline, you can insert parameter events directly on the timeline, as an alternative to curve sequences.

Parameter events can be created for MIDI parameters by dragging parameter objects from the **[Parameter](#toc.parameterpanel)** panel in the track inspector onto the timeline area of a track. The events are drawn as squares with a header showing the parameter name. The left edge of the square is aligned at the event time position. If the parameter object has a value range, as defined in the **Parameter Properties** dialog, the parameter event will show a value along with a dial you can use to change the value. See the [parameter properties](#toc.parameterproperties) section for more information. The dial is sized according to track height.

The **Parameter Properties** dialog for a parameter object contains a **Record as curve sequence on separate track** check box. This setting determines if recording parameter changes should generate curve sequences or parameter events.

![](images/dialog_parameter_event.png)

If there are several parameter events stacked on top of each other, it can be difficult to select an individual event with the mouse. If you select one of the events, you can use the left/right arrow keys to step between the events. The selected event will always be drawn on top of unselected events. Alternatively, you can use the event list on the **[Track](#toc.trackpanel)** panel in the inspector, where you can view all parameter events on the track, and edit their values with the dials in the list. If you want to enter a precise value, open the [](#dialog.paramevent)**Parameter Event Properties** dialog by double-clicking the event or pressing the Enter key when the event has key focus.

When you edit the parameter event value, it is applied to the parameter in real time so you can audition the effect of the value change.

## <a name="toc.mixing"></a>6.3. Mixing

![](images/editor_mixer.png)

The mixer can be used to to get an overview of, and precisely control track settings, levels, and effect chains. By default, the mixer is accessible by clicking the **Mixer** button on the [editor profile toolbar](#toc.editorprofiletoolbar), located above the transport bar.

#### [](#mixer.region)Mixer Region

*   Click+drag the title bar to adjust the height.
*   Double-click the title bar or press F8 to restore/minimize.

The layout of the mixer strips mirrors the tracks region, with the tracks arranged as columns rather than rows. Collapsed group tracks will be shown collapsed in both the mixer and arrangement editor. Selecting a track in the arrangement editor will scroll the mixer if the track is off-screen.

_Tip:_ Track tag selections apply to both the arrangement editor and mixer. See the [track tags](#toc.tracktags) section in the arrangement chapter for more information.

You can set the height of the mixer region by dragging its title bar vertically, or using the **Minimum region height** and **Maximum region height** settings in the **[Mixer Region Properties](#toc.mixerregion)** dialog. Double-click the title bar or press F8 to minimize/restore the mixer region.

The column to the left side of the mixer contains a button to open the mixer options menu, as well as shortcut buttons to show/hide embedded plugin editors, effect chains, **+** new effect buttons, **Source** selectors, and **Input** selectors. The options to show or hide these and other mixer elements are also available in the mixer options menu. Below these buttons is the **Zoom strip widths** slider, used to horizontally zoom mixer strips from 20% to 300% original size. Double-clicking or Ctrl+clicking the slider will set zoom to the default 100%. Double-clicking again will restore the previous zoom setting. When you adjust the zoom by dragging the slider, the zoom will lock onto the focus track.

When zooming the mixer strip widths below 100%, the embedded plugin editors and various mixer controls will change position and size to accomodate for the narrow mixer strips. The BSMR buttons will be moved above the meters, the translucent faders will gradually overlap the meters, values will be shown with fewer decimals, various texts will be shortened or removed, in order to present a clean view of the mixer strips even at 20% zoom.

The arrangement editor slide and zoom tools can also be used to navigate the mixer strips. Selecting the Slide tool (hold Shift+Alt) will show the hand mouse cursor, allowing you to click anywhere on the mixer strips and drag to slide the view. Selecting either the Zoom X or Zoom XY tool (hold Ctrl+Alt) allows you to click on a mixer strip and drag sideways to zoom in/out on the mixer strip. Instead of click+drag you can also use the the mouse wheel to zoom in/out.

Mixer strips use the same track controls and selector buttons also used on track headers and in the rack. See the [track controls](#toc.trackcontrols) section in the tracks chapter for more information.

_Note:_ The control type used for gain/pan/send controls can be changed in the **Mixer Region Properties** dialog.

Each track configured for audio processing presents a large fader and peak meter. The number of meters displayed on a track depends on the speaker configuration (mono, stereo, or surround setups) of devices in the track effect chain. Clicking a meter toggles RMS metering on/off on the track. You can select to use a different RMS meter scale, such as the K-System, in the **Arrangement Properties** dialog.

Parameter tracks show a fader indicating the parameter value at the edit/play cursor position. This fader can also be used to record parameter automation. See the [parameter automation](#toc.parameterautomation) chapter for more information.

Additionally, the following controls and elements are available on mixer strips:

*   **Fader & Meter Grid**: See the [fader and meter grid](#toc.faderandmetergrid) section.
*   **Peak hold indicators**: Display the peak dB values measured on tracks during playback. Clicking a peak hold indicator will reset its value, and double-clicking any peak indicator will reset the value on all mixer strips.
*   **Latency information**: Shows the time that the signal on the track is delayed before it arrives at connected monitoring equipment, presented as miliseconds, with the number of samples in paranthesis. This is caused by latency added by plugins and the audio interface. The delay will be present during live monitoring, but is automatically compensated for during playback and recording.

Double-clicking an empty region of a mixer strip opens the **[Track Properties](#toc.trackproperties)** dialog for the track. Clicking the gain or pan value display opens the **Track Properties** dialog with key focus set to the matching value field. These value displays may not be available, depending on the **Gain/pan fader** setting in the **Mixer Region Properties**.

The master track, as well as bus tracks can be configured to be docked to the left or right side of the mixer in the **Mixer Region Properties** dialog. By default, the master track is docked to the left side of the mixer. Docked tracks will always be shown, even when they would otherwise be hidden by [track tag](#toc.tracktags) selections.

#### [](#mixer.menu)Mixer Options Menu

Besides options to show or hide various mixer elements, the mixer options menu contains the following settings:

*   [](#cmd.mixer.showeditor)**Show Embedded Plugin Editors**: Shows embedded plugin editors in the mixer.
*   [](#cmd.mixer.showchain)**Show Effect Chains**: Shows effect chain panels.
*   [](#cmd.mixer.showneweffect)**Show New Effect Buttons**: Shows buttons for inserting effects.
*   [](#cmd.mixer.showbypass)**Show Bypass Buttons**: Shows bypass buttons.
*   [](#cmd.mixer.showsource)**Show Source Selectors**: Shows source selectors.
*   [](#cmd.mixer.showinput)**Show Input Selectors**: Shows input selectors.
*   [](#cmd.mixer.showgain)**Show Gain Controls**: Shows gain controls.
*   [](#cmd.mixer.showpan)**Show Pan Controls**: Shows pan controls.
*   [](#cmd.mixer.showsend)**Show Send Controls**: Shows send controls.
*   [](#cmd.mixer.showgrid)**Show Fader and Meter Grids**: Shows fader and meter grids.
*   [](#cmd.mixer.showpeak)**Show Peak Hold Indicators**: Shows peak hold indicators.
*   [](#cmd.mixer.showlatency)**Show Latency Information**: Shows latency information.
*   [](#cmd.mixer.minimizeaudio)**Minimize Audio Tracks**: Minimizes all audio tracks.
*   [](#cmd.mixer.minimizemidi)**Minimize MIDI Tracks**: Minimizes all MIDI device mapping tracks.
*   [](#cmd.mixer.minimizeparam)**Minimize Parameter Tracks**: Minimizes all parameter tracks. Disabling this option restores parameter tracks to their previous state.
*   [](#cmd.mixer.expandall)**Expand All Groups**: Shows all tracks including collapsed and hidden groups. Disabling this option restores group tracks to their previous collapsed/expanded state.

#### [](#mixer.editor)Embedded Plugin Editors

Shortcut to the **Show Embedded Plugin Editors** menu option.

Some Zynewave plugins will show a graphical editor. Other plugins will show a generic editor where you can select which parameters to display.

To select the parameters, either use the inspector parameter panel or right-click a plugin selector and use the **Mixer Editor Parameter** submenu.

#### [](#mixer.chain)Effect Chains

Shortcut to the **Show Effect Chains** menu option.

#### [](#mixer.neweffect)New Effect Buttons

Shortcut to the **Show New Effect Buttons** menu option.

#### [](#mixer.source)Source Selectors

Shortcut to the **Show Source Selectors** menu option.

#### [](#mixer.input)Input Selectors

Shortcut to the **Show Input Selectors** menu option.

#### [](#mixer.zoom)Zoom Strip Widths

Double-click or Ctrl+Click to set zoom to default. Double-click again to restore previous zoom setting.

Dragging the slider will lock zoom on the focus track. To lock zoom on a specific track, hold Ctrl+Alt and use click+drag or the mouse wheel over the strips.

To slide the strips, hold Shift+Alt and use click+drag, or hold Alt and use the mouse wheel.

### <a name="toc.faderandmetergrid"></a>6.3.2. Fader and Meter Grid

![](images/editor_mixer_fader_meter_grid.png)

When enabled in the mixer options menu, the Fader and Meter Grid is displayed at the bottom right side of every mixer strip. Each row of blocks in the grid represents an effect in the track effect chain. The left column of blocks represents the fader position, and the right column represents the meter position. A highlighted block indicates the position at which the fader or meter is currently set. Bus sends are drawn as framed blocks instead of filled blocks.

Clicking the grid will toggle the meter between pre- and post-effect metering. Shift+clicking a block in the grid will set the fader or meter to the corresponding effect track. Move the mouse cursor over the grid to show a popup with detailed information.

### <a name="toc.embeddedplugineditors"></a>6.3.3. Embedded Plugin Editors

Embedded plugin editors can be shown/hidden using the **Embedded plugin editor** button on the options column at the left side of the mixer region, or with the **Show Embedded Plugin Editors** option on the mixer options menu.

To add or remove parameters from an embedded plugin editor, enable or disable parameters from the **Add/Remove Mixer Editor Parameter** submenu of the selector button context menu, or select **Remove All Mixer Editor Parameters** from the menu to remove all parameters.

Alternatively, you can use the parameter list in the track inspector **[Parameter](#toc.parameterpanel)** panel. Click the **Embedded editor parameters** button in the **Parameter** panel to show checkboxes next to each parameter in the list. The second checkbox for each parameter is used to show/hide the parameter in embedded plugin editors in the mixer.

Parameters inside embedded plugin editors are displayed with a value readout and a dial. Click+drag anywhere inside the editor to adjust the value of a parameter. Changes made to parameters can be recorded in the same way as recording adjustments made to controls inside plugin editor windows. See the [parameter automation](#toc.parameterautomation) chapter for more information.

The Zynewave parametric equalizer plugin - [zPEQ](#toc.zpeq) - is presented using its familiar UI, integrated in the mixer. See the [zPlugins](#toc.zplugins) chapter for more information on how to use the zPEQ editor miniature. The embedded editor is automatically resized when using the mixer strip zoom function.

_Note:_ Embedded plugin editor configurations are stored in the project file, and apply to all arrangements in the project.

### <a name="toc.busses"></a>6.3.4. Busses

Busses are generally used to create a branch off the [track hierarchy](#toc.trackhierarchy), with the result that the signal not only flows upwards in its own track chain, but is also routed to another track chain starting on the bus track. This can be used to the advantage of routing multiple tracks to the same effect chain, or to create submixes that may otherwise be difficult to set up within the track hierarchy.

Podium supports a total of 100 bus instances, and each bus supports up to 32 audio channels. Bus sends are not fixed at pre- or post-effect positions, but can instead be moved to any point in the effect chain in the same way as effect mappings. Busses are handled like other device objects, such as VST effect plugins - to route a track to a bus, assign a send mapping to the track by either selecting the mapping from the menu on the **+** new effect button, or by dragging a mapping from the **[Device](#toc.devicepanel)** panel in the [track inspector](#toc.trackinspector). Unless there is already a track holding the matching return mapping, a dialog will appear, asking whether to create one. Bus return tracks created in this way are, by default, set to automatic solo mode.

By default, bus mappings are located in the **Busses** folder, accessible from the [device panel](#toc.devicepanel) on the project page. The default mappings are named 'Send n' and 'Return n' - these names can be changed in the same way as those of other device mappings. See the [devices](#toc.devices) chapter for more information.

_Tip:_ You can use [track templates](#toc.tracktemplates) to set up new tracks with a number of send mappings assigned.

In a newly created project, you will have four busses available. Additional bus mappings can be created using the **Device** panel on the project page. Choose **New Bus Instance** from the **Device** menu to create a new bus instance using the default bus naming scheme. Alternatively, you can right-click an existing bus mapping, and choose **New Instance** to create a new bus mapping with its name based on the name of the selected instance. This option is also available on context menu in the **Device** panel in the track inspector.

_Tip:_ If you prefer to start a new arrangement with a more traditional mixer layout, for example, 16 tracks and 4 busses, you can specify the number of tracks and busses in the **New Arrangement Properties** dialog.

Mixer strips for bus return tracks can be configured to be docked to the left or right side of the mixer, using the **Mixer Region Properties** dialog. Docked bus tracks will always be shown, even when they would otherwise be hidden by [track tag](#toc.tracktags) selections.

### <a name="toc.levels"></a>6.3.5. Levels

On all tracks that are configured to stream audio there is a gain control that offsets the level of any audio passing through the track. This gain control is meant for setting the overall balance of the tracks.

When you wish to automate level fades you create parameter tracks and record the level fades into curve sequences.

The Podium mixer engine operates in 32-bit or 64-bit floating point. One advantage of using floating point is that clipping of overloaded audio does not occur until the audio is streamed to audio devices or rendered to a fixed point wave file. If audio overloads in the course of streaming and summing through the track tree you can reduce the level higher in the tree without losing quality.

Each track can be configured for use as an audio mixing junction. If audio is enabled then an audio level meter will be displayed in the track header and the the mixer track strips. The track will also include a gain adjustment. The purpose of the gain controls are to create an overall balance of your tracks and, for example, to boost weak audio inputs or reduce the gain of a track summing the output of multiple child tracks to avoid that it will overload plugins higher in the track tree.

If you want to automate levels you should assign the audio level parameter to a track and record curve sequences. The audio level parameter works as an offset to the current track gain setting. It functions as a damper of the track gain setting, so if you want to be able to automate a boost in the track level you should set the gain to the max desired. Since any automated level curves act as an offset to the track gain setting, you can at a later point readjust the balance of your track gains without having to redo the level automations. The automated level curves follow your track gain adjustments. Imagine you have an automated level curve fading from full scale to -6 dB below full scale. If your track gain is set to +6 dB the automated level curve will create a fade from +6 to 0 dB. If you adjust the track gain to -12 dB the level curve will create a fade from -12 to -18 dB.

Meters in the mixer region measure from -infinite to +6 dB. If the level on a track exceeds 0 dB the meter coloring will turn red and slowly fade back to green when level falls below 0 dB again. In general you should always try to make your audio tracks use the full range of the meter but always avoid any meter overloads. Preferably you should adjust the output level on the devices supplying the audio.

Both external devices and plugins often have a dedicated master volume. Once you have optimized the device output levels you can use the track gains to balance your mix. Even if you have a track that is supposed to be very quiet in the final mix you should always capture the source audio in full scale for optimum quality and only reduce the level as late as possible in the track tree mixing.

## <a name="toc.recording"></a>6.4. Recording

![](images/editor_recording.png)

This chapter describes how to record audio, MIDI, and plugin parameter automation. See the [parameter automation](#toc.parameterautomation) chapter for information on mixer parameter recording.

Before being able to start recording, you must assign the appropriate input device mapping(s) to one or multiple tracks. Click the **Input** selector on the track header and select an input from the menu. Alternatively, you can open the **[Input](#toc.inputpanel)** panel in the track inspector, or press F6, select an input, and either double-click it to assign it to the focus track, or drag it onto the track list to create a track with the mapping assigned. See the [devices](#toc.devices) chapter for more information on using device mappings.

_Tip:_ You can drag a folder containing multiple device mappings from the **[Input](#toc.inputpanel)** panel in the inspector to the track list to create a new track for each device mapping inside the folder.

For recording audio, you must assign an audio input mapping to a track you wish to record on. To record note events via MIDI, or plugin parameter automation using a MIDI controller, you must assign the desired MIDI input device mapping to a track, and also assign an instrument plugin or hardware device definition, using the **Source** selector on the track header.

You do not need to assign an input if you plan on recording plugin parameter automation by moving the plugin UI controls with the mouse.

_Tip:_ The first MIDI input device configured in Podium will be automatically assigned to the focus track in a newly created project. The name of an auto-assigned input is displayed dimmed on the **Input** selector.

After you have assigned an input to a track, click the **R** record arm button on the track header, or press R to arm the focus track for recording.

Activate recording mode by clicking the **record** button on the transport bar, by pressing K, or Decimal on the numeric keypad. When recording mode is activated, all **R** buttons on record enabled tracks, track lane backgrounds, as well as any sequence events on record enabled tracks are colored with the record color defined in the **Colors** dialog. If punch recording is activated, only those parts of tracks and sequences that fall inside the punch range will be colored. Furthermore, the play cursor will be colored with the record color once it enters the recording range.

Recording will commence on all record enabled tracks whenever playback is started with recording mode activated, or when recording mode is activated during playback, beginning at the play cursor position. Any recorded sound, note, and curve sequences will be displayed and updated in realtime during recording. It is possible to edit already recorded sequences, even during recording, without interrupting recording or playback. To stop recording, deactivate recording mode or stop playback. Recording mode will be deactivated automatically when playback is stopped. This can be configured using the context menu on the **record** button, or on the **[Play/Record](#toc.preferences.playrecord)** preferences tab.

You can activate metronome mode by clicking the **metronome** button on the transport bar, or by pressing U. The metronome will generate a clicking sound on each bar and beat during playback to aid you in keeping the desired tempo. Open the **[Metronome](#toc.preferences.metronome)** preferences tab, or choose **Metronome Preferences** from the **Metronome** button context menu to configure the metronome.

Loop mode can be activated by clicking the **loop** button on the transport bar, or by pressing L. Set the loop range by moving the loop locators, or using the options on the loop region context menu. When recording with loop loop mode activated, [multi-take recording](#toc.multitakerecording) will be used automatically on tracks with audio inputs assigned. This behavior can be configured on the **[Play/Record](#toc.preferences.playrecord)** preferences tab. When recording in loop mode with multi-take recording disabled, sound events will be overwritten on each subsequent pass through the loop range. Conversely, any new MIDI data recorded will be added to the existing note sequence when recording in loop mode, enabling you, for example, to layer drum notes during each pass.

_Tip:_ You can quickly set the loop range around the current selection by pressing Alt+L.

In summary, the following steps need to be taken to set up recording:

*   Assign an audio or MIDI input device mapping to a track. See the [devices](#toc.devices) chapter for more information.
*   Arm the track for recording by clicking the **R** button on the track header, or pressing R when the track has focus.
*   Activate recording mode by clicking the **record** button on the transport bar, by pressing K, or Decimal on the numeric keypad.
*   Optionally, activate metronome mode and loop mode by clicking the **metronome** and **loop** buttons on the transport bar, or by pressing U and L, respectively. Note that recording audio with loop mode activated will, by default, enable [multi-take recording](#toc.multitakerecording).
*   Start playback by clicking the **play** button on the transport bar, by pressing Space, or Enter on the numeric keypad.

### <a name="toc.punchmode"></a>6.4.1. Punch Mode

![](images/editor_punch_range.png)

Punch mode is used in combination with recording mode to limit the time range recording should be activated in.

Click the **punch in** and **punch out** buttons on the transport bar, or press I and O, respectively, to toggle punch in/out mode. Set the punch range by moving the punch locators, using the options on the punch region context menu, or the options on the **punch in/out** buttons context menu.

_Tip:_ You can quickly set the punch range around the current selection by pressing Alt+K.

When punch mode is activated, recording will only be activated once the play cursor enters the punch range, and deactivated again once the play cursor leaves the range. Activate only **punch in** to start recording from the punch in position, and keep recording until the end of the arrangement. Likewise, activate only **punch out** to start recording at the beginning of the arrangement, and stop recording at the punch out position.

### <a name="toc.multitakerecording"></a>6.4.2. Multi-Take Recording and Compositing

Multi-take recording can be useful in many situations, whether you are recording a performance or trying out different variations of a musical phrase, without having to worry about manual track management or recording over existing material.

_Note:_ Currently, multi-take recording is only available for audio recording.

Depending on the **Convert record enabled tracks to composite multi-take groups** setting on the **[Play/Record](#toc.preferences.playrecord)** preferences tab, multi-take recording will be used automatically upon starting recording, or only when loop mode is activated. To disable multi-take recording, set this option to **Never**. You can manually configure a track for multi-take recording by enabling **Use as composite track** in the **Track Properties** panel, or choosing **Composite Track** from the **Options** submenu of the track context menu.

![](images/editor_composite_track.png)

A composite multi-take group consists of a **composite** track and a number of **take** tracks. When using multi-take recording, contrary to loop recording, each new recording will not overwrite the previous one. Instead, a new take track will be created for each subsequent recording. The maximum number of take tracks to use in each multi-take group can be set on the **[Play/Record](#toc.preferences.playrecord)** preferences tab. Note that only sound events on the composite track will actually be played back. Sound events on take tracks are drawn dimmed to emphasize this.

Events created on take tracks will, by default, be named after the time recording was started at (in the format of hours:minutes:seconds).

The following steps need to be taken in order to set up multi-take recording:

*   Assign an audio input device mapping to a track.
*   Arm the track for recording.
*   Activate recording mode on the transport bar.
*   Activate loop mode and set a loop range. See the [play/record](#toc.preferences.playrecord) section for multi-take recording options.
*   Start playback.

Once you have recorded enough takes, you can start to combine the best parts of each take to assemble a satisfying performance - a process widely referred to as compositing, or 'comping'.

For this purpose, you can toggle solo mode on take tracks by Shift+clicking the **solo** button, or pressing Shift+S to toggle solo mode on the focus track to listen to each take separately and decide which sections to use.

_Tip:_ Take tracks can be renamed, rearranged, and deleted like any other tracks.

![](images/editor_composite_track_selection.png)

To create a comp from your recorded takes, split the composite event on the composite track, using the scalpel tool at every position you want to switch to another take.

Each split segment on the composite track has an additional control element not present on other types of sequence events - the **take selection bar**. Click this bar to cycle through all available takes, or right-click the bar to open a context menu, which allows you to directly select a take to use for the segment. To create smooth transitions, it is recommended to resize the composite events to slightly overlap each other, select all events on the composite track, and choose **Crossfade** from the sequence event context menu.

If you have selected multiple composite events, and select a take on one of the selected composite events, any similar named takes in the other selected composite events will also be selected. If the **Use timestamp as name for new take events** option on the **[Play/Record](#toc.preferences.playrecord)** preferences tab is enabled, it is easy to simultaneously change takes on multiple composite tracks. If you for example have recorded multiple takes of a band rehearsal using multiple audio inputs, you can select all the composite events, and switch the takes for all tracks simultaneously. Since the takes are named with a timestamp of the recording start, the selected takes will always be from the same recording, even if you reorganize the take tracks.

_Note:_ Only those takes that start before or at the same position as a composite event can be selected as active take for the composite event.

_Note:_ When composite events are moved on the timeline, this will offset the recorded material inside the composite event in time, compared to the original take - this can be used to a desired effect. Switching the active take used for the composite event hereafter will, however, revert to the original position of the take.

Like with normal group and child tracks, take tracks can be hidden to show only the composite track by Ctrl+clicking the **Collapse** button on the composite track header, or with key shortcut Ctrl+G, to conserve screen space.

Should you need to convert the comp into a single sound event ready for export or reuse on another track, select all composite events, and choose **Merge** from the sequence event context menu. Alternatively, you can bounce render the composite track.

### <a name="toc.recordingmidiparameters"></a>6.4.3. Recording MIDI Parameters

When receiving any MIDI messages such as control change, NRPN and SysEx messages, Podium will try to match them with any of the parameter objects belonging to the device mapping assigned to the recording track. If a match is found and the **Record as curve sequence on separate track** option in the **Parameter Properties** dialog of the parameter is selected, then that parameter will be assigned to a new parameter track (if not already assigned to a track), and the value of the parameter will be recorded to a curve sequence. If the matched parameter is not configured for curve recording, then a static parameter event will be placed on a dedicated child track. If the received message is not matched to any parameter objects, and the message is not a SysEx message, then the message is considered unusable for this particular device and is discarded. SysEx messages will be stored in stream events on a dedicated child track. By using this form of parsed recording of MIDI messages Podium makes your recorded material more understandable by presenting it with parameters named according to their purpose rather than MIDI message format.

* * *

# <a name="toc.setup"></a>7. Setup

The setup options can be reached through the **Setup** menu.

Apart from the data that is stored in project files and any associated wave files, all persistent configurations made in Podium are stored in a single plain text setup file. Podium does not store any information in the Windows registry. Of the information stored in the setup file it is only the settings for the Audio/MIDI interfaces, the mixer engine resolution and the root VST plugin folder that may influence how project files are loaded and played back. This makes it a simple task to copy your project folders to backup media and to port your projects to Podium installations on other PC systems.

The **Setup** menu contains five configuration dialogs, covering everything from interface selection to customizing the appearance and behavior of Podium:

*   **[Interfaces](#toc.interfaces)**
*   **[Preferences](#toc.preferences)**
*   **[Colors](#toc.colors)**
*   **[Editor Profiles](#toc.editorprofiles)**
*   **[Windows](#toc.windows)**

## <a name="toc.setupfiles"></a>7.1. Setup Files

When Podium is starting up it will try to load a setup file named "Podium.ini". If the file is not found, Podium creates the file with the default setup. When Podium is exiting it will write the current settings back to "Podium.ini".

If Podium is not exited properly, "Podium.ini" may become corrupted. This can happen if the computer is powered off while the setup file is being written. The next time Podium is started a corrupt setup file will typically cause the editor windows to be blank because the profiles are missing. If this happens, either use **Load Default Setup** on the **Setup** menu to overwrite "Podium.ini" with the default setup, or use **Load Setup...** if you have saved a backup of your setup file.

If you have put a lot of work into customizing the setup, you should save it to a backup setup file. Use the **Save Complete Setup...** command for this purpose. The **Save Color Setup...** command is used for saving color schemes, which consist only of the settings from the **Colors** dialog.

The load and save commands on the **Setup** menu can also be used to store setups for different occasions. There may be situations where you want to use different configurations of your MIDI and audio interfaces, or you could have setup files for different types of projects and work styles.

The Podium setup files are stored under the Windows managed application data folder. If you have a multi-user Windows installation, each user will have their own personal application data folder. For newer Windows versions using English, the setup folder is in the following location (substitute [user] with your user name):

"C:\Documents and Settings\[user]\Application Data\Zynewave\Podium"

If you use a Windows file explorer to locate this folder you may not be able to see the application data folder in the file list if you have the **Do not show hidden files and folders** option selected in the Explorer **Folder Options** dialog. You can still access the folder by entering the folder name directly in the Address bar.

Any setup files you save to the application data folder, including "Podium.ini", will remain if you uninstall Podium. You do not lose your setup if you uninstall or install a newer version of Podium.

## <a name="toc.interfaces"></a>7.2. [](#dialog.interfaces)Interfaces

### <a name="toc.interfaces.audio"></a>7.2.1. [](#dialog.interfaces.audio)Audio I/O

![](images/dialog_interfaces_audio.png)

For audio interfaces you can select to use either ASIO or Windows Wave/MME driver types. The best performance is obtained by using ASIO drivers. The support for Wave drivers is there primarily to allow Podium to run on a PC system that does not have any ASIO drivers installed. The panel below the driver type setting will contain options specific to the selected driver type.

When using the ASIO driver type, you can select one of the available ASIO drivers that are installed on your PC system. After selecting a new ASIO driver, you need to load the driver by clicking the **Apply** button in order to update the other setup options with information derived from the driver. At the bottom of the panel is a **Driver Setup...** button that will open the control panel of the currently active ASIO driver.

The choices available for the **Clock Source** setting will depend on the ASIO driver. The clock source will control the sample rate synchronization. If the audio interface has digital inputs then it usually is possible to use these inputs as clock source. Some interfaces do not support selecting the clock source through the ASIO driver, but instead allows the user to select it in the ASIO control panel.

When using the Wave/MME driver type, the interface is divided into separate input and output devices, similar to MIDI interface drivers. You can select one input device and one output device. Note that if you select input and output devices for two different hardware interfaces, the two devices may not be sample synchronized, which can lead to timing errors as the sample clock of the two interfaces may slowly drift apart.

The **Default sample rate** setting will show all the supported sample rates for the selected audio interface. Podium can handle sample rates up to 192 kHz. The default sample rate will be used when first initializing the audio driver. If an arrangement is monitor activated, the audio streaming will be initialized to the sample rate set in the **Arrangement Properties** dialog. When creating a new arrangement, the default sample rate will be preselected for the arrangement.

The **Active channels** listbox will show all the supported channels for the selected audio interface. If you are going to use only a subset of the available channels, you should disable all unneeded channels, as this will reduce the CPU load required to transfer samples between Podium and the audio driver.

### <a name="toc.interfaces.midi"></a>7.2.2. [](#dialog.interfaces.midi)MIDI I/O

![](images/dialog_interfaces_midi.png)

MIDI interface drivers on Windows PC systems are implemented as separate input and output devices. Check the boxes next to all the inputs and outputs that you want to use with Podium.

For each enabled MIDI input, you can select whether you want Podium to **Use time stamps from driver** when recording MIDI messages. If this option is cleared then the time stamps are set by Podium when the messages are retrieved from the driver. Better accuracy can be achieved when using driver time stamps. Unfortunately many MIDI interface drivers do not support time stamping correctly. One problem can be a fixed time displacement of recorded events. Another problem can be drifting timing, resulting in an increasing displacement of the recorded events. If you are concerned about getting the optimal timing accuracy when recording MIDI inputs, you could try enabling this option and check the results with your MIDI interface.

For each enabled MIDI output, there are three options:

*   **Send Time Code (MTC)**.
*   **Send Timing Clock**: Allows you can enable output of MIDI Timing Clock messages. This special MIDI message is a pulse that is sent 24 times per quarter note. External effects devices can use this pulse to sync for example delay times or LFO speeds with the tempo in Podium. Timing Clock messages are not meant for synchronizing playback with external sequencers.
*   **Detect Mackie compatible control surface**:

Depending on the Windows version you are using, you will likely see a MIDI output named Microsoft GS Wavetable SW Synth. This virtual MIDI output can be used to play a simple software synthesizer that is integrated in Windows. The output of this synth is sent to the audio device selected for sound playback in the Windows **Sounds and audio devices** control panel. Note that conflicts may occur if this audio device is also in use by the currently active ASIO driver in Podium.

### <a name="toc.interfaces.controlsurfaces"></a>7.2.3. [](#dialog.interfaces.surfaces)Control Surfaces

![](images/dialog_interfaces_control_surfaces.png)

### <a name="toc.interfaces.report"></a>7.2.4. [](#dialog.interfaces.report)Report

![](images/dialog_interfaces_report.png)

The report page shows information about the currently active audio driver that can be helpful for diagnostic purposes. The report will include descriptions of any error conditions that have been detected during the log period. The log period will begin when the driver is initialized, and end when you first open the **Interfaces** dialog. Clicking the **Update** button will set a new log end time and update the report. Use the **Reset** button to reset the report and start a new log period. The **Save...** button can be used to export the report to a text file. If you contact Zynewave support about a problem with an audio interface, you may be requested to supply a report file by email.

## <a name="toc.preferences"></a>7.3. [](#dialog.preferences)Preferences

### <a name="toc.preferences.projects"></a>7.3.1. [](#dialog.preferences.projects)Projects

![](images/dialog_preferences_projects.png)

*   **New projects folder**: Specifies the folder where new projects will be stored.
*   **Project template library folder**, **Track template library folder**, **Hardware definition library folder**: Specify the locations of your template and hardware definition files, respectively.

When you run Podium after you have installed it for the first time, you will be presented with a dialog where you can choose to let Podium build a set of default folders, or to open the **Preferences** dialog to configure the folders yourself. If you later on move or rename the folders, you must update the paths to the folders on this page. If the paths are not valid, the **Preferences** dialog will pop up when you start Podium, and the invalid paths will be highlighted with red background color.

### <a name="toc.preferences.engine"></a>7.3.2. [](#dialog.preferences.engine)Engine

![](images/dialog_preferences_engine.png)

*   **Mixer engine bit resolution**: Podium is able to process audio with either 32-bit floating point or 64-bit floating point precision. Setting it to 64-bit will require more memory bandwidth and CPU processing power, so unless you have compelling reasons for wanting 64-bit precision, it is recommended to use 32-bit processing for best performance. Please note that this option has nothing to do with whether you are running a 32-bit or 64-bit version of Windows. 64-bit mixing works the same way whether running on a 32-bit or 64-bit OS. More information can be found in the [about 64-bit mixing](#toc.preferences.about64bit) section.
*   **New sound default file format**: Selects which file format to use when saving sounds created in Podium. The available formats are “.wav”, “.aif”, or “.aiff”. See the [sound](#toc.sound) section for more information.
*   **New sound bit resolution**: When set to **Audio driver setting**, the bit resolution supplied by the audio driver will be used. You can see what the audio driver bit resolution is in the **I/O resolution** info line in the **Interfaces** dialog. Some drivers report 32-bit resolution when in reality the audio interface hardware only uses the upper 24-bits and sets the lowest 8-bits to zero. Consult the manual for your interface to see how many bits the audio converters support. Even if the interface do support a high bit-resolution, you can select the 24-bit or 16-bit fixed resolution settings in this combobox, to reduce the amount of disk space used when saving sound files.
*   **Stream muted sounds for fast response to unmuting**: Clear this option if you want to reduce unnecessary disk usage for muted tracks.
*   **Bypass processing when detecting CPU overload**: When this option is off, Podium will continue to process plugins even when CPU overload is detected. If you have a PC with a multi-core CPU, leaving this option off provides the best uninterrupted audio performance. If you have an old single-core CPU machine, and you experience problems with the UI becoming unresponsive when overload occurs, turning this option on will allow you to still operate the UI during overload.
*   **Release drivers when Podium does not have focus**: The ASIO driver system has the disadvantage that only one application at a time can access a specific audio channel. If you try to start up another application that uses the same ASIO driver that you configured in Podium, you will likely get an ASIO error message in the other application. Enabling this option allows you to switch to another application that uses the ASIO driver, without having to quit Podium first.
*   **Sound file cache folder**: Specifies the location where Podium saves its temporary audio cache files. If you leave this field blank, Podium will use the Windows temporary folder. If you have limited free space on the storage drive where your Windows is installed, or if you have another drive with faster read/write access time, you may want to set up a cache folder on your second drive. Every time you record audio or perform edits in the sound editor, the waveform data is cached to this folder if there isn’t enough available free memory. Since Podium only saves to sound files when the user selects save commands, the space required for the temporary audio files can be quite large. One gigabyte free space is the recommended minimum. The cache files are deleted when you exit Podium.

### <a name="toc.preferences.playrecord"></a>7.3.3. [](#dialog.preferences.playrecord)Play/Record

![](images/dialog_preferences_play_record.png)

*   **Stop playback when end of arrangement/sound is reached**: When enabled, playback will stop when the play cursor has reached the end of the last event in the arrangement, or the last waveform data in the sound. Playback will not stop if recording mode is enabled, to allow recording new material beyond the end of the arrangement/sound.
*   **Deactivate record mode when playback is stopped**: When enabled, the record mode button is automatically deselected when playback is stopped. This can avoid situations where you forget to manually deselect record mode, and then unintentionally start recording again the next time you start playback.
*   The following set of options pertains to **Multi-take recording**. See the [multi-take recording and compositing](#toc.multitakerecording) section for more information.
    *   **Convert record enabled tracks to composite multi-take groups**: Sets under which circumstances multi-take recording should be used. Choose **Never** to disable multi-take recording unless a track has been manually set as composite track.
    *   **Maximum take tracks per composite group**: Sets the maximum number of takes to record in each composite group.
    *   **Delete oldest take when maximum take tracks is reached**: When enabled, takes will be deleted starting from the oldest take, and replaced by new recordings once the track limit is reached.
    *   **Use timestamp as name for new take events**: When enabled, the time of recording (in the format of hours:minutes:seconds) will be used as name for new recorded events. If disabled, recorded events will be named 'Track name: Take n'.
*   **Record enabled MIDI messages**: Select which types of MIDI messages you want to record from external MIDI inputs. Only in rare cases would you need to clear any of the options. If you for example have a synthesizer that transmits SysEx messages when you operate the synth's front panel buttons, you can clear the **SysEx** option to avoid recording your actions.

### <a name="toc.preferences.metronome"></a>7.3.4. [](#dialog.preferences.metronome)Metronome

![](images/dialog_preferences_metronome.png)

*   **Output to MIDI interface**: Enables you to select among the interfaces you have enabled in the **Interfaces** dialog. Set the MIDI channel, the MIDI notes, and note velocities for the bar and beat clicks.
*   **Output to Audio interface**: Set which audio channel to use for outputting the click sound. Selecting the **Stereo** option will output the click as a stereo sound on two audio channels starting with the selected audio channel number. Gain adjustments can be specified for the bar and beat clicks.
*   **Roll back to previous bar/beat on playback start**: Specify how many **Bars** and **Beats** the play cursor should be moved back before playback starts with metronome mode activated.

### <a name="toc.preferences.plugins"></a>7.3.5. [](#dialog.preferences.plugins)Plugins

![](images/dialog_preferences_plugins.png)

*   **Enable plugin multiprocessing**: Select whether to distribute plugin processing to all available processors, or use only a single processor for plugin processing. Podium supports multiprocessing, either in the form of hyper-threading enabled processors, multi-core or multiple physical processors. When enabled, processing can be completed in a shorter period of time, which results in extra available CPU headroom. Disable this option if you encounter plugins that become unstable when using multiprocessing.
*   **Enable ReWire devices**: When disabled, ReWire devices will not be loaded, or detected when creating a new project.
*   **Enable recording of VST plugin MIDI output**: Allows recording the MIDI output of a VST instrument assigned on a track. The recorded sequence events can then be reused on tracks with other instruments. This option is off by default, because some plugins will copy the MIDI data it receives on its input through to its output, resulting in duplicate recorded events when recording overdubbed on an existing sequence.
*   **VST plugin scan folders**: Up to four VST plugin scan folders can be specified. These folders will be searched when Podium scans for plugins. When you run Podium for the first time, it will automatically detect any "Vstplugins" subfolders it can find at: "C:\\", the Windows "program files" folder, and the folder containing the Podium.exe program file.
*   **Automatically search for missing plugins when loading a project**: If you have changed your plugin installations since you created a project, the plugin file references stored in the project may be invalid. You will see these missing plugins highlighted with red background in the device list on the project page. When this option is enabled, after loading a project Podium will automatically try to search for any missing plugin files in the VST plugin scan folders, and relink the plugins if they are found. If this option is not enabled, you can manually do the search with the **Search for Missing Plugins** command in the **Device** menu.
*   **VST plugin editor knob mode**: Select your preferred method for using the mouse to adjust knobs in VST plugin editors. Set to **Plugin default** to use each plugin's default mode. Note that some plugins do not support changing the knob mode.

### <a name="toc.preferences.editors"></a>7.3.6. [](#dialog.preferences.editors)Editors

![](images/dialog_preferences_editors.png)

*   **Activate power when opening arrangement editor**: If enabled, the power button will automatically be activated when you open an arrangement editor page or window. When power is turned on, VST plugins will be loaded, and audio/MIDI devices will be activated. You may want to turn this option off, if you are doing edits in arrangements that does not require the plugins to be loaded. Only one arrangement can be powered on at a time, so if you open a new arrangement editor, the previous powered arrangement will be turned off.
*   **Enable panel show/hide animations in editors**: Sets whether to use sliding animations when selecting list panels in the inspector, and minimizing/restoring the embedded editor or mixer. Clear this option if your PC system has a slow graphics card.
*   **Include editor tool shortcuts in timeline context menus**: The tools in the edit toolbar will be included as shortcuts in the timeline context menu.
*   **Drag scroll acceleration width around editor**: Podium will automatically scroll the timeline area when you move the mouse outside the timeline area while doing a drag operation. This setting specifies the pixel distance outside the timeline area that is used to determine the scroll speed. The farther away you move the mouse cursor, the faster the scrolling.
*   **Drag scroll maximum pixels per second**: Specifies the maximum scroll speed used when the mouse is moved beyond the pixel distance as set in **Drag scroll acceleration width around editor**.
*   **Maximum sequence/sound undo levels**: Maximum number of steps stored in the edit history for each arrangement, sound and sequence object. When you reach the maximum, each new edit will remove the oldest edit from the edit history list. The edit history menu can be opened by right-clicking the undo or redo toolbar buttons. This setting determines the maximum number of edits that are shown in the menu.

### <a name="toc.preferences.appearance"></a>7.3.7. [](#dialog.preferences.appearance)Appearance

![](images/dialog_preferences_appearance.png)

*   **Default button size**: Specifies the overall minimum size of menu, selector and option buttons. Buttons in toolbars can be scaled even larger by adjusting the toolbar height. If you are working with a touchscreen monitor, you may prefer to set a larger button size to be able to comfortably hit the buttons with your finger. The button size can be adjusted directly in the Podium UI by placing the mouse cursor over the project window menu bar, holding the Ctrl key down, and using the mouse wheel to adjust the button size.
*   **Scrollbar size**: Specifies the size of the Podium UI scrollbars.
*   **Button corner roundness**: Specifies the amount of roundness applied to buttons. 0% results in rectangular buttons. 100% results in circular buttons.
*   **Slider knob corner roundness**: Specifies the amount of roundness applied to slider knobs.
*   **Use glass effect on slider knobs**: When enabled, slider knobs will be rendered with a glossy effect. When disabled, knobs will appear as matte.
*   **Panel texture image file**: Allows selecting an image to replace the default brushed metal texture. The image must have a minimum resolution of 32x32 pixels.
*   **Dye texture image to match panel background color**: Enable this option to colorize the custom texture image with the panel background color specified in the **Colors** dialog.

### <a name="toc.preferences.about64bit"></a>7.3.8. About 64-Bit Mixing

If your music production mainly involves using softsynths and encoding the final master to MP3 files, then don't bother with 64-bit mixing as you won't be able to hear any improvements in audio quality.

However, if you are producing music recorded in pristine studio conditions and aimed for reproduction on high end audio equipment, 64-bit mixing will offer better precision and larger dynamic range.

The 64-bit mixing will be utilized when the mixer engine is processing and routing audio internally. The audio will be converted down to 32-bit when routed through plugins that only support 32-bit processing. Support for 64-bit processing was introduced with the VST 2.4 plugin protocol.

When describing floating point numbers, the 32 and 64 bits refer to the amount of memory that is required to store the floats. The bits are split into two parts that store the precision and the exponent for the 'floating point'. 32-bit floats offers 25 bit precision and 64-bit floats offers 54 bit precision.

The advantage of 64-bit mixing is evident when an audio signal is gain scaled or when two or more audio signals are summed in the mixer engine.

Gain scaling occurs when the track gain or pan settings are affecting the audio signal. The scaling involves multiplying the floating point audio signal with a floating point scale value. These multiplications will result in values that use more precision bits than the original audio signal, causing the least significant bits of the result to be discarded.

To illustrate the effect of summing, let's assume that you have two 25 bit precision audio sources that you want to mix together. These sources could be sound files or the 32-bit floating point output of VST plugins. If you mix these sources together without changing the gain of the tracks, the output will fit within 32-bit floats, provided that the summed output does not clip. If you change the gain of one of the tracks, then the 25 bit precision of that track is displaced up or down in relation to the other track. A gain change of 6 dB will result in approximately one bit displacement. When summing the two tracks the combined precision interval has thus been extended beyond the 25 bits that can be stored in 32-bit floats, so the least significant bits are truncated and you loose some of the precision in the audio sources.

This is where 64-bit mixing will offer an advantage over 32-bit mixing, as it can use 54 bit precision to store the results of gain scaling and summing, and thereby reduce the artifacts of the floating point truncations.

So what's the point of the higher precision if the master output is being bounced to a 24-bit or 16-bit sound file? For every audio track that you add to a mix, you add noise as a result of the truncation of the lower bits of the signal. The accumulation of these rounding errors can result in a slightly degraded output that can be present even when rendering to 16-bit sound files.

Despite these apparent mathematical benefits, 64-bit mixing will only yield a minimal quality improvement. 32-bit mixing is still fully sufficient for professional grade productions.

## <a name="toc.colors"></a>7.4. [](#dialog.colors)Colors

![](images/dialog_colors.png)

Podium conforms to the themes and appearance settings in the Windows Display control panel when drawing window frames and dialog boxes. With the **Colors** dialog you can customize the colors used for drawing the contents of Podium windows.

Clicking the **...** buttons next to a color opens a standard Windows color dialog where you can define the color. You may be more familiar with colors specified as combinations of red, green, and blue (RGB) values, but colors can also be specified as hue, saturation, and luminance (HSL) values. You can set colors using both these color models in the Windows color dialog. There are value fields for Hue, Sat, and Lum, and the vertical slider next to the color pad controls the luminance as well.

When trying out different color combinations, it is a good idea to use the **Apply** button. This will store the color settings in the current setup, but will keep the **Colors** dialog open. You can then quickly make incremental changes until you have found a color setup to your liking.

Alternatively to using the **Colors** dialog, you can change the colors of interface elements using the context menu on the color picker in the track inspector. See the [color picker](#toc.colorpicker) section for more information.

### <a name="toc.colors.surfaceandtext"></a>7.4.1. Surface and Text Colors

The **Panel background** color is used for drawing window backgrounds that are shown in Podium windows. The **Listbox background** is the background color for listboxes such as the content and device panels on the project page.

The **Button** color is used for all buttons, including scrollbars. The **Slider knob** color is used for the knobs indicating the position of sliders. The **Text** color is used for all text that is written on panels, buttons, listboxes, and sequence events.

The colors for **Active selection fill** and **Active selection text** are used to draw selected objects that have keyboard focus. Having keyboard focus means that the selected objects will respond to keyboard commands such as the arrow keys to move the focus and the Delete key to delete the selected objects. The **Inactive selection fill** and **Inactive selection text** colors are used to draw selected objects that do not have keyboard focus.

The **Timeline fill** color defines the background color of the timeline inside editors. The **Timeline text** color is used for text inside the timeline ruler region, for waveform display in the sound editor, as well as for events displayed in the navigator region in the note and sound editors. The **Timeline grid** color is used to draw the grid lines indicating bars and subdivisions.

**Default track color** is used for drawing the track headers, as well as for drawing the background of sequence events on tracks that have no color assigned. Use the [color picker](#toc.colorpicker) in the inspector, or the **Track Properties** dialog to set a color for the focus track. If the **Colorize note events with track colors** option is enabled in the **[Notes Region](#toc.notesregion)** dialog, the track color will also be applied to note events inside sequences on the track. See the [note editor](#toc.noteeditor) chapter for more information.

### <a name="toc.colors.indicatorsandhighlight"></a>7.4.2. Indicator and Highlight Colors

The colors for **Play and power**, as well as for **Record** are used on related transport toolbar buttons, the play cursor, and the loop and punch bars in the timeline ruler regions. The **Plugin editor** color is used on selector buttons when the plugin's native editor is open. The **Bounce** color is used for bounce buttons on track headers, as well as for the bounce waveform overlay on bounce enabled tracks. The **Solo**, **Mute**, and **Record** colors are used for the respective controls on track headers. The **Record** color is furthermore used on track lane backgrounds and sequence events when in recording mode.

You can set two colors to define the parameter gradation color range. The resulting range of colors is used to draw the body of the curve in curve sequences, as well as note events, the glow inside slider ridges, and the glow inside the value ring on parameter dials. The first color is used for the lowest parameter value, and the second color for the highest parameter value.

The level meter gradation color range is used to draw the level meters in the tracks and mixer regions. The first color is for -infinite dB, and the second color is for 0 dB. If the level goes beyond 0 dB, then the meters are painted with the **Level meter overload** color.

### <a name="toc.colors.track"></a>7.4.3. Track Colors

The percentage values set for **Overall color opacity**, **Rack/header/strip opacity**, and **Lane background opacity** control the blending of track colors with the panel background. An opacity value of 0 will ignore track colors and draw all objects with the specified **Default track color**. Lowering the **Overall color opacity** value can be a convenient way to tone out track colors, if the contrast with the panel background color is too strong. **Lane background opacity** controls the blend of the track color that is overlaid on the timeline with the timeline fill color.

Track colors can be further customized using the **Group track luminance** and **Parameter track luminance** offset settings. Track luminance offsets will be applied to the track color of the specified track types. This allows you to define that, for better distinguishability, parameter automation tracks and curve sequence events should be painted with a darker or brighter shade of the track color.

### <a name="toc.colorsetups"></a>7.4.4. Color Setups

Color setups are saved as standard Podium setup files, with the important difference that they only store the settings specified in the **Colors** dialog.

Podium includes a number of color setups. Select a color setup using the **Load Color Setup** submenu on the **Setup** menu. You can save your color customizations as a color setup file with the **Save Color Setup...** command.

Color setup files are stored in the "Zynewave\Podium\Color Setups" folder inside the Windows Application Data folder. Choose the **Explore Setup Folder** command on the **Setup** menu to open a Windows file explorer window directed to the setup folder location.

## <a name="toc.favoritefolders"></a>7.5. [](#dialog.favoritefolders)Favorite Folders

![](images/dialog_favorite_folders.png)

The **Favorite Folders** dialog is used to set up links to a selection of folders that you use frequently. These favorite folders can be accessed in the [browser](#toc.browserpage) by clicking the favorite toolbar buttons or by using the **Favorites** submenu in the file browser menu.

The dialog can be opened from the [Setup menu](#h.8wrwkuc3rez6) or with the **Organize Favorites...** command in the file browser menu.

*   **Insert new...**: Opens a **Browse For Folder** dialog where you select the folder you want to add to the folder list. The folder will be inserted at the highlighted position in the list. Another way to add favorite folders is to use the **Add to Favorites** command in the file browser menu. This will add the current folder in the file browser to the end of the favorites list.
*   **Delete**: Deletes the currently highlighted favorite. Note that only the favorite link is deleted. The actual folder is not deleted.
*   **Move up** & **Move down**: Moves the highlighted favorite up or down in the list. The order that the favorites are arranged in the list is the same order used in the favorite submenus.
*   **Show full folder path when showing favorites in menus**: Disabling this option will show only the name of the last subfolder in each favorite. Enable this option if you have vaguely named subfolders and need to have the full path to uniquely identify your favorites.

## <a name="toc.editorprofiles"></a>7.6. Editor Profiles

The layout of the arrangement, note, curve and sound editors are defined by editor profiles. A profile is constructed of a list of different types of regions that are stacked as layers in the editor.

The Podium default setup contains a complete set of profiles. You can modify these or create you own alternative new profiles. A typical task for many users would be to modify the toolbars in the default profiles to fit a certain screen size. The default setup is constructed to fit on XGA resolution screens. If you are using a higher screen resolution you may want to join the edit and transport toolbars into one, to gain extra screen space for the other regions in the profile.

Several profiles can be defined for each editor type in which case you can switch between the profiles using the **View** menu in the editor. This can be used for example to switch between a standard editor profile and an event list profile, or to switch between arrangement profiles with or without a mixer region.

#### [](#dialog.editorprofiles)Editor Profiles

![](images/dialog_editor_profiles.png)

The profiles in the editor **View** menu are shown in the same order as they are inserted in the **Profile list**. Use the **Move Up** and **Move Down** buttons to reorder the profiles. When a new editor is opened, the first compatible profile in the list will be selected by default.

The **Insert New** button will insert a new blank profile into the profile list. The **Copy** button will insert a duplicate of the currently selected profile. The **Delete** button deletes the currently selected profile. Please note that if you inadvertently delete a profile or create new profiles without adding regions to the profile, opening an editor may show a blank page. In that case you should either reconfigure your profiles, or if everything is completely messed up, restore the default setup with the **Load Default Setup** command on the **Setup** menu of the project window.

#### [](#dialog.editorprofileproperties)Editor Profile Properties
You can access the properties of a profile by selecting it in the **Profile list** and clicking the **Properties...** button. You can also access the properties for the currently selected profile in an editor by selecting **Editor Profile Properties** on the **View** menu.

![](images/dialog_editor_profile_properties.png)

The **Profile name** is used to identify the profile in the **Editor Profiles** dialog and on the **View** menu in editors. The **Editor type** setting determines what types of sequences this profile is intended for. The **View** menu in editors will only show profiles with a compatible editor type. The available editor types include **Arrangement**, **Note**, **Curve**, **Sound - Master**, **Sound - Slave**, **Embed** variations, and the generic **All types**. The **Sound - Master** profile type is used when opening sound objects directly from the project window, and thus should contain a transport toolbar. A **Sound - Slave** profile will typically not contain a transport toolbar, as this profile type is used when opening the sound through an audio event in an arrangement editor, and thus will be linked to the transport in the arrangement editor. The embed variations of the note, curve, and sound types are used for the embedded editor region. The **All types** editor type will be available in all editors, and is typically used for an event list profile.

The **Region list** shows a descriptive label of all the regions that are currently added to the profile. Clicking the **Insert New...** button will show a menu where you can select a region type, and subsequently a properties dialog for the selected region type is opened. Alternatively you can click **Copy** to insert a duplicate of the currently selected region. The **Move Up** and **Move Down** buttons can be used to rearrange the regions. Clicking the **Properties...** button will bring up the properties dialog for the currently selected region.

Some profile and region settings are not accessible through the properties dialogs but are stored in the profile when modified in the editor. These settings include positions of horizontal and vertical drag bars, panel collapse states and various mode selectors in the regions. When a profile is selected in an editor, these 'last used' settings will be used as defaults.

A common feature found in many of the region properties dialogs are settings for minimum and maximum region height. Setting the minimum and maximum to the same value will define a fixed height region. Setting the minimum lower than the maximum means the region can resize according to the total height of the editor. A profile can contain multiple resizable regions. The **Embedded Editor** and **Mixer** regions have a title bar which can be dragged to resize the region. Other resizable regions can be separated by a **Space** region configured to be used as a drag handle for resizing regions.

### <a name="toc.spaceregion"></a>7.6.1. [](#dialog.spaceregion)Space Region Properties

![](images/dialog_space_region.png)

The space region is used for adding visual separation between other regions in a profile.

#### Layout

*   **Region height:** Region height in pixels.
*   **Fill type:** Visual effect. The choices are: Blank, Shadow, Up slope, Down slope, Bump, Recess.

#### Actions

*   **Use as drag handle for resizing regions**: Some of the other region types are resizable and have settings for minimum and maximum height. Enable this option to be able to drag the space region in the editor to resize the surrounding regions.

### <a name="toc.toolbarregion"></a>7.6.2. [](#dialog.toolbarregion)Toolbar Region Properties

![](images/dialog_toolbar_region.png)

#### Layout

The list shows the current contents of the toolbar.

*   **Insert**: When you want to insert elements into the toolbar, select the position you want to insert at in the **Layout** list, select the desired item in the **Elements** list and click **Insert**.
*   **Remove**: Removes the currently selected layout element.
*   **Move &up**: Moves the currently selected element up in the list.
*   **Move &down**: Moves the currently selected element down in the list.
*   **Region &height**: Height of the region in pixels.

#### Elements

The **Elements** list shows all the available elements that can be added to the toolbar. The list is divided into sections. The **Default groupings** section can be used to insert a whole set of elements matching the toolbars you find in the Podium default setup. The **Separator** element is a vertical line useful for separating groups of toolbar elements. The **Align to right** break element is not a visual toolbar element, but indicates that all elements inserted after the break will be stacked against the right border of the editor.

### <a name="toc.timelinerulerregion"></a>7.6.3. [](#dialog.timerulerregion)Timeline Ruler Region Properties

![](images/dialog_timeline_ruler_region.png)

The timeline ruler region is used to show time resolution legends, a triangular handle for the cursor position and curtain handles for the selection, punch, and loop ranges. The region has a context menu with options to set the ranges and to select a mouse edit mode.

#### Layout

*   **Region height**:
*   **Show timeline numbers**:
*   **Show clock times above bar numbers**:
*   **Show edit and play cursor**:
*   **Show segment range**:
*   **Show punch range**:
*   **Show loop range**:
*   **Auto-hide when shown range is disabled**:
*   **Show edit mode selector buttons**:

#### Actions

*   **Use mouse wheel to zoom**
*   **Left-click to slide timeline**

### <a name="toc.navigatorregion"></a>7.6.4. [](#dialog.navigatorregion)Navigator Region Properties

![](images/dialog_navigator_region.png)

*   **Minimum region height:**
*   **Maximum region height:**

### <a name="toc.scrollbarregion"></a>7.6.5. [](#dialog.scrollbarregion)Scrollbar Region Properties

![](images/dialog_scrollbar_region.png)

The scrollbar region shows a horizontal scrollbar for navigating the timeline.

*   **Show zoom to full range button**
*   **Show zoom to selection button**
*   **Show zoom slider**

### <a name="toc.formatregion"></a>7.6.6. [](#dialog.formatregion)Format Region Properties

![](images/dialog_format_region.png)

The format region is used to show and edit either tempo or marker events.

*   **Region height:**
*   **Show event type:** Options are **Marker events** and **Tempo events**.

### <a name="toc.tracksregion"></a>7.6.7. [](#dialog.tracksregion)Tracks Region Properties

![](images/dialog_tracks_region.png)

The tracks region is the cornerstone of the arrangement editor. The **Tracks Region Properties** dialog contains three sections: layout, track header options, and timeline options.

#### Layout

The **Track separation space** and **Group separation space** settings control the number of pixels that individual tracks and track groups will be spaced apart respectively. The **Vertical group bar width** is the width of the hierarchy bars shown to the left of the track headers.

Track headers and lanes are tinted with the color defined for the track. The amount of coloring can be defined with the **Track header color opacity** and **Track lane color opacity** settings.

#### Track Header Options

The appearance of pan, gain, and send controls on track headers can be specified using the **Control type** setting. Choices are Dial, Slider, and Readout slider. Choose None if you don’t want controls on the headers.

Meters on track lane headers can be configured for either horizontal or vertical layout with the **Audio meters** setting. To remove the meters from headers, choose None.

The appearance of track headers can be further controlled using the settings **Show track color bar at right edge of header**, **Show effect chain**, **Show device bypass buttons**, **Show device automation record buttons**, and **Set minimum track height to fit contents**.

#### Timeline Options

Checking **Show track separation bars** will draw horizontal bars in the separation space. These can be used as visual guides if you are using a large display area. When **Show sequence event headers** is enabled, sequence events will be split into a header area that is aligned with the track headers, and a separate area for showing the miniature of the sequence contents.

Normally the sequence event area is filled with the miniature graphics and any text and symbols are drawn on top of the miniature. Clear the **Show sequence event names** option if you prefer to do your arranging without worrying about naming your sequences and sounds. When the **Show sound event fade curves** option is enabled, all sound events show their fade curve. When disabled, only the event under the mouse cursor shows a fade curve. Clear the **Show embedded sequence editor** option to hide the editor that is normally embedded at the bottom of the tracks region.

### <a name="toc.embeddededitorregion"></a>7.6.8. [](#dialog.embeddedregion)Embedded Editor Region Properties

![](images/dialog_embedded_editor_region.png)

### <a name="toc.mixerregion"></a>7.6.9. [](#dialog.mixerregion)Mixer Region Properties

![](images/dialog_mixer_region.png)

The mixer region is typically embedded in an arrangement editor together with a tracks region. Alternatively you can define a dedicated mixer arrangement profile with one or more mixer regions, and set up a second project window for the mixer.

The **Mixer Region Properties** dialog contains settings for the mixer layout. It also allows you to customize mouse actions in the mixer.

*   **Minimum meter height**: a vertical scrollbar will appear in the mixer region if it is resized smaller than the specified meter height.
*   **Minimum strip width**:
*   **Dock master chain** and **Dock bus returns**: the mixer can be configured to show master chain and bus return tracks in separate docked panels, use these drop-down lists to specify whether the panels should be docked to the left or the right or not docked at all.
*   **Gain control**, **Pan control**, and **Send control**: the appearance of the different controls can be specified.
*   **Use small font**, **Show scrollbar even when strips fit in view**, **Show hierarchy/signal flow arrows**:
*   Actions can be specified for clicking, Shift+clicking, Ctrl+clicking, Alt+clicking, middle-clicking, right-clicking, and double-clicking the device and input rows.

### <a name="toc.notesregion"></a>7.6.10. [](#dialog.notesregion)Notes Region Properties

![](images/dialog_notes_region.png)

The notes region is used with note sequences. The **Notes Region Properties** dialog allows you to control the appearance of the region.

The background of the region is drawn with ghosts of all notes in the arrangement. The **Ghost note intensity** setting defines the visibility of these ghost notes. There is also a setting to **Hide muted ghost notes**.

### <a name="toc.velocityregion"></a>7.6.11. [](#dialog.velocityregion)Velocity Region Properties

![](images/dialog_velocity_region.png)

When included in a note editor profile, it will show note event on/off velocities.

In addition to the minimum and maximum heights settings, the dialog also has a setting for **Curve fill opacity**. A lower opacity value allows the background guides to show through the painted body of the curve or the note velocity columns.

### <a name="toc.curveregion"></a>7.6.12. [](#dialog.curveregion)Curve Region Properties

![](images/dialog_curve_region.png)

When included in a curve editor profile, it will show curve events.

In addition to the minimum and maximum heights settings, the dialog also has a setting for **Curve fill opacity**. A lower opacity value allows the background guides to show through the painted body of the curve or the note velocity columns.

### <a name="toc.channelsregion"></a>7.6.13. [](#dialog.channelsregion)Channels Region Properties

![](images/dialog_channels_region.png)

The channels region is the cornerstone of sound editors. It will display the waveform of each channel in a sound.

The **Channels Region Properties** dialog allows you to specify the minimum and maximum heights of the region.

### <a name="toc.eventlistregion"></a>7.6.14. [](#dialog.eventlistregion)Event List Region Properties

![](images/dialog_event_list_region.png)

An event list region contains a listbox that shows text descriptions of the events. The **Event List Region Properties** dialog contains size settings for the region. There are also settings to control how the event times are displayed as percentage variations from the selected editor quantize value.

## <a name="toc.windows"></a>7.7. [](#dialog.windows)Windows

![](images/dialog_windows.png)

The position and size of the windows that you open in Podium are stored in the setup file. Some windows store additional information, such as the browser window which has options that can be configured for each browser window. Deleting a window in the Windows dialog will remove the setup information, and the window will thus appear in its default configuration the next time it is opened.

Many of the dialog windows will also open at the position that you last moved them to, but these positions are not stored in the setup file. Each time Podium is started, dialogs will open in their default center position. An exception to this, is the standard file dialog. If you move and resize the file dialog, it will appear as you last used it the next time you start Podium.

Another exception are plugin editor windows. Plugins are linked to the tracks that they are assigned to, so the plugin editor positions are stored in the properties of the tracks, and thus will be saved in the project file.

Podium follows the guidelines for Windows standard key shortcuts. Pressing Ctrl+Tab will cycle key focus between all open windows. Pressing Alt+F4 will close the window that currently has focus. Note that if you press Alt+F4 with focus on the application window, this will invoke the **Exit...** command in the **Podium** menu.

### <a name="toc.screens"></a>7.7.1. Screens

Windows in Podium are linked to virtual screens. Switching between screens allows you to quickly change the window layout to suit your preferred workflow for example for arranging, mixing, file browsing or plugin editing. When you switch screens, all currently open windows will be closed, but stored in the setup as being open in the screen you are switching away from. Any windows that were previously open in the screen you are switching to, will be opened.

There are four virtual screens that can be accessed on the **Setup** menu or using shortcut keys F9 to F12. When the **Windows** dialog is open, you can use the **Current screen** combobox to switch between screens. The descriptions in the **Window list** will show **\<Open>** if a window is currently open, or **\<Open in screen x>** if it is open in another screen. Clicking the **Show** button will open the selected window into the current screen.

The Podium application window is always open in all the screens. If the window is maximized, it will be shown maximized in all screens. If it is not maximized then the window position and size can be set separately for each screen.

When you select a command to open a window that is open in another screen, Podium will automatically switch to that screen and activate the window there. Let's say you in screen 1 have positioned the application window to fill the entire display, and in screen 2 have positioned it to fill only half the display with a sequence editor open in the other half. If you are working in an arrangement editor in screen 1, and double-click a sequence event to open the sequence editor, then Podium will switch to screen 2 with the alternative layout of the arrangement and sequence editors.

* * *

# <a name="toc.controlsurfaces"></a>8. Control Surfaces

Podium supports the Mackie control surface standard. This includes full support for Logic Control, Mackie Control Universal (MCU) and MCU Pro. Podium also supports control surfaces from other manufacturers that can be configured to run in Mackie emulation mode. An example is the Behringer BCF-2000, which supports a subset of the Mackie control features.

## <a name="toc.controlsurfaceconfiguration"></a>8.1. Configuration

To enable a control surface, the MIDI input/output connections must be activated in the Podium **Interfaces** dialog. Enable the **Detect Mackie compatible control surface** option for each MIDI output that is connected to a control surface. Podium will auto-detect any available control surfaces when you power-on the control surface, when you start Podium, or when you reconfigure the MIDI interfaces. If you connect the MIDI cables after the control surface is powered-on and Podium is running, the auto-detection will not engage. You can then force detection by opening the **Interfaces** dialog and clicking **OK**.

Some control surfaces support uploading new firmware versions via MIDI. To do this with Podium, first disable the **Detect Mackie compatible control surface** option to prevent Podium from activating the control surface. Also make sure that neither **Send Timecode (MTC)**, **Send Timing Clock**, or the MIDI metronome is enabled for the MIDI output. (For information on metronome configuration, see the **[Metronome](#toc.preferences.metronome)** preferences section.) Open the **Device** menu on the project page, point to **Import Hardware Definition** and choose **Generic Effect Device**. Select the MIDI output interface for the control surface in the **Import Hardware Definition** dialog and click **OK**. Use the **Import File...** command in the **Content** menu and select the MIDI file with the firmware update. The imported arrangement should contain a track with one or more stream events. Make sure the 'Generic (01)' MIDI mapping is assigned on the main track. Follow the instructions for your control surface to put it in firmware update mode, and then start playback in Podium to begin the firmware upload.

## <a name="toc.mixerintegration"></a>8.2. Mixer Integration

When arrangement monitoring is activated, the mixer strips in the Podium mixer will show channel indicators on the tracks that are linked to a control surface fader. Each indicator shows the channel number of the corresponding fader on the control surface. The controlled channels can be shifted using the fader navigation buttons on the control surface.

![](images/surface_mixer.png)

When a control surface is present, the mixer view menu has a **Follow control surface** option. If enabled, the mixer will scroll when navigating the fader channels on the control surface.

If the control surface supports touch sensitive faders, the fader knobs in the Podium mixer will light up when the control surface faders are touched (similar to when you grab a fader with the mouse). When a fader is touched on the control surface you cannot grab the fader with the mouse in the Podium mixer. Likewise, when a fader is grabbed by the mouse, moving the faders on the control surface will have no effect.

Having a control surface with touch sensitive motorized faders is an advantage when working with parameter track automation during playback. If fader touch is not detected, Podium will assume that the fader is not grabbed and so will send fader movements of any already recorded automation. This can result in motor resistance when you try to move the fader to edit the automation.

If the control surface does not support touch sensitive faders, you can use the channel record button on parameter tracks to simulate fader touch. Pressing and holding the channel record button will have the same effect as grabbing the fader with the mouse, and you can then move the fader without motor resistance, until you release the record button. This function is also useful with touch sensing faders, as it allows you to start an automation edit without having to catch a moving fader.

## <a name="toc.mackiecontrol"></a>8.3. Mackie Control

![](images/surface_mcu.png)

![](images/surface_mcu_pro.png)

### <a name="toc.mackiehelpmode"></a>8.3.1. Help Mode

You can toggle help mode on/off by pressing the rightmost button three rows down (factory label "UNDO"). When help mode is activated the help button LED will blink and all other buttons are disabled. Pressing any button will show a help text for that button in the MCU LCD display. If the button has multiple key combination functions this is shown with the combo key in brackets (for example [Shift]) followed by a description. The V-Pots and Jog wheel will scroll the text in the LCD display.

The factory button labels on the MCU have been reused as widely as possible in the Podium button layout. But for the buttons that are special to Podium, the help mode is useful as a quick reminder.

![](images/surface_display_help.png)

### <a name="toc.mackiekeyboardsimulation"></a>8.3.2. Keyboard Simulation

Some of the Mackie buttons will simulate key presses on a normal PC keyboard. As long as Podium is running, the buttons can be used to control any application that has the keyboard focus. The buttons that simulate key presses are (from bottom to top on the MCU):

*   Cursor keys
*   Zoom (Tabulator)
*   Shift, Control, Alt
*   Option (Windows applications key)
*   Cancel (Escape)
*   Enter
*   Global 7 (Undo/Ctrl+Z)
*   Global 8 (Redo/Ctrl+Y)
*   F1-F8

The Shift, Control and Alt keys can be combined with other keys. This means that a large range of the Windows key shortcuts and Podium zoom and edit shortcuts can be simulated on the MCU. Some examples: You can switch to other applications with Alt+Tab, shift between open windows with Ctrl+Tab, close a window with Alt+F4, open the properties dialog with Alt+Enter, navigate lists with the cursor keys, refresh file browsers with F5 etc. When Podium has key focus, you can jump between the different panels and editors with Tab and F1-F8, navigate the lists in the track inspector and assign objects to tracks, navigate events and open editor windows, move events with Ctrl+Cursor keys etc. If you are using a mouse next to the MCU, you can press combinations of the Shift, Control and Alt keys to activate the different mouse zoom tools.

### <a name="toc.mackiearrangementmode"></a>8.3.3. Arrangement Selection Mode

When first starting Podium, the MCU will be in arrangement selection mode. In this mode you can use the V-Pots or Jog wheel to scroll in a list of all arrangements in the project. The LCD display will show the currently selected arrangement. The rightmost button just above the record button (factory label "SOLO") is the monitor button. This button will blink when in arrangement selection mode, and light constantly when an arrangement is activated. Press the monitor button or press a V-Pot to activate monitoring for the currently selected arrangement. The Podium project windows will show the arrangement. Deactivating monitoring will return the MCU to arrangement selection mode.

![](images/surface_display_arrangement.png)

### <a name="toc.mackiemixermode"></a>8.3.4. Mixer Mode

When monitoring is activated the MCU will be in mixer mode. In this mode all faders and buttons will become active, and the LCD display will show track names and meters for each fader channel. The group of four fader bank navigation buttons can be used to shift the displayed channels by a full bank or by a single channel.

The group of six buttons above the transport buttons (factory label "AUTOMATION") controls which tracks are assigned to the faders. The top three buttons selects between master, main and bus return sections. This follows the default layout of the docked master and bus return sections in the Podium mixer. Pressing and holding multiple buttons combines the sections. The display below shows an example of a main track section:

![](images/surface_display_tracks.png)

The tracks with names shown on the second line are parameter automation tracks. You can toggle the display of these with the Parameter Tracks button (factory label "LATCH"). The Touch button next to it is used for creating parameter automation tracks. Holding down this button while pressing either a channel select button or a V-Pot will create a new parameter track with the corresponding parameter assigned.

As an alternative to the flat track layout you can enable the group mode button (factory label "GROUP"). This mode will assign tracks to the faders according to the track hierarchy. In this mode the channel 1 fader is assigned the current group, and faders 2-8 are assigned child tracks of the group track. Pressing the fader bank navigation buttons will shift only faders 2-8, leaving the group track always on channel 1. The display below shows an example of group mode:

![](images/surface_display_group.png)

To quickly navigate between tracks in group mode you use the Group Select button (factory label "GLOBAL VIEW"). Press it to toggle group select mode on/off, after which you can use the select buttons to navigate the hierarchy. Pressing the select button for the Drums track in the previous example will assign the Drums track as the new group track. If you have multiple group layers you can continue downwards in the hierarchy this way. To step up to the parent group press the channel 1 select button.

![](images/surface_display_group_select.png)

Instead of toggling group select mode on/off, you can press and hold the group select button while pressing a channel select button. Pressing and holding the group select button while pressing the fader bank navigation buttons will shift the group track to the previous or next group within the parent group.

* * *

# <a name="toc.zplugins"></a>9. zPlugins

The full version of Podium comes with three FX plugins: zPEQ, zPitch and zReverb, only zPEQ and zPitch are included with the demo version. These plugins are all VST 2.4 compatible, this includes support for double-precision processing, which is used when the Podium mixer engine is running in 64 bit mode.

You find the zPlugins in the Zynewave Effects folder of the device panel in the [track inspector](#toc.trackinspector).

To use a zPlugin, simply assign it to an effect track. An effect track can be managed both on the track header and in the inspector group panel. The zPlugins can be controlled using their native editors launched by clicking the name of the plugin on the effect track (or by pressing E with the plugin track selected). They can also be controlled using their embedded editors in the track panel of the inspector. To display an embedded editor, click the area immediately to the left of the **X** button on the effect track. Both the native editors and the track inspector can be resized by dragging their borders. Note that the plugin editors are only available when the arrangement is activated and the plugins have been loaded into memory.

The zPlugins are installed in "Program Files\Zynewave\Podium\Vstplugins\Zynewave Effects". When using the project wizard to scan and import plugins, Podium will search this folder in addition to the user-specified Vstplugin folder.

The zPlugins can be used in other hosts using their generic plugin editor, which means that the graphic displays for zPEQ and zReverb are only available when the plugins are used in Podium. The zPlugins include a feature that allows Podium to reduce the plugin CPU usage when the plugin is processing silence. This feature is not part of the standard VST specification so it will not be available when the plugins are used in other hosts.

## <a name="toc.zpeq"></a>9.1. [](#zpeq.editor)zPEQ

![](images/window_zpeq.png)

zPEQ is a parametric equalizer plugin that supports processing of mono, stereo and up to 32 channel surround processing. Up to six bands can be enabled and each band has parameters for band type, frequency, gain and Q.

#### Frequency Response Display

*   Double-click the background to enable the next unused band with the frequency set to the clicked position.
*   Double-click a band handle to disable the band.
*   Click+Drag to adjust frequency and gain of the nearest band.
*   Alt+Click+Drag to adjust the Q value of the nearest band.
*   Ctrl+Click in the display to toggle display of phase offset as a translucent layer on top of the response curve.

Right-click in the display to show a band type menu for the nearest band:

*   [](#cmd.zpeq.loshelf)**Low Shelf**: Increases or reduces frequencies below the cutoff frequency.
*   [](#cmd.zpeq.hishelf)**High Shelf**: Increases or reduces frequencies above the cutoff frequency.
*   [](#cmd.zpeq.parametric)**Parametric**: Makes a bell-shaped bump in the frequency reponse curve.
*   [](#cmd.zpeq.bandreject)**Band Reject**: Attenuates within a narrow frequency band.
*   [](#cmd.zpeq.bandpass)**Band Pass**: Attenuates outside a narrow frequency band.
*   [](#cmd.zpeq.lopass)**Low Pass**: Cuts frequencies above the cutoff frequency.
*   [](#cmd.zpeq.hipass)**High Pass**: Cuts frequencies below the cutoff frequency.
*   [](#cmd.zpeq.disable)**Disable Band**: Shortcut for disabling the band.

#### Band Parameters

Below the frequency response display are controls for adjusting the parameters of each band. These controls are only shown in the editor window and not in the embedded rack and mixer editors.

*   [](#zpeq.bandenable)**Band Enable**: Toggles the band on/off. Shift+Click to enable the band and disable all other bands.
*   [](#zpeq.bandtype)**Band Type**: Click or Right-Click to show the band type menu.
*   [](#zpeq.bandfreq)**Band Frequency**: Specifies the center or corner frequency of the band. The maximum band frequency is 20000 Hz. This limit may be lower depending on the current samplerate.
*   [](#zpeq.bandgain)**Band Gain**: Gain is only used by shelving and parametric band types.
*   [](#zpeq.bandq)**Band Q**: The behaviour of the Q parameter depends on the band type.
    *   For Low shelf and high shelf, Q is slope in the range of 3 to 12 dB/octave at the center frequency.
    *   For Parametric, band reject and band pass, Q is bandwidth in the range of 0.01 to 10 octaves. One octave is defined by two frequencies where the lower frequency is half the upper frequency. Parametric bandwidth defines the frequencies where the gain is halved. Band reject and band pass bandwidth defines the frequencies where the gain is reduced by 3 dB.
    *   For Low pass and high pass, Q is resonance at the corner frequency. The dB/octave is fixed, but as a workaround you can add an additional band of the same type and at the same frequency to create steeper slopes.

## <a name="toc.zpitch"></a>9.2. [](#zpitch.editor)zPitch

![](images/window_zpitch.png)

zPitch is a pitch-shift plugin that has been designed to allow smooth automation of the pitch parameter.

The central pitch band can be used as an alternative way to adjust the **Pitch** parameter:

*   Click+Drag the pitch band to adjust in full semitone steps.
*   Shift+Click+Drag the pitch band to adjust in cents.
*   Ctrl+Click to reset to 0% transposition.

#### Parameters
*   [](#zpitch.pitch)**Pitch**: Amount of pitch transposition. One semitone equals 100 cents and the valid range is -1200 to +1200 cents.
*   [](#zpitch.mix)**Mix**: Ratio of dry/wet signal (0% is all dry, 100% is all wet). Set it at ~50% and you can sing harmony with yourself, with the pitch parameter controlling the harmony voice.

## <a name="toc.zreverb"></a>9.3. [](#zreverb.editor)zReverb

![](images/window_zreverb.png)

zReverb is a reverb that allows individual placement of two mono input sources and a stereo microphone within a room enclosure. The reverb is based on a combination of early reflections and late diffusion.

The left side panel shows [](#zreverb.widthlabel)**Width**, [](#zreverb.lengthlabel)**Length** and [](#zreverb.heightlabel)**Height** room dimensions as defined by the room parameters. The [](#zreverb.decaylabel)**Decay** time measures how long it takes for the reverberation signal to decrease by 60 dB.

The center display area illustrates the room dimensions with draggable handles for the position of the microphone and up to two sources (L and R in stereo setup). The line extending from the microphone handle indicates the angle of the microphone direction. The bar next to the floor square illustrates the height of the room. The handle positions can also be adjusted with the [](#zreverb.source1label)**Src1**, [](#zreverb.source2label)**Src2** and [](#zreverb.miclabel)**Mic** parameters.

The reverb stereo output is generated by simulating a pair of directional microphones angled at 90° in an XY stereo set-up. For optimal recording of the direct signal, the microphone and sources should be aligned so that the angle between the two lines extending from the microphone towards the two sources is 90°.

*   Click a handle to drag its position.
*   Alt+Click to set and drag the microphone angle.

#### [](#zreverb.roomlabel)Room

*   [](#zreverb.roomsize)**Size**: The room size in square meters. This parameter also controls the diffusion delays.
*   [](#zreverb.roomwidthlength)**Width:Length**: Changes the ratio between room width and length while keeping the room size constant.
*   [](#zreverb.roomheight)**Height**: Increasing the room height results in a longer decay time without affecting the initial reflections from the walls.
*   [](#zreverb.wallreflection)**Wall Reflection**: Specifies how much of the signal is preserved each time a reflection bounces off a wall. This value is the inverse of the absorption coefficient for the wall.

#### [](#zreverb.placementlabel)Sources & Microphone

*   [](#zreverb.source1x)**Source1 X**: The source1 relative width placement in the room.
*   [](#zreverb.source1y)**Source1 Y**: The source1 relative length placement in the room.
*   [](#zreverb.source2x)**Source2 X**: The source2 relative width placement in the room.
*   [](#zreverb.source2y)**Source2 Y**: The source2 relative length placement in the room.
*   [](#zreverb.micx)**Mic X**: The microphone relative width placement in the room.
*   [](#zreverb.micy)**Mic Y**: The microphone relative length placement in the room.
*   [](#zreverb.micangle)**Mic Angle**: The center direction of the stereo microphone set-up.

#### [](#zreverb.diffusionlabel)Diffusion

*   [](#zreverb.threshold)**Threshold**: Specifies the gain range that early reflections will decay before late diffusion starts. Having more reflections can provide a more detailed room presense but can also cause undesired echoes. Decreasing the threshold will increase the CPU usage required for processing the additional reflections. Note that the number of generated reflections also depends on the settings of the room, source and microphone parameters.
*   [](#zreverb.hidecaytime)**Hi-Decay**: The relative high frequency decay time. Decreasing this value can be used to simulate that high frequencies decay faster when sound travels in air. Room interior materials can also influence absorption of high frequencies.
*   [](#zreverb.stereowidth)**Stereowidth**

#### [](#zreverb.dampingfilterlabel)Damping Filter

*   [](#zreverb.locut)**Locut**: The damping locut and hicut defines the frequency dependant absorption of the walls. The amount of damping applied to each reflection depends on the number of walls in its path. The late diffusion signal is fully damped and can be further damped with the hi-decay parameter.
*   [](#zreverb.hicut)**Hicut**: See description of **Locut**.

#### [](#zreverb.levelslabel)Levels

*   [](#zreverb.reflectionslevel)**Reflections**: The level of the early reflections signal mixed into the output.
*   [](#zreverb.diffusionlevel)**Diffusion**: The level of the late diffusion signal mixed into the output.
*   [](#zreverb.drylevel)**Dry**: The level of the stereo input mixed unprocessed into the output. When dry signal is applied to the mix, the source to microphone direct signal is removed from the mix and the delay is adjusted so that the reverb signal will sound in sync with the dry signal.

#### [](#zreverb.diffusiondelayslabel)Diffusion Delays

*   [](#zreverb.delaylinetime)**Delay**: The 16 delay parameters enable fine tuning of the diffusion sound (diffusion delay lines). The delay times are scaled by the room **Size** parameter. A lot of different soundscapes can be modeled by manipulating the delay times. The delay parameters are only accessible in the editor window and not in the editor embedded in the [track inspector](#toc.trackinspector).

#### [](#zreverb.tuningpad)Tuning Pad

*   Click towards the right edge to apply an increasing amount of randomization to all the delay times.
*   Click towards the top to apply an increasing number of tuning calculations. This may take a while depending on the available CPU power. The tuning will reduce the ringing effect that can occur when multiple delay lines are reinforcing each other.

#### Clipboard Buttons

*   [](#zreverb.copy)**Copy**: Copy settings to clipboard.
*   [](#zreverb.paste)**Paste**: Paste settings from clipboard.
*   [](#zreverb.swap)**Swap**: Swap settings with clipboard. This is useful for doing quick A/B comparison.

* * *

# <a name="toc.keyshortcuts"></a>Appendix A: Podium Key Shortcuts

**Key Shortcut** | **Description**
| --- | --- |
| | **Global**
Alt+P | Open Podium menu.
Alt+S | Open Setup menu.
Alt+W | Open Window menu.
F1 | Open/close help page.
Shift+F1 | Open and lock the help page for the element under the mouse cursor.
F2, F3, F4, F5, F6 | Open/close one of the five track inspector panels.
F7 | Open/close browser page.
F8 | Restore/minimize mixer/embedded region (arrangement editor).
F9, F10, F11, F12 | Switch between the four screens.
Ctrl+Tab, Ctrl+Shift+Tab | Rotate key focus between all open windows.
Tab, Shift+Tab | Rotate key focus between listboxes/panels in the focus window.
Ctrl+O | Show file dialog to open a project.
Ctrl+S | Save project.
Ctrl+Shift+S | Save sound when focus is in sound editor.
Ctrl+Shift+Alt+S | Save all changes to project and sound files.
Menu | Open context menu for current selection.
| | **Listbox**
Up/Down | Move focus in the list.
PgUp/PgDown | Move focus up/down an entire page.
Home/End | Move focus to first/last object in the list.
Left | Collapse folder if object is expanded or else navigate to parent object.
Right | Expand folder if object is collapsed or else navigate to first child object.
Plus/Minus | Expand/collapse folder object.
Enter | Activate focus object. Action depends on context of list box.
Alt+Enter | Open properties dialog for focus object.
Alt+N | Open stickie note for focus object.
| | **Multiple selection listbox**
Ctrl+[Move] | Move focus without changing anchor position or object selection state.
Shift+[Move] | Move focus and select range from anchor to focus and deselect others.
Ctrl+Shift+[Move] | Move focus and extend select range from anchor to focus.
Space | Select focus object.
Ctrl+Space | Toggle select focus object and set anchor.
Shift+Space | Select range from anchor to focus and deselect others.
Ctrl+Shift+Space | Select focus object and deselect others.
| | **Object browser**
Shift+Enter | Enter focus object as list root.
Shift+Backspace | Go up one level.
Ctrl+A | Select all objects in the list.
Ctrl+X | Cut selected objects to clipboard.
Ctrl+C | Copy selected objects to clipboard.
Ctrl+V | Paste clipboard objects into the list.
Delete | Delete selected objects.
| | **File browser**
Shift+Enter | Enter subfolder as list root if focus is on a folder.
Shift+Backspace | Go up one level.
Enter | Start audition if focus is on a sound file.
Escape | Stop audition.
| | **Project page**
Alt+C | Open Content menu.
Alt+D | Open Device menu.
Enter | Enter editor page for focus object.
Ctrl+Enter | Open editor window for focus object.
Backspace | Move to parent page.
Ctrl+I | Import media file.
| | **Editors**
Alt+F | Open File menu.
Alt+T | Open Tracks menu (arrangement editor).
Alt+E | Open Edit menu.
Alt+V | Open View menu.
1/2/3..8/9/0 | Switch between the first ten editor profiles in the view menu.
Ctrl+Z | Undo previous edit action.
Ctrl+Y | Redo previously undone edit action.
Alt+Z | Open the undo history menu.
Alt+Y | Open the redo history menu.
D/F | Step between edit tools.
Shift+D/F | Step between grid values.
A | Toggle snap mode.
Alt+G | Open Grid and Snap menu.
Ctrl+A | Select all.
Alt+A | Select all from edit cursor.
Ctrl+R | Reset current selection.
Ctrl+X | Cut selection to clipboard.
Ctrl+C | Copy selection to clipboard.
Ctrl+V | Insert clipboard contents at segment selection start or at edit cursor.
Delete | Delete current selection.
Alt+M | Create new marker at cursor position (arrangement and sound editor).
| | **Mouse modifiers**
Shift+Alt | Activate the slide tool.
Ctrl+Shift | Activate the zoom-Y tool. Click+drag or use wheel to zoom.
Ctrl+Alt | Activate the zoom-X tool. Click+drag or use wheel to zoom.
Ctrl+Shift+Alt | Activate the zoom-X/Y tool. Click+drag or use wheel to zoom.
Shift | Click to drag a marquee selection. Works even if clicked on events.
Ctrl | Click an empty timeline area to drag a marquee selection adding to existing selection.
Ctrl | Click events to toggle selection.
Ctrl | Click events and drag to create copies. Press Ctrl repeatedly to toggle between phantom and unique copies in arrangement editor.
Shift | Press and hold when dragging to disable snapping.
Alt | Press and hold when dragging events to lock horizontal or vertical position.
| | **Slide & Zoom**
Shift+Alt+ArrowKeys | Slide.
Shift+Home/End | Slide to the top/bottom.
Alt+Home/End | Slide to the start/end.
Home | Center the timeline on the current selection.
End | Center vertically on the current selection.
Ctrl+Shift+Alt+ArrowKeys | Zoom in/out.
Ctrl+Shift+End | Set vertical zoom to default.
Ctrl+Home | Set timeline zoom to full range.
Ctrl+End | Set timeline zoom to the current selection.
| | **Edit cursor, segment, punch and loop ranges**
Q/W, Num4/6 | Move edit cursor to previous/next grid line.
Shift+Q/W, Num7/9 | Move edit cursor to previous/next marker, loop, punch or segment range.
Ctrl+Q/W, Num1/3 | Move edit cursor to start/end of current selection.
Ctrl+E | Toggle "link edit cursor to play cursor" option.
J | Toggle segment selection.
Shift+J | Set nearest segment start or end position to edit cursor position.
Alt+J | Set segment range to markers surrounding the edit cursor.
Shift+K | Set nearest punch in or punch out position to edit cursor position.
Alt+K | Set punch in/out range to markers surrounding the edit cursor.
Shift+I | Set punch in position to edit cursor position.
Alt+I | Set punch in position to the marker left of the edit cursor.
Shift+O | Set punch out position to edit cursor position.
Alt+O | Set punch out position to the marker right of the edit cursor.
Shift+L | Set nearest loop start or end position to edit cursor position.
Alt+L | Set loop range to markers surrounding the edit cursor.
| | **Transport**
Ctrl+Shift+Alt+Space | Toggle arrangement power on/off.
Num0 | Stop playback.
NumEnter | Start playback.
Space | Start/stop playback.
L | Toggle loop mode.
K, NumDecimal | Toggle record mode.
U | Toggle metronome mode.
I | Toggle punch in mode.
O | Toggle punch out mode.
| | **Arrangement editor**
Shift+1/2/3..8/9/0 | Select zoom snapshot.
S/M/R | Toggle Solo, Mute and Record Arm mode on the track.
Shift+S/M/R | Toggle mode on the track and clear mode on all other tracks.
Shift+Alt+S | Toggle automatic solo mode.
B | Toggle bounce playback. Render track when offline bounce mode is selected.
Alt+B | Render track only within the punch range in offline mode.
Ctrl+B | Toggle playback without rendering in offline mode. Toggle bounce record arming in realtime mode
X | Toggle bypass mode of device mapping on the track.
E | Toggle plugin editor window on the track.
G | Toggle collapse state of group track.
Ctrl+G | Toggle hiding of tracks within group track.
H | Toggle between minimized and normal height of track.
Plus/Minus | Expand/collapse group track.
Ctrl+M | Mute/unmute selected events.
Ctrl+N | Bundle/unbundle selected events.
Ctrl+T | Split selected events at edit cursor position.
Ctrl+U | Convert selected phantom sequence/sound events to unique copies.
Ctrl+Shift+V | Replace effect chain of current track with a chain copied from another track.
Alt+Enter | Open sequence, sound or track properties dialog for the currently selected event or track.
Shift+Enter | Open sound event properties dialog for the currently selected sound event.
| | **Arrangement tracks region**
Cursor keys | Move focus between tracks and events on tracks.
PgUp/PgDown | Move track focus to previous/next track on same group level.
Shift+PgUp/PgDown | Move track focus to first or last track.
Ctrl+PgUp/PgDown | Move track up or down within the parent group.
Ctrl+Left/Right | Offset time of selected events with the editor grid value.
Insert | Add duplicates of selected events, snapped to the next grid line.
Shift+Insert | Add duplicates of selected events, without snapping.
Ctrl+Insert | Add duplicates of selected events, snapped to the next bar.
| | **Arrangement mixer region**
Left/Right | Move track focus.
Up/Down | Move track focus to parent track or first child track.
Shift+Left/Right | Move track focus to previous/next track on same group level.
| | **Note editor**
Cursor keys | Navigate the note events.
Ctrl+Left/Right | Offset time of selected events with the editor grid value.
Ctrl+Up/Down | Transpose selected events.
Shift+Up/Down | Transpose selected events in octaves (piano roll mode).
Plus/Minus | Adjust attack velocity in steps of 1/16.
Ctrl+Plus/Minus | Adjust note durations with the editor grid value.
Insert | Add duplicates of selected events, snapped to the next grid line.
Shift+Insert | Add duplicates of selected events, without snapping.
Ctrl+Insert | Add duplicates of selected events, snapped to the next bar.
| | **Curve editor**
Left/Right | Navigate the curve events.
Ctrl+Left/Right | Offset time of selected events with the editor grid value.
Plus/Minus | Adjust value of selected events in steps of 1/32.
Ctrl+Plus/Minus | Adjust tangent length of single selected spline event.
Alt+Plus/Minus | Adjust tangent slope of single selected spline event.

* * *

# <a name="toc.texttranslations"></a>Appendix B: Text Translations

The purpose of this appendix is to provide translation of common Podium UI texts that do not belong to specific chapters in this guide.

#### Dialog Buttons:

*   [](#button.ok)**&OK**
*   [](#button.cancel)**&Cancel**
*   [](#button.apply)**&Apply**
*   [](#button.abort)**&Abort**
*   [](#button.yes)**&Yes**
*   [](#button.no)**&No**
*   [](#button.close)**&Close**
*   [](#button.help)**&Help**

#### Dialog Value Units:

*   [](#unit.decibel1)**dB** [](#unit.decibel2)**dB**
*   [](#unit.milliseconds1)**ms**
*   [](#unit.percentage1)**%**
*   [](#unit.pixels1)**pixels** [](#unit.pixels2)**pixels** [](#unit.pixels3)**pixels** [](#unit.pixels4)**pixels**

#### Option Texts:

These texts are surrounded by \<> (angle brackets) to distinguish them from the names of other option values.

*   [](#text.option.none)**\<None>**: Shown in combo boxes and other places where a specific value has not been selected.
*   [](#text.option.empty)**\<Empty>**
*   [](#text.option.noname)**\<No name>**
*   [](#text.option.notsaved)**\<Not saved>**

* * *

</div>