# sublime-text-setup

My personal sublime text setup.

## Plugins

In order of awesomeness:

* JavaScript Refactor
* Origami
* SideBarEnhancements
* SublimeLinter
* SublimeLinter-annotations
* GotoWindow
* Pretty JSON
* ColorPicker
* Zen Tabs
* GitGutter

## Themes

* Spacegray
* One Dark Color Scheme
* Predawn

## Key Bindings

	[
	    { "keys": ["super+shift+d"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Delete Line.sublime-macro"} },
	    { "keys": ["super+d"], "command": "duplicate_line" },
	    { "keys": ["ctrl+shift+d"], "command": "find_under_expand" },
	    { "keys": ["alt+up"], "command": "swap_line_up" },
	    { "keys": ["alt+down"], "command": "swap_line_down" },
	    { "keys": ["super+l"], "command": "show_overlay", "args": {"overlay": "goto", "text": ":"} },
	    { "keys": ["super+alt+r"], "command": "find_all_under" },
	    { "keys": ["super+\\"], "command": "toggle_side_bar" },
	    { "keys": ["super+ctrl+s"], "command": "save_all" },
	    { "keys": ["ctrl+d"], "command": "find_under_expand" },
	    { "keys": ["ctrl+shift+d"], "command": "find_under_expand_skip" },
	    { "keys": ["super+shift+m"], "command": "expand_selection", "args": {"to": "brackets"} },
	    { "keys": ["super+enter"], "command": "replace_all", "args": {"close_panel": true}, "context": [{"key": "panel", "operand": "replace"}, {"key": "panel_has_focus"}] },
	    { "keys": ["alt+minus"], "command": "jump_back" },
	    { "keys": ["alt+shift+minus"], "command": "jump_forward" }
	]
	
