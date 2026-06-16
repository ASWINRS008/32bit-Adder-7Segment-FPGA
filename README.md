# 32-Bit Adder with 7-Segment Display Output

Language: Verilog | FPGA: Intel Cyclone IV | Tool: Quartus II / ModelSim | Type: FPGA Hardware Design

An FPGA hardware implementation of a 32-bit adder. The design computes the sum of two 32-bit inputs and displays the resulting output on 7-segment displays.

## Design Modules

1. **32-Bit Adder**: Computes the binary sum.
2. 2. **Binary to BCD Converter**: Converts the binary output into Binary Coded Decimal (BCD) format.
   3. 3. **7-Segment Decoder**: Decodes the BCD digits to drive the segment lines of the FPGA board displays.
      4. 4. **Frequency Divider / Multiplexer**: Alternates display control signals to drive multiple digits using minimal IO pins.
        
         5. ## FPGA Pin Mapping
        
         6. Contains pin configurations targeting Intel Cyclone IV E FPGA boards.
        
         7. ## Code Structure
        
         8. - `adder_32bit.v`: 32-bit adder module.
            - - `bcd_converter.v`: Binary to BCD conversion logic.
              - - `seven_segment.v`: 7-segment decoder and multiplexing unit.
                - - `top_module.v`: Top-level integration file.
                 
                  - ## Author
                 
                  - Aswin R S - M.Tech VLSI and Microelectronics
                  - GitHub: https://github.com/ASWINRS008
