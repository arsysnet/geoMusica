[RELEASED]

[geoMusicaLive branch publicRelease 1.201221]

ATTENTION!: this branch is currently being developed on the experimental TD 2020.44350

New features:
- Ableton Live 11 (beta) support, with Max for Live devices to handle communication, and a Live template for exploring
- Startup sequence now opens in correct order the different TD processes
- On this branch deprecated TDmorph for preseting (using Live session for that, will merge with master branch further ahead with both systems working)
- Deprecated GeoSynth (also only on this branch for obvious reasons)
- Tiles, Stars and Intersections section is now available (use the INTERSECT function with caution!)
- Mathematical and Geometrical UI elements for G. SCALE, ANGLE, STEP SCALE, ALT STEP, MOD MULT and OFFSET are now available
- Layer Link and trace options are now available (linked layers generate MIDI notes on MIDI channel 16)

Bugfixes:
- resizing window settings now correctly updates the trace function
- UI general fixes


[publicRelease 1.200903]

New features:
- now you can change the spinning direction on the preferences page of Engine, clockwise or counterclockwise
- added resize dimensions for windowed mode, on the settings of Render
- added support for diffent layout schemes on fullscreen mode, useful for ultrawide screens

[publicRelease 1.200901]

Bugfix:
- minor bugfixes

[publicRelease 1.200823]

Bugfix:
- removed Engine COMP from Synth, too much instabilities
- .bat file now correctly calls the start command (thank you bangnoise)

[publicRelease 1.200820]

New features:
- added support for Mac OS
- restyling of UI elements
- new ableton live template (still under development but can be used)


[publicRelease 1.200803]

Bugfix:
- trigger visualization in Render now layer based, reduces false triggers when changing presets
- bug on widget visualization from copy to buttons squashed
- TDMorph parameters on UI now get the correct layer number in the name


[privateBeta 1.200730]

Bugfix:
- TDMorph direct drag n drop from UI elements works again
- new copy SOP stamping to prevent bug in primitive SOP both on Engine and Render


[privateBeta 1.200729]

New features:
- windowed mode option in Render UI, makes Render and UI windows toggle to borders and fixed resolution of 1024x1024

Bugfix:
- on N LAYERS change, widgets could dissapear
- layer link on geoEngine inconsistency resolved

[privateBeta 1.200728]
- ultra optimization on Engine MIDI triggering script, now based on eventCHOP instead of TriggerCHOP (Thanks Wieland!)

[privateBeta 1.200726]
- Render camera now adapts to different resolutions
- replaced global variables for resolution in Render and UI with dynamic primary monitor detection
- added options in setup for defining ASIO setup (Synth)

[privateBeta 1.200724]
- artwork on Synth and Engine
- option to turn off engineCOMP on Synth
- full readme on about sections

[privateBeta 1.200723]

- TD 2020.25380 base upgrade
- Synth got engineCOMP functionality on the Voice COMP

New features:
- added buttons to bring forward the Engine and the Synth windows
- added button for link to help development
- reshaping of the Engine perform window


[privateBeta 1.200721]

New features:
- added auto versioning system
- render and resolution responsiveness on Render and UI


[privateBeta 1.200718]

New features:

- added quit button on bottom right of Render, quits all geoMusica processes simultaneosly
- removed TD splashscreen (testing)
- added XPRT / BASIC button on top right UI, to toggle between what will be the two versions of future official release, one for Derivative Comunnity, another for the Patreon support page.
- added 12TET Tuning setting to Synth, to choose the tuning standard of equal temperament limitation to frequencies


