tmux-tut
========


source https://www.youtube.com/watch?v=wKEGA8oEWXw

is a Terminal Multiplexer

install

    $sudo apt-get install tmux

start

    $tmux

exit

   $exit

how it works
-------------
tmux start a client and a server, terminal sends to client, client to server and server to shell

this allows to close the terminal window and pick from where i left  it, ex

start vim

    $vim documnet

exit terminal

repoen terminal, and continue work on vim

    $tmux attach

keys
---------

default PREFIX is ctrl+b, press prefix and then command,, ex to detach from sessio

    ctrl+b, d(etach)
    
from now on ctrl+b = PREFIX

get help

    PREFIX, ?

has alot of keybindings

keys
-------

to create new window

    PREFIX, c(reate)

to go to next window

    PREFIX, n(ext)

go to previous window, yes you guessed it 

    PREFIX, p(revious)

go to #windows

    PREFIX [0-9] = go to window number


