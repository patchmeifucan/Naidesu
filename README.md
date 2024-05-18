# Naidesu

Very basic Reverse Shell in Nim for UNIX-Like OSes such as Linux, *BSD, and macOS. This was just a test for me to wrap my head around how Nim works, but also because the overwhelming bulk of Nim Reverse Shells are Windows specific and the descriptions for switching the code to be executed on Linux were extremely lazy and had issues regarding pathing and receiving STDOUT of particular commands. You don't deserve that, so I took it upon myself to do it.

Usage is simple, compile with `nim c naidesu.nim` and view help options with `./naidesu --help` or `./naidesu -h`
`exit` exits the shell session then closes the socket, `naidesu` prints out a funny image of a cute rat if you're stressed out from struggling on a CTF and need to cool off

Don't use this for Blackhat campaigns, write your own code cybercriminal scum.
