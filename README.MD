# Triple High Side Smart Switch Node

Compact power management board intended to control three high-side DC loads. The node provides current monitoring of each load. Temperature and supply voltage are also monitored. This node works with other CAN-CTL modules using the robust CAN bus interface.

<IMG src="https://github.com/gordonthree/SW-SMART-TRI-HIGH/blob/main/SW-SMART-TRI-HIGH.png?raw=true" width=480>

* STM32G0B1KBTx 32-pin microcontroller
* Three BTS7002 Profet Smart Switches for high side loads, firmware limited to 15 amps each
* Microchip MCP2562 isolated CAN bus transceiver
* Automotive grade 5v switchmode power supply and linear 3.3v regulator
* Voltage divider to monitor supply voltage
* Switch current monitoring and diagnostics
* Three position screw terminal block for CAN bus connection
* Five position screw terminal block for power-out
* Heavy duty terminal block connectors for power in
* Headers for SWD programming and USART1 debug serial port

