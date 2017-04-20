# true-rng

Hardware design to create a true-random number generator.
See https://hackaday.io/project/21054-true-random-number-generator for details.

The EAGLE files are incomplete and unchecked. I have hand-edited the symbols
and footprints based on miscellaneous EAGLE data that I have found spread around. It is not to be trusted yet! It needs checking. Also the electrical design has not been prototyped or simulated.

__noise_amplifier.xlsx__

The spreadsheet noise_amplifier.xlsx has the design equations and
documentation for the analog circuit design. I can explain the design process
in more detail in the hackaday.io project if anyone is interested.
The technique could be used to design buffer amplifiers for other types of sensors.

__vreg_local.lbr__

A local library with symbols, footprints, and maps.

__analog_rng2.sch__

The schematic so far.

__analog_rng2.brd__

The board layout, work-in-progress.

__LICENSE__

Copyright 2017 Tom Anderson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

