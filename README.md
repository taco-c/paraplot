# paraplot
Adaptive parallel plotting wrapper for chia.

This is a tool for creating Chia plots in parallel, with a dynamic delay.

It monitors the plotting process and begins a new plot after phase 1 (can be configured).

## Dependencies
+ `inotifywait`

## Configuration
Copy `paraplotrc.example` to `~/.config/paraplotrc`. Then edit it as you like.
Make sure the file is executable.

## Usage
```
./paraplot <number of plots>
```

