# Switching Circuits

## Motivation
Designing a buck and boost converters and simulate them using PSpice to understand how to select suitable componenets. 

## Description 
  Switch mode DC to DC converter are used to convert unregulated dc input into a controlled dc output at desired voltage level. 
The average output voltage is controlled by controlling the switch on off ratio, which is known as the duty ratio. In here 
only non-isolated coveters are used and these converters are analyzed in the steady state.
  
  Following assumptions are carried out when designing the switching circuits Switches are treated as ideal components with no inductive or 
capacitive elements. DC input voltages to the converter contains no internal impedances and source is a low ripple dc voltage source. 
Output supplied to the load can be represented by equivalent resistance.

### 1. Buck Converters 
  Buck converter is a step-down converter that produces a lower average output voltage than the input voltage. It is mainly used in 
regulated DC power supplied and Motor Controllers. 
  
  Output voltage of the buck converter is controlled by varying the duty ratio and average 
output voltage ratio varies linearly with control voltage. When buck converter component values are determined Continuous Conduction 
Mode is taken as the operating mode of buck converter.

### 2. Boost Converters
Boost converter is a step-up converter. They are mainly used in regulated DC Power supplies and the regenerative braking of DC Motors. 
Output voltage of buck converter is always greater than input voltage.(step-up)

Output voltage of the boost converter is controlled by varying the duty ratio and, average output voltage ratio varies linearly with 
control voltage. When boost converter component values are determined, Continuous Conduction Mode is taken as the operating mode of 
buck converter.
