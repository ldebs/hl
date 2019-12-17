# hl
A bash script to highlight standard output with color based on regular expression

## Options
Just launch the `hl` script with `--help` to see its options

## Example
A typical use is :

`tail -f /somewhere/myLogFile | hl R "ERR.*" Y "WARN.*" DG "DEBUG.*"`

## Install
Copy the `hl` script file into a bin directory accessible in your PATH and set its executable flag

Enjoy
