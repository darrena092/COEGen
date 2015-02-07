# COEGen
Converts binary files to .coe files for initializing Xilinx FPGA block RAM.

## Usage
``` $ COEGen --file [filename] --width [block width in bits] --depth [memory depth in blocks] ```

For example:

``` $ COEGen --file binary.bin --width 8 --depth 256 ```

This will create a .coe file containing binary.bin. The memory will be 8-bits per block with 256 blocks, meaning 256 bytes. The output filename in this example would be "binary.bin.coe".

## Compiling
I would recommend using Code::Blocks to compile. Just load the project and build it. You must have the boost libraries installed and compile against them for it to be successful.

## More information
More information is available at http://wornwinter.wordpress.com/


