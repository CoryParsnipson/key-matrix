# key-matrix

Arduino code for polling buttons in a matrix format.

NOTE: this code is pretty much taken verbatim from [1] but with one big change. Since one of the switches is actually a MOSFET, we need to write the value of the row pins to be LOW after we poll it or the MOSFET will still be on when we disconnect the row pin.

# References

[1] https://www.baldengineer.com/arduino-keyboard-matrix-tutorial.html

