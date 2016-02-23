# musicalTyping
Have you ever wished that your keyboard made music when you typed?

When completed, this Mac OSX app should produce random beep-boop sounds when any key is pressed on the keyboard.

I have some ideas for future features, but that is the core idea.

It should be pretty straightforward, but the technical unknown is how easy it will be to find and use a library that will allow me to capture key presses regardless of which app is in focus.

I have done a minor bit of research and it looks like it might be very easy, but you never know until you try.

### Possible features:

- different (selectable) sound themes
- a way of handling keyboard mashes, so that it doesn't sound too terrible trying to play 80 sound files at once... Something like, if there are more than 7 keypresses in .2 seconds it could play a pre-determined (chaotic but pleasing) sound.
- effects (audioUnit effects like reverb)
- a theme that uses synthesis (monophonic-synth) and raises the pitch of the sound with each keypress, so that fast typing would cause the pitch to rise and slow typing would produce low-pitched sounds.
