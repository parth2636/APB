APB Protocol Project :
This project implements an AMBA APB (Advanced Peripheral Bus) interface in Verilog, with a custom-designed APB Master RTL and a Slave Testbench. 
The environment supports running multiple test scenarios, where individual tests can be selected dynamically using $test$plusargs.


Features:

APB Master RTL

		Implements APB protocol signals (PADDR, PWRITE, PWDATA, PRDATA, PSEL, PENABLE, PREADY).
		Supports configurable read and write transfers.

APB Slave Testbench

		Simulates APB slave responses with wait state handling.
		Implements PSLVERR logic for error response cases.

Flexible Test Selection

		Multiple test features included.
		Each test can be run individually using +testname without modifying the testbench
		Suitable for automation and regression flows.


