# tcc-test

## CPU Specs:

|Processor Number | i5-5257U |
|---|---|
| Cores  | 2 |
| Threads  | 4 |
| Base Frequency | 2.70GHz |
| Turbo Frequency | 3.10GHz  |
| Cache | 3Mb  |
| TDP  | 28W  |
| Bus Speed | 5 GT/s  |

## Table of Inference Time (Avg of 5 times)

| Condition  | Inference (seconds) |
|---|---|
| TF Thread=1  | 0.987266 |
| TF Thread=2  | 0.983502  |
| TF Thread=3  | 0.975702  |
| TF Thread=4  | 0.98477  |
| TCC OpenMp | 4.5208 |
| TCC OpenMp -O2 | 0.371 |
| WebAssembly Old Chrome | 5.0366  |
| WebAssembly New Chrome | 34.0354  |
| WebAssembly New None Opt Chrome | 5.1726  |
| WebAssembly Old Safari | 32.77124  |
| WebAssembly New Safari | 32.8444  |
| WebAssembly New None Opt Safari | 32.76 |

## Capabilty of other architecture
### Web Assembly 
[Install WebAssembly Environment](https://webassembly.org/getting-started/developers-guide/)
### ARM 
[Archc Retargetable Simulator](http://www.archc.org/)

[SystemC Dependency](https://www.accellera.org/downloads/standards/systemc)

[Configured Arm Cross-compiler](http://www.archc.org/downloads.html)

### RISCV 
[GNU tool-install Newlib](https://github.com/riscv/riscv-gnu-toolchain)

[Spike Simulator](https://github.com/riscv/riscv-isa-sim)

[Riscv pk](https://github.com/riscv/riscv-pk)

