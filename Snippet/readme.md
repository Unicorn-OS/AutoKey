# Copy/Paste from Clipboard
https://askubuntu.com/questions/1214819/auto-pasting-into-gui-text-editor-box

Copy
'''field = clipboard.get_selection()
field = field.lower()
clipboard.fill_selection(field)
keyboard.send_keys("<ctrl>+c")'''

Paste
'''field = clipboard.get_selection()
field = field.lower()
clipboard.fill_selection(field)
keyboard.send_keys("<ctrl>+v")'''
