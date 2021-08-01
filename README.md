# paraplot

Adaptive parallel plotting wrapper for chia.

Monitors the process of the plotting, and starts a new plot when phase This way you don't need to use a timed delay for creating plots. Phase 1 is the most CPU intensive phase of making plots, therefore it optimizes stuff.

## Dependencies

+ `inotifywait`

## MONitor PHase N

Prints line when written to specific file.

Using `inotifywait`, listens to a file for changes. At file change uses `grep` to find a matching line, then prints it.

