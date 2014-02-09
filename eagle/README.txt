max21100_v1 - Initial version, tested and working.
max21100_v2 - untested
    Add I2C jumper (tying CS high) to select I2C mode.
    Add SAO jumper to select address for I2C.
    V2 label
    Increase label sizes and reposition
    Move dsync, int1 and int2 headers pins to simplify board.
    Rename labels to reflect default I2C usage, SCK->SCL, SDO->SA0, SDI->CS
    Remove central via and label under chip.
    Improve via positions and straighten traces from chip.
max21100_v3 - untested
    Shortened pin labels.
    Moved MDA, MCL, SCL, SDA, CS and SA0 headers to simplify layout.
    Moved jumpers and removed default for I2C and SA0 jumpers.
    Renumbered capactitors.
    Swapped positions of R1 and R2.
    Added pin 1 marker.
