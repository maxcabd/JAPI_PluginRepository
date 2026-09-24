# Extra Stage Slots 1.0.0

Adds XML-configured stage slots, including independent stages, custom titles and descriptions.

- Put `ExtraStageSlots.dll` in `japi/plugins/`. Remove the old `ASBRExtraStages.dll` if present; keep only one stage-slots plugin.
- Put the compiled `extraStageSelectParam.bin.xfbin` in `data_win32/ui/btlsel/ssel/` for a loose install, or `data/ui/btlsel/ssel/` inside a mod CPK.
- The starter configuration is empty. Keep your existing working configuration; merge slot rows when combining stage mods. XML is the editable source; the game reads XFBIN.
- `examples/stock-duplicate` adds a stock `6knd` slot for testing. Custom stages require separate stage assets and StageInfo definitions.

Requires JAPI and the supported ASBR 2.33 executable. CPKModLoader is needed only for CPK installation. Developer file logging is disabled. Source code is not currently published.
