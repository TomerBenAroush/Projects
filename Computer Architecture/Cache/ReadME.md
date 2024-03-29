Cache Simulator in C++

This project implements a custom cache memory simulator.

The cache memory configuration will be flexible and defined at runtime using parameters. 

Additionally, the simulator will read an input file detailing memory accesses.

The simulator will calculate the Miss/Hit rate and the average access time to memory 
for the specified configuration and for the input trace file.

Features customizable through parameters for initialization:
- Cache memory size (in byte resolution)
- Block size (in byte resolution)
- Associativity level
- Access times (in clock cycles)
- Write Allocate policy: No Write Allocate or Write Allocate
