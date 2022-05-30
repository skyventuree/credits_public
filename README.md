# notes for macOS with M1 chips:
you can install `just-playback`, just make sure that you have `cffi` installed as x86_64 (by install `cffi` in Terminal with Rosetta 2 or with `arch -x86_64`) beforehand.

This fork will be alive for people who still can't install `just-playback`. Please support @plaaosert!

# credits_public
- Forked version of Frums - Credits animation repository.
- Trimmed all `just-playback` related function. **Require manual song syncing. You should only use this if you can't install `just-playback`.**
- Totally multiplatform.
- Tested on clean Python 3.10 (macOS) with minimal modules installed.

# media credits
- All animation work done by @plaaosert. I just removed all the `just-playback` related function.
- Song credit: Frums - Credits EX https://soundcloud.com/frums/credits-ex

# how to run
Run credits.py. Required libraries:
  - ~~just-playback https://github.com/cheofusi/just_playback~~
  - keyboard https://github.com/boppreh/keyboard
  - colorama https://github.com/tartley/colorama - the version of colorama used is also included inside this repository.