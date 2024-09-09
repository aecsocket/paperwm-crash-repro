PaperWM cursor locking crash reproduction case

# Instructions

- `cargo run`
- The window will lock your cursor so you can't move it
- Try alt-tabbing, Win+L/R, etc. Free your cursor, move it to some other apps,
  try doing some stuff.
- Tab back into the window then Alt+F4
- Your cursor should remain frozen, and if you try to move it, gnome-shell crashes
