openLRSngTX is an improved version of 1W OpenLRS TX module. It is designed as to fit JR module.

Main differences to normal openLRS are
- PPM input wired to ICP pin to be able to use timer for PPM sampling
- buzzer moved on timer pin to be able to use a piezo speaker for multiple tones
- serial port wired to 'module connector' for telemetry on er9x/open9x
- few I/O pins available for extra switches

External 3v3-5v power brick is needed

A test sketch to verify the board can be found here https://github.com/kh4/openLRSngTX_tester
