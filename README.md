## Linux steps
1. Rename current User prefs folder under `~/.config/sublime-text-3/Packages` to something else to avoid clash when you clone.
2. Clone this repo into a new User folder: `git clone git@github.com:jonnyparris/sublime-prefs.git User`
3. Remove the old User folder after copying anything useful across that you might need (if it's not from a fresh Sublime install) - `diff -rq User User_old` is pretty handy here.
