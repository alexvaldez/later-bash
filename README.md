# later

This is a simple command-line todo app inspired by http://todomvc.com/

## Background

I set out to do this when a guy I knew posted on Twitter how to get a command line todo app
on an ARM Linux box and found themselves shaving yaks - trying to get a Haskell compiler to run
and installing NixOS, etc.

I decided to rewrite the app using bash, which I figured would be much more portable, particularly
if I avoid any external utilities not commonly found on a normal Linux install. It took me one weekend
to re-sharpen my bash skills and produce this. The exercise was so much fun that I think I'll use
this little exercise to enable me to (re)learn other languages. Right now, I'm planning on the following
(in no particular order): Ruby, go, TypeScript, Clojure, Ocaml and C# (and probably Java just because.)

## TODO

- Sync with a repo (git and whatever else strikes my fancy)
- Use tput to display todo's as per the markdown markup. (The file it produces is already a .md file.)
- Add a config file to customise and set default preferences.
