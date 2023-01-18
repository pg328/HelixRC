# HelixRC
theme = 'dark_plus'

[editor]
line-number = 'relative'
mouse = false
rulers = [80]
shell = ['zsh', '-c'] 
scrolloff = 2
cursorline = true

[keys.normal]
";" = [ "collapse_selection", "keep_primary_selection"]
[keys.insert]
";" = [":w","normal_mode" ]

[editor.cursor-shape]
insert = "bar"

[editor.file-picker]
hidden = false
