# morpho

Framework for SoC description, Config file generation and codegen 

## Main Objective

Create a tool capable of generating different config files based on a modular JSON platform description. Some of type of capabilities being considered are:

- Renode .repl generation
- zephyr SoC .dts generation
- SVD generation
- C header generation (per-peripheral basis)
- Rust PAC generation (per peripheral basis)
- Rust HAL skeleton generation 

## Possible features

- SVD traslate: Use a provided SVD to generate a `morpho` peripheral and platform description files. 
