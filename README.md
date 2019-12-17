# ArduinoPy 
ArduinoPy is a Arduino IDE Library that provides a "Python VM Engine" hosted on top of the Arduino IDE environment. This allows adding Python scripting functionality within an Arduino Sketch.

Unlike other microcontroller Python implementations, ArduinoPy does not try to replace the Arduino development environment with a bare metal Python framework or try to implement a full Python framework with a parser,compiler, or repl ... no modules trying to handle all aspects of the microcontrollers hardware. 

Rather, ArduinoPy takes a simpler approach by only implementing a bare minimal Python VM environment that is built up from and leveraging the Arduino IDE existing libraries and framework. Also, ArduinoPy only has a bytecode interpreter virtual machine engine ... no eval() or REPL ... per say ... but any bytecode can be executed either from ram, rom, or flash ... a full c function interface is provided to map existing Arduino code into the Python environment ... as well as the ability to call Python (Bytecode) from Arduino sketches.

**Resources**

https://github.com/micropython/micropython
