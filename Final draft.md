# EVRE LEVEL 1 TASKS REPORT

# Task : Auto Night Lamp Using LED for Electric Vehicles

### OBJECTIVE :

To Design a light-sensitive LED circuit using an LDR and a BJT transistor. The LED turns on when light levels drop or if the surrounding gets dark 

Simulating an automatic headlamp system for EVs. Test using a mobile flashlight for light detection.

### My Learnings : 

### LDR (Light Dependent Resistor)

A Light Dependent Resistor (also known as a photoresistor) is a passive electronic component whose electrical resistance decreases as the intensity of incident light increases. 

LDRs are commonly used in applications such as automatic street lighting, camera light meters, and ambient light sensors in smartphones due to their ability to detect light levels without physical contact. 

### BJT Transistor :

A Bipolar Junction Transistor (BJT) is a three-terminal semiconductor device that uses both electrons and holes as charge carriers to control a large collector current via a small base current.

### Outcome :

Auto night lamp system for EVs demonstrated with mobile flashlight simulation.

## [VIDEO](https://youtube.com/shorts/NNr7aEieCLs?feature=share)



# Task : Utilizing Transistors as Switches and Voltage Regulators 

### Objective :

To Understand how transistors can be used as digital switches and basic voltage regulators. Begin by using an Arduino to send a digital signal to the base of a transistor to control an LED (ON/OFF).

Then, explore how a transistor introduces voltage drop by simulating a circuit in Tinkercad

To observe how voltage reduces across the LED after adding a transistor.

### My Learnings :

### NPN Transistor :

An NPN transistor is a type of bipolar junction transistor (BJT) constructed with a p-type semiconductor layer sandwiched between two n-type semiconductor layers.  It features three terminals: the emitter, base, and collector, with the emitter arrow in its schematic symbol pointing outward to indicate conventional current flow. 

When the aurdino output is high i.e 5V the transistor turns on and the LED glows

When the aurdino output is low i.e 0V the transistor turns off and the LED stops glowing 

A transistor is not a perfect switch.
When ON,there is a small voltage drop between Collector and Emitter.

This is called : Collector-Emitter Saturation Voltage 

#### What is an Voltage Regulator 

A voltage regulator is a circuit that keeps an output voltage steady even when the input voltage or load changes. For example, it might turn a varying 12–16 V supply into a stable 5 V output.

#### Diode :

A diode is an electronic component that lets current flow mainly in one direction—like a one-way valve for electricity.

### Outcome :

Gaining practical knowledge of using a transistor as a switch and insight into voltage regulation principles relevant to buck converters.


## [VIDEO](https://youtu.be/cmxROhQFnAw)


#  Task : Point Turn of a Vehicle with Ultrasonic Sensor

### OBJECTIVE :

Building an obstacle-avoiding robot using an HC-SR04 ultrasonic sensor, Arduino, and a motor driver.
The vehicle should detect obstacles and perform a point turn by rotating in place to change direction.
It combines sensor data processing with differential motor control.

### MY LEARNINGS :
 
#### HC-SR04 Ultrasonic Sensor
The range and working of an HC-SR04 sensor.
It's range varies from 2cm - 400cm.
It operates at 5v dc supply.
Accuracy is of ±3 mm.
Objects must be roughly perpendicular to sensor for reliable detection.

#### Motor Driver 

The Motor Driver can both go in forward and backward direction based upon the electic signal sent to it. 
This helps the bot to move in all directions (mainly in the direction where there are no obstacles).

### OUTCOMES
Vehicle can detect and avoid obstacles.
Performs point turn autonomously when close to an object.


## [VIDEO](https://www.youtube.com/watch?v=93gUBhUaNdY)



#  Task : Temperature and Humidity Detection

### OBJECTIVE :

Using an LM35 analog temperature sensor to monitor ambient or localized heat (e.g., near a soldering iron). When temperature exceeds a threshold, turn on an LED using a BJT as a switch. In parallel, use the DHT11 digital sensor to read and display temperature and humidity on a 16x2 LCD

### MY UNDERSTANDINGS :

An LM35 temperature sensor is an sensor which measeures temperature and sends analog signals to the micro controller so that it can read the data and display temperature in human understandable form 

A DHT11 digital sensor is also used to read temperatire , it measures humidity as well and sends the data in digital signals form rather than analog signals 
its more accurate and modern compared to the LM35 sensor 

### Outcome :

Understand analog and digital sensor interfacing.

Implement threshold-based switching and data display.


## [VIDEO](https://youtube.com/shorts/jzfPqTmDfM4)



# TASK : Wireless Charger Simulation on Tinkercad

### OBJECTIVE :

Generate PWM signal by aurdino.

The transmitter coil produces an alternating magnetic field.

The receiver coil was intended to receive energy through inductive coupling.

The LED represents the successful transfer of energy wirelessly.

### MY UNDERSTANDING :

Tinkercad has limitations in simulating actual electromagnetic induction, so the LED may not illuminate exactly as it would in a real circuit.

Understood the principle of wireless power transfer using inductive coupling.

Learned the role of transmitter and receiver coils.

Understood how PWM can be used to drive the transmitter circuit.

Gained knowledge of the basic working principle of wireless charging systems.

### Outcome :

Understand basic working of wireless charging systems.

![image](WC.jpg)




# TASK : Battery Capacity Measurement

### Objective : 

Monitoring the voltage of a Li-ion battery using analog input on Arduino. 

Use a MOSFET Transistor as a switch to disconnect the load when voltage drops below a safe threshold.

Ensures safe battery operation and demonstrates basic battery protection logic.

### My Understandings :

### Mosfet Transistor :

It is a Transistor which is used to control the voltage in a circuit it requires very low voltage to operate and it can concontrol very high voltage in the circuit

It acts as an internal automatic switch which inhibits the flow of voltage if its too high ensuring that the circuit doesnot fail and the battery doesnot get damaged

It has 3 pins:

1) The Gate pin 
2) The Drain pin
3) The Source pin

### Outcome :

Demonstrate battery protection via voltage monitoring and switching

## [VIDEO](https://youtu.be/fAyzLbWAqTs)



# Task : Battery Charging

### Objective :

Charge the Li-on battery using solar panels and a solar charging module

### My Understandings :

### Solar Pannels :

Solar panels are devices that use photovoltaic (PV) technology to convert sunlight directly into electricity.

Which is then converted by an inverter into Alternating current (AC) for use.

### Li-ion Battery Charging Module :

A lithium battery charging module is a compact electronic circuit designed to safely charge Li-ion or LiPo batteries, such as popular 18650 cells, by managing critical parameters like constant current and constant voltage.  These modules, often based on chips like the TP4056, typically provide a 1A charge current for 3.7V single-cell batteries

### Boost Converter :

A boost converter, also known as a step-up converter, is a DC-to-DC converter that increases an input voltage to a higher output voltage while proportionally decreasing the output current to conserve power. 

### Outcome :

Understood the practical implementation of solar-based charging


## [VIDEO](https://youtu.be/f-xeOJilFeM)


# TASK : RLC circuit simulation in MATLAB

### OBJECTIVE : 

Learning the basics of Simulink and SIMSCAPE in MATLAB by designing a simple RLC or transistor-based circuit.

Simulate voltage, current, and frequency responses over time using virtual probes and scopes

### MY LEARNINGS :

#### MUX BLOCK :

It's a block in simulink which combines multiple input signals and combines it into a single virtual vector output , without changing it's underlying data , structure.

#### INTEGRATOR BLOCK :

IT integrates an input signal with respect to time 

#### SCOPE :

IT's an output model block used to visually dispay time-domain signals during a simulation 

#### GAIN BLOCK :

It is used to ,ultiply a signal by a constant value or gain , mainly used to amplify a signal 

### OUTCOME :

Understand MATLAB-Simulink for circuit modeling and waveform analysis.

## SCOPE :

![image](RLC1.png)

## Circuitry :

![alt text](RLC2.png)


## Why simscape was not used and what changes was made to the task :

This RLC circuit was modeled in Simulink using Gain and Integrator blocks because the Simscape Electrical library was not available.

The method is based on the mathematical equations of a series RLC circuit. The resistor is represented by a Gain block using. 

The inductor is represented by a Gain of 1/L followed by an Integrator, which calculates the circuit current from the inductor voltage.

The capacitor is represented by a Gain of 1/C followed by another Integrator, which calculates capacitor voltage from current. 

The Sum block applies Kirchhoff’s Voltage Law, where the input voltage is equal to the sum of resistor, inductor, and capacitor voltages. Therefore, the model produces the same time-domain current and voltage response as a series RLC circuit, using equations rather than physical circuit blocks.




# TASK : Solar Tracker

### OBJECTIVE :

Use LDRs and a servo motor controlled by Arduino to orient a solar panel toward the strongest light source.

The system maximizes solar energy collection using dual LDR comparison logic and basic actuator control.

### MY LEARNINGS ;

#### LDR :

It stands for light dependent resistor 

When there is no solar power or less intensive power then the mobility of thge electrons will be less and the resistance of the LDR will be really high

When the solar power is more or high intensity then the mobility of the electrons willl be high and the LDR will have lower resistance value 

#### Solar and servo Movement

The LDR detects out of the 2 which receives the maximum light and the servo mototr on which the solar pannel is mounted it moves in that direction  

The arduino tells the servo motor by what angle to move so as to that the solar pannel receives the maximum sun light 

If both the LDR's are receiving sunlight then the one receiving maximum sunlight is targeted and the solar pannel isrotated in that direction which is mounted on the servo motor.

### OUTCOME :

Achieve energy maximization through sun-tracking mechanisms.



## [VIDEO](https://youtu.be/UblQfe1kg7I)



# TASK - LED Brightness Control Using PWM and MOSFET

### OBJECTIVE :

Use an Arduino and an N-channel MOSFET to control LED brightness through Pulse Width Modulation (PWM). The Arduino sends a signal to the MOSFET gate, allowing current flow between the drain and source. By varying the PWM duty cycle, you can control the LED brightness  higher duty cycle means more brightness, and lower duty cycle means dimmer output.

### MY LEARNINGS :

#### N CHANNEL MOSFET :

A MOSFET (Metal-Oxide-Semiconductor Field-Effect Transistor) is a type of electronic component used to switch or amplify electrical signals in circuits

N CHANNEL MOSFET TRANSISTOR:a type of electronic switch or amplifier that uses voltage to control the flow of current, using electrons as the main charge carriers

IT HAS :

a) GATE : The control pin. It turns the device on or off.
b) SOURCE : The pin where current enters (or leaves) the channel.
c) DRAIN : The pin where current leaves (or enters) the channel.

#### PWM :

is a digital technique for controlling analog power by rapidly switching a signal between on and off.

Duty Cycle: This is the percentage of time a signal stays in the "ON" state during a single cycle. A 100% duty cycle means full power, while 0% means zero power.

Frequency: This measures how fast the complete on-off cycle repeats per second (measured in Hertz). High frequencies prevent visible flickering in lights or audible noise in motors.


### OUTCOME :

Understood how MOSFETs operate as switches and how PWM controls power delivery efficiently

Making MOSFETs ideal for such applications

## [VIDEO](https://youtu.be/cevJkOc09As?si=i8TZOn8cC9FxRYMw)



# TASK - AC to DC Conversion and Observing Direct DC vs. Rectified DC

### OBJECTIVE :

Simulate an AC signal using Arduino PWM output, then convert it to DC using half-wave rectification. Use a diode to block the negative cycle and a capacitor to filter the signal, producing rectified DC. Compare the LED brightness when powered by a direct DC source (battery) versus rectified DC output.

#### MY LEARNINGS :

#### DIODE :

a two-terminal electronic component that acts as a one-way valve for electrical current, allowing it to flow in only a single direction

#### RECTIFICATION :

It is the process of converting an alternating current (AC), which changes direction back and forth, into a direct current (DC), which flows in only one direction

### OUTCOME :

Understood the basics of AC to DC conversion, diode rectification, and how filtering improves DC quality.
Observed that LEDs glow brighter on stable DC compared to filtered rectified DC.

## [VIDEO](https://youtu.be/Wu6m6rCRhRE?si=yxYstmAFsNU9qvd-)



# Task - Generating an AC-Like Signal Using a 555 Timer and MOSFET

### OBJECTIVE :

Use a 555 Timer IC to generate a square wave signal and drive two N-channel MOSFETs in a push-pull configuration. As the timer alternates between HIGH and LOW, one MOSFET connects the load to ground while the other pulls it to Vcc, producing an AC-like square waveform. The MOSFETs amplify the signal, enabling the circuit to handle higher current loads.

### MY LEARNINGS :

#### 555 timer :

The 555 timer IC is a tiny, popular integrated circuit used to generate pulses, delays, and continuous wave signals in electronic circuits

It is named so cause it has 3 - 5 kilo ohm resistors in it

A 555 timer primarily controls voltage levels internally to make its timing decisions

In positive cycle the wave rises from 0v to 9v showing AC wave like nature in the osciloscope and in the negative cycle the direction of the wave gets reversed and appears in the opposite direction dropping from 9v to 0v 

### OUTCOMES :

Learn how to convert DC to an AC-like signal using a 555 Timer and MOSFETs. Observe power amplification

## [VIDEO](https://youtu.be/S2K7sxfFGwA?si=STtKgbJDZDbuY8Qx)



# TASK : Building a Basic H-Bridge Motor Driver using MOSFETs 

### OBJECTIVES : 

You are required to design and build a basic H-Bridge motor driver circuit using N-Channel and/or P-Channel MOSFETs. The H-Bridge should allow you to control the direction of a DC motor using digital signals (e.g., from Arduino or switches).

### MY LEARNINGS :

#### H-BRIDGE :

An H-bridge is an electronic circuit that reverses the polarity of the voltage applied to a load, allowing DC motors to run forward or backward

IT basically acts as a H shaped bridge 

When the polarity is not reversed current flows through one switch and the DC mototr spins in one direction 

When the polarity is reversed the initial switch will be in off state and anew switch will be on and current flows through that line and the dc motor spins in the opposite direction 

It is called a bridge because it allows a pathway for the current to flow 

### OUTCOME :

Demonstrate the ability to control the rotation direction of a DC motor using an H-Bridge configuration.


## [VIDEO](https://youtu.be/Sg0uAzjKgjw?si=aCqmvssqrQgkEVKU)


