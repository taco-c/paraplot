#TODO

## Before release/publication
- [x] remove personal details from code
  - [x] remove from paraplot.sh
- [ ] git init

## General
- [x] feat: custom notifications
  - [x] custom command (ex. notify\_dc)
  - [ ] custom events types (plot-start, plot-finish, phase-n)
- [x] feat: prompt before starting plotting
  - [x] show settings used for this session
  - [ ] **-y** auto yes
- [x] feat: pause time after phase N is done 
- [ ] feat: support for MAX\_CONCURRENT
- [ ] feat: getopts to take precedence over config file
  - [ ] **-r** THREADS
  - [ ] **-k** K\_SIZE
  - [ ] **-t** TEMP\_DIR 
  - [ ] **-d** DEST\_DIR
  - [ ] **-c** POOL\_ADDR
  - [ ] **-f** CONFIG\_FILE
- [x] feat: support for arbitrary parameter insertion to `chia`
  - [x] CHIA\_PARAMS in config file
- [ ] feat: man page

