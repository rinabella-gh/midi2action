## midi2action

An adaptation of other user's scripts to allow using my MIDI pad as a keyboard for managing stream layouts. My adjustments are VERY rough, it is just for ensuring the bare basics of what I need. At some point I plan on making this a more robust application but for now this will do.

### Running 

After making sure it's executable.

> ./midi2action

Allowed arguments:

> ./midi2action -l 

list all detected devices

> ./midi2action -t (yourMidiDevice) 

test that alsa is seeing keystrokes. 

> ./midi2action (yourMidiDevice)

## Acknowledgements

This is forked from [AV-MidiMacros](https://github.com/Avante-Vangard/AV-MidiMacros). While it does not explicitly state a license, the author used wording to commit to public domain, and is itself an adaptation from [this stackoverflow](https://superuser.com/questions/1170136/translating-midi-input-into-computer-keystrokes-on-linux). I have removed the bulk of the (impressive) work that was done to have an interface via LibreOffice spreadsheets to pare down only to what I need at this time.
