# \# 1-to-4 Demultiplexer Using BJTs

# 

# \## Project Overview

# 

# This project implements a 1-to-4 demultiplexer using discrete BC547 NPN transistors instead of packaged logic ICs.

# 

# The circuit uses three cascaded 1-to-2 demultiplexer stages to route a single digital input to one of four output lines according to two select lines, S1 and S0.

# 

# \## Working Principle

# 

# A demultiplexer takes one input and routes it to one of several outputs based on the select lines.

# 

# \- S1 S0 = 00 → Y0

# \- S1 S0 = 01 → Y1

# \- S1 S0 = 10 → Y2

# \- S1 S0 = 11 → Y3

# 

# The circuit is built using three cascaded 1-to-2 demultiplexer stages.

# 

# \## Components Used

# 

# \- BC547 NPN transistors

# \- 100 kΩ, 4.7 kΩ and 1 kΩ resistors

# \- 5 mm LEDs

# \- +5 V DC power supply

# \- Breadboard

# \- Jumper wires

# \- 3-position DIP switch

# \- Digital multimeter

# \- Digital oscilloscope

# \- Function generator

# 

# \## Truth Table

# 

# | S1 | S0 | D | Y0 | Y1 | Y2 | Y3 |

# |----|----|---|----|----|----|----|

# | 0  | 0  | 1 | 1  | 0  | 0  | 0  |

# | 0  | 1  | 1 | 0  | 1  | 0  | 0  |

# | 1  | 0  | 1 | 0  | 0  | 1  | 0  |

# | 1  | 1  | 1 | 0  | 0  | 0  | 1  |

# | X  | X  | 0 | 0  | 0  | 0  | 0  |

# 

# \## Experimental Results

# 

# The circuit successfully routed the input signal to the selected output for all combinations of S1 and S0.

# 

# Testing was performed using a function generator and oscilloscope. A square wave input of approximately 15 Hz was also tested.

# 

# Some signal loss and differences in output voltage were observed between the output channels.

# 

# \## Project Files

# 

# \- \*\*Final report\*\* 

# \- \*\*project proposal\*\*

# \- \*\*Project Images\*\* — Project construction and circuit photographs

# \- \*\*Testing\*\* — Testing results, oscilloscope images and videos

# 

# \## Project Report

# 

# The complete project report is available in the `Documents` folder.

# 

# \## Team Members

# 

# \- Nahiyan Nafis

# \- Abdullah Al Jafi

# \- Mueid Morshed Aurnib

# \- Mohammad Safat Intisar

# \- Prottoy Islam Riad

# 

# \## Institution

# 

# \*\*Islamic University of Technology (IUT)\*\*

# 

# \## Project Title

# 

# \*\*Implementation of a 1-to-4 Demultiplexer Using BJTs\*\*

