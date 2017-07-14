# i3BlocksTimer
simple notification timer for i3Blocks

## setup
put the timer file to i3BlocksScripts directory.
make it executable
add [timer] to your i3blocks.conf:
`
[timer]
label=&#xf017;
interval=10
signal=10
`
restart i3

## how to use
left button click - set minutes count
right button click - set human readable date string (see DATE STRING from 'man date')
middle button click - reset timer
