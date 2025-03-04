# SPI_SV_Verification
This project implements the Verification module of the SPI (Serial Peripheral Interface) communication protocol using SystemVerilog (SV). It consists of two main components:

  Design_SPI: This file contains the RTL design for the SPI Master and SPI Slave modules. The Master initiates communication, and the Slave responds based on the SPI protocol.
  TestBench_SPI: This file contains the testbench code, which verifies the SPI protocol using different classes such as drivers, monitors, scoreboards, and sequences. The testbench ensures that the SPI Master and     Slave modules communicate correctly under various test scenarios.

The verification environment follows an object-oriented approach, leveraging SystemVerilog classes to create a modular and reusable testbench. While UVM is not used, the structure ensures a scalable and organized verification methodology.

Steps to be followed:
1. Copy & Run the Code in EDA Playground
2. Go to EDA Playground.
3. Select the SystemVerilog + UVM simulation environment (e.g., QuestaSim, VCS, or Xcelium).
4. Create two files:
  Design_SPI.sv → Copy & paste the SPI Master-Slave design code.
  TestBench_SPI.sv → Copy & paste the verification testbench code.
5. Run the simulation and verify that the SPI protocol is functioning correctly.

