# RAM Tester using IC 8085 and 8255

This project implements a RAM tester using Intel 8085 microprocessor and Intel 8255 Programmable Peripheral Interface (PPI). The RAM tester is designed to test the functionality and reliability of RAM chips.

## Overview

The RAM tester operates by writing specific bit patterns to different memory locations in the RAM and then reading them back to verify correctness. The testing process is controlled by the 8085 microprocessor, and the address and data lines are interfaced with the RAM using the 8255 PPI.

## Features

- Writes various bit patterns to RAM for testing.
- Reads back data from RAM and compares with expected values.
- Provides detailed testing logs including pass/fail status and error messages.
- Supports testing of different RAM sizes and configurations.

## Hardware Requirements

- Intel 8085 microprocessor
- Intel 8255 Programmable Peripheral Interface (PPI)
- RAM chips to be tested
- Supporting circuitry (e.g., address decoder, clock generator)

## Software Requirements

- Assembler for 8085 assembly language (e.g., ASEM-85)
- Burner software for programming the 8255 PPI
- Serial communication software for interfacing with the tester (optional)

## Usage

1. Assemble the provided 8085 assembly code using the assembler.
2. Program the 8255 PPI with the required configuration for interfacing with the RAM.
3. Connect the hardware components according to the schematic.
4. Power up the system and run the RAM tester program on the 8085 microprocessor.
5. Follow on-screen instructions to initiate the testing process.
6. Monitor the test results and logs to determine the RAM's functionality.

## Schematic

![RAM Tester Schematic](https://drive.google.com/file/d/1uxYkIrJ8L31LmVN--OdTZCDg3ddIiU3K/view?usp=sharing)

## Testing Procedure

1. **Power-On Test:** Ensure all components are powered up correctly.
2. **Initialization:** Initialize the 8255 PPI and setup necessary configurations.
3. **Address Generation:** Generate address signals for accessing different memory locations in the RAM.
4. **Write Test:** Write specific bit patterns to each memory location in the RAM.
5. **Read Test:** Read back data from the RAM and compare with the expected values.
6. **Error Handling:** Log any errors encountered during testing.
7. **Result Display:** Display the test results including pass/fail status and error messages.


