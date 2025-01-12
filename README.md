# bpif3_gen_binary

Tool to generate the `bootinfo` and `FSBL` binaries for the [Banana Pi BPI-F3](https://docs.banana-pi.org/en/BPI-F3/BananaPi_BPI-F3)
(and other `SpacemiT K1` based boards).

`bpif3_gen_binary` was extracted from [u-boot](https://gitee.com/bianbu-linux/uboot-2022.10) in the official `SpacemiT`
`BSP` for the `K1` chip ([Bianbu Linux](https://gitee.com/bianbu-linux)).
From the vendor `u-boot` the script files
[build_binary_file.py](https://gitee.com/bianbu-linux/uboot-2022.10/blob/bl-v2.0.y/tools/build_binary_file.py) and
[common_decorator.py](https://gitee.com/bianbu-linux/uboot-2022.10/blob/bl-v2.0.y/tools/common_decorator.py) have been
taken over and merged into a single file.
The config files have been taken over from the board / SoC specific
[config](https://gitee.com/bianbu-linux/uboot-2022.10/tree/bl-v2.0.y/board/spacemit/k1-x/configs) folder.

Usage:
```
bpif3_gen_binary -c <config file> -o <output file>
``` 
