# MagicFn4Ev1
AutoHotKey & Karabiner script that utilize your (probably) useless CapsLock as Magic Fn, available for pretty much every keyborard.

## Feature
- Use CapsLock as a Magic Fn that combines with other keys to act as some keys that don't exist on a 60/68 keyboard.
  - `CapsLock` + `wasd` -> `Arrow keys`
  - `CapsLock` + `1234567890-=` -> `F1-F12` (only AHK)
  - `CapsLock` + `[` -> `Home`
  - `CapsLock` + `]` -> `End`
  - `CapsLock` + `;` -> `PgUp` (only AHK)
  - `CapsLock` + `'` -> `PgDn` (only AHK)
  - `CapsLock` + `esc` -> `` ` `` (only AHK)
- May your wrists rest in peace (x

## Why this exists?
> Update
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
- Click [HERE](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/MagicFn4Ev1/MagicFn4Ev1/master/MagicFn4Ev1.json) to import the script
- Go to [Preferences] - [Complex modifications] - [Rules] - [Add rule], click on [Enable all] for entry MagicFn4Ev1 or select the rules that you wish for on your demand.
- Enjoy your Magic Fn :)
