# Alacritty for Windows (Patched)

This is an automated patched build of [https://github.com/alacritty/alacritty](Alacritty) for Windows

There's an open [https://github.com/alacritty/alacritty/issues/2324](issue) that when pasting text you either end up with blank or missing newlines.

The developers aren't interested in manipulating the pasted text (which I get) but I need this in order for the terminal to function properly. 

This repo is an automated builder that, when a new version is pushed to the upstream repo it will automatically patch and release a windows build with the same version. 

Many thanks to the Alacritty devs for a cool/fast/functional terminal.