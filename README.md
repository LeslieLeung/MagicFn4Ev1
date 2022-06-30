# MagicFn4Ev1
AutoHotKey & Karabiner script that utilize your (probably) useless CapsLock as Magic Fn, available for pretty much every keyborard.

## Feature
- Use CapsLock as a Magic Fn that combines with other keys to act as some keys that don't exist on a 60/68 keyboard.
  - `CapsLock` + `wasd` -> `Arrow keys`
  - `CapsLock` + `1234567890-=` -> `F1-F12`
  - `CapsLock` + `[` -> `Home`
  - `CapsLock` + `]` -> `End`
  - `CapsLock` + `;` -> `PgUp` (only AHK)
  - `CapsLock` + `'` -> `PgDn` (only AHK)
  - `CapsLock` + `esc` -> `` ` ``
- May your wrists rest in peace (x

## Why this exists?
> Update:
> 
> I recently switched to macOS and AHK doesn't work on macOS, so I used Karabiner to replace AHK.

I daily drived a Anne Pro 2 60% keyboard for almost 3 years, and its Magic Fn feature really is a great convenient for a programmer so lazy like me to type without moving my wrists even a bit (so they can rest comfortably on the wrist rest). It was a hardware implemented feature on Anne Pro 2 and unfortunately my new keyboard don't have this magic. Did a little research and I come up with this ahk script that saved the world (at least mine).

I believe the charm of a 60% keyboard is that every necessary key is accessable without the need to move your resting wrists. Some 60% keyboard don't have arrow keys (like Anne Pro 2) at all, therefore the Magic Fn thingy is really handy. Also, if you are a programmer, you would understand that from time to time you have to select auto-complete options promted by your "INTELLEGENT" IDE, which would be quite interrupting and low efficient if you have to lift your right hand to get to the arrow keys. With Magic Fn, arrow keys would be wasd, which is consistent to most game mappings, and you can spare your right little finger to click Enter. It works the same for Home, End and some other common used keys.

I'd say whoever designed this machanism is a really genius, and not every keyboard manufacturer is brilliant. Therefore I replicated the Anne Pro 2 key mapping in this script, making my new keyboard identical to the still using Anne Pro 2 without having to accustom to a new mapping.

## How to use
### AHK Script(Windows)
- Download and install [AutoHotKey](https://www.autohotkey.com/)
- Download the `MagicFn4Ev1.ahk` from the repo
- (Optional) Tune the script to whatever mapping you keen to (delete, edit or add new lines between the `#if` lines)
- Double click on the downloaded `MagicFn4Ev1.ahk` file
- Enjoy your Magic Fn :)

### Karabiner(macOS)
- Download and install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
- Click [HERE](https://genesy.github.io/karabiner-complex-rules-generator/#eyJ0aXRsZSI6Ik1hZ2ljRm40RXYxIiwicnVsZXMiOlt7ImRlc2NyaXB0aW9uIjoiQ2FwcyBmb3IgTWFnaWNGbiAobXVzdCBlbmFibGUsIG90aGVyd2lzZSBub25lIG9mIGJlbG93IHdvcmtzKSIsIm1hbmlwdWxhdG9ycyI6W3sidHlwZSI6ImJhc2ljIiwiZnJvbSI6eyJrZXlfY29kZSI6ImNhcHNfbG9jayIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sic2V0X3ZhcmlhYmxlIjp7Im5hbWUiOiJjYXBzX2xvY2sgcHJlc3NlZCIsInZhbHVlIjoxfX1dLCJ0b19hZnRlcl9rZXlfdXAiOlt7InNldF92YXJpYWJsZSI6eyJuYW1lIjoiY2Fwc19sb2NrIHByZXNzZWQiLCJ2YWx1ZSI6MH19XX1dfSx7ImRlc2NyaXB0aW9uIjoiQ2FwcyArIFdBU0QgZm9yIGFycm93cyIsIm1hbmlwdWxhdG9ycyI6W3sidHlwZSI6ImJhc2ljIiwiZnJvbSI6eyJrZXlfY29kZSI6InMiLCJtb2RpZmllcnMiOnsib3B0aW9uYWwiOlsiYW55Il19fSwidG8iOlt7ImtleV9jb2RlIjoiZG93bl9hcnJvdyJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoidyIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJ1cF9hcnJvdyJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiYSIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJsZWZ0X2Fycm93In1dLCJjb25kaXRpb25zIjpbeyJ0eXBlIjoidmFyaWFibGVfaWYiLCJuYW1lIjoiY2Fwc19sb2NrIHByZXNzZWQiLCJ2YWx1ZSI6MX1dfSx7InR5cGUiOiJiYXNpYyIsImZyb20iOnsia2V5X2NvZGUiOiJkIiwibW9kaWZpZXJzIjp7Im9wdGlvbmFsIjpbImFueSJdfX0sInRvIjpbeyJrZXlfY29kZSI6InJpZ2h0X2Fycm93In1dLCJjb25kaXRpb25zIjpbeyJ0eXBlIjoidmFyaWFibGVfaWYiLCJuYW1lIjoiY2Fwc19sb2NrIHByZXNzZWQiLCJ2YWx1ZSI6MX1dfV19LHsiZGVzY3JpcHRpb24iOiJDYXBzICsgW10gZm9yIEhPTUUgYW5kIEVORCIsIm1hbmlwdWxhdG9ycyI6W3sidHlwZSI6ImJhc2ljIiwiZnJvbSI6eyJrZXlfY29kZSI6Im9wZW5fYnJhY2tldCIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJob21lIn1dLCJjb25kaXRpb25zIjpbeyJ0eXBlIjoidmFyaWFibGVfaWYiLCJuYW1lIjoiY2Fwc19sb2NrIHByZXNzZWQiLCJ2YWx1ZSI6MX1dfSx7InR5cGUiOiJiYXNpYyIsImZyb20iOnsia2V5X2NvZGUiOiJjbG9zZV9icmFja2V0IiwibW9kaWZpZXJzIjp7Im9wdGlvbmFsIjpbImFueSJdfX0sInRvIjpbeyJrZXlfY29kZSI6ImVuZCJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX1dfSx7ImRlc2NyaXB0aW9uIjoiQ2FwcyArIG51bSBmb3IgZiBLZXlzIiwibWFuaXB1bGF0b3JzIjpbeyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiMSIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmMSJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiMiIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmMiJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiMyIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmMyJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiNCIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmNCJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiNSIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmNSJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiNiIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmNiJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiNyIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmNyJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiOCIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmOCJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiOSIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmOSJ9XSwiY29uZGl0aW9ucyI6W3sidHlwZSI6InZhcmlhYmxlX2lmIiwibmFtZSI6ImNhcHNfbG9jayBwcmVzc2VkIiwidmFsdWUiOjF9XX0seyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiMCIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmMTAifV0sImNvbmRpdGlvbnMiOlt7InR5cGUiOiJ2YXJpYWJsZV9pZiIsIm5hbWUiOiJjYXBzX2xvY2sgcHJlc3NlZCIsInZhbHVlIjoxfV19LHsidHlwZSI6ImJhc2ljIiwiZnJvbSI6eyJrZXlfY29kZSI6Imh5dGhlbiIsIm1vZGlmaWVycyI6eyJvcHRpb25hbCI6WyJhbnkiXX19LCJ0byI6W3sia2V5X2NvZGUiOiJmMTEifV0sImNvbmRpdGlvbnMiOlt7InR5cGUiOiJ2YXJpYWJsZV9pZiIsIm5hbWUiOiJjYXBzX2xvY2sgcHJlc3NlZCIsInZhbHVlIjoxfV19LHsidHlwZSI6ImJhc2ljIiwiZnJvbSI6eyJrZXlfY29kZSI6ImVxdWFsX3NpZ24iLCJtb2RpZmllcnMiOnsib3B0aW9uYWwiOlsiYW55Il19fSwidG8iOlt7ImtleV9jb2RlIjoiZjEyIn1dLCJjb25kaXRpb25zIjpbeyJ0eXBlIjoidmFyaWFibGVfaWYiLCJuYW1lIjoiY2Fwc19sb2NrIHByZXNzZWQiLCJ2YWx1ZSI6MX1dfV19LHsiZGVzY3JpcHRpb24iOiJDYXBzICsgZXNjIGZvciBgIiwibWFuaXB1bGF0b3JzIjpbeyJ0eXBlIjoiYmFzaWMiLCJmcm9tIjp7ImtleV9jb2RlIjoiZXNjYXBlIiwibW9kaWZpZXJzIjp7Im9wdGlvbmFsIjpbImFueSJdfX0sInRvIjpbeyJrZXlfY29kZSI6ImdyYXZlX2FjY2VudF9hbmRfdGlsZGUifV0sImNvbmRpdGlvbnMiOlt7InR5cGUiOiJ2YXJpYWJsZV9pZiIsIm5hbWUiOiJjYXBzX2xvY2sgcHJlc3NlZCIsInZhbHVlIjoxfV19XX0seyJkZXNjcmlwdGlvbiI6IkxlZnQgU2hpZnQgZm9yIHN3aXRjaCBpbnB1dCBtZXRob2RzIiwibWFuaXB1bGF0b3JzIjpbeyJmcm9tIjp7ImtleV9jb2RlIjoibGVmdF9zaGlmdCJ9LCJ0byI6W3sia2V5X2NvZGUiOiJsZWZ0X3NoaWZ0IiwibGF6eSI6dHJ1ZX1dLCJ0b19pZl9hbG9uZSI6W3sia2V5X2NvZGUiOiJzcGFjZWJhciIsIm1vZGlmaWVycyI6WyJsZWZ0X2NvbnRyb2wiXX1dLCJ0eXBlIjoiYmFzaWMifV19XX0=) to view the script, and click on [INSTALL!] to install this script.
- Go to [Preferences] - [Complex modifications] - [Rules] - [Add rule], click on [Enable all] for entry MagicFn4Ev1 or select the rules that you wish for on your demand.
- Enjoy your Magic Fn :)
