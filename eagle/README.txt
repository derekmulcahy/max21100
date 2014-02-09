max21100_v1 - Initial version, tested and working.
max21100_v2 - Improved version
    Add normally high I2C jumper (tying CS high) to select I2C mode.
    Add normally low SAO jumper to select 0 address for I2C.
    V2 label
    Increase label sizes and reposition
    Move dsync, int1 and int2 headers pins to simplify board.
    Rename labels to reflect default I2C usage, SCK->SCL, SDO->SA0, SDI->CS
    Remove central via and label under chip.
    Improve via positions and straighten traces from chip.
